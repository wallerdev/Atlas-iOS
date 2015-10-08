platform :ios, '8.0'

# Import CocoaPods sources
source 'https://github.com/CocoaPods/Specs.git'
source 'git@github.com:layerhq/cocoapods-specs.git'

layerkit_framework_path = '~/Dropbox/Layer/Builds/iOS/LayerKit-0.17.0-pre5'

use_frameworks!

target 'Programmatic' do
  pod 'Atlas', path: '.'
  pod 'LayerKit', path: "#{layerkit_framework_path}"
end

target 'Storyboard' do
  pod 'Atlas', path: '.'
  pod 'LayerKit', path: "#{layerkit_framework_path}"
end

target 'ProgrammaticTests' do
  pod 'KIFViewControllerActions', git: 'https://github.com/blakewatters/KIFViewControllerActions.git'
  pod 'LYRCountDownLatch', git: 'https://github.com/layerhq/LYRCountDownLatch.git'
  pod 'KIF'
  pod 'Expecta'
  pod 'OCMock'
  pod 'LayerKit', path: "#{layerkit_framework_path}"
end

target 'StoryboardTests' do
  pod 'KIFViewControllerActions', git: 'https://github.com/blakewatters/KIFViewControllerActions.git'
  pod 'LYRCountDownLatch', git: 'https://github.com/layerhq/LYRCountDownLatch.git'
  pod 'KIF'
  pod 'Expecta'
  pod 'OCMock'
  pod 'LayerKit', path: "#{layerkit_framework_path}"
end

target 'UnitTests' do
  pod 'Expecta'
  pod 'OCMock'
  pod 'LayerKit', path: "#{layerkit_framework_path}"
end
