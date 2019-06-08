# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

abstract_target 'MP' do
  use_frameworks!
  inhibit_all_warnings!
  platform :ios, '9.0'
  target 'VimeoUploaderSample' do
    pod 'GoogleAPIClientForREST/YouTube', '~> 1.2.1'
    pod 'GoogleSignIn', '~> 4.0'
    pod 'ObjectiveDropboxOfficial'
    pod 'VimeoNetworking', '~> 4.0.0'
    pod 'VimeoUpload', :git => 'https://github.com/Vimeo/VimeoUpload', :branch => 'master'
  end
end
