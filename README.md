# BookStore-React-Native



in assets/fonts we have to copy/paste .ttf files for react-native-vector-icons and for font family or need to update the infoplist in xcode workspace


============INFO============

Only files which have been added/modified after creating a react-native project have been added in the repo

FOR FONTS -

Ensure that your project has contents of /assets/files and react-native.config.js given in the repo.
In terminal (in BookStoreApp) , run the following commands
-> react-native link -> react-native run-ios
FOR ICONS -

yarn add react-native-vector-icons
Update key and values as array in "info.plist" file in current BookStore Xcode folder
key : UIAppFonts
array of Strings: -
AntDesign.ttf
Entypo.ttf
EvilIcons.ttf
Feather.ttf
FontAwesome.ttf
FontAwesome5_Brands.ttf
FontAwesome5_Regular.ttf
FontAwesome5_Solid.ttf
Foundation.ttf
Ionicons.ttf
MaterialIcons.ttf
MaterialDesignIcons.ttf
MaterialCommunityIcons.ttf
SimpleLineIcons.ttf
Octicons.ttf
Zocial.ttf
In terminal (in BookStoreApp) , run the following command {react-native run-ios}
