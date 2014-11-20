# Uncomment this line to define a global platform for your project
# platform :ios, '6.0'

source 'https://github.com/CocoaPods/Specs.git'

def import_pods
  platform :ios, '8.0'
  pod 'RestKit'
  pod 'Alamofire', git: 'https://github.com/mrackwitz/Alamofire', branch: 'podspec'
  pod 'Stencil', git: 'https://github.com/kylef/Stencil.git'
end

target 'SwiftTorture' do
  import_pods
end

target 'SwiftTortureTests' do
  import_pods
  pod 'LlamaKit', git: 'https://github.com/ashfurrow/LlamaKit', commit: '8a79bc3cd65080e856a1c13d5c3e7ee5f512fbf5'
end
