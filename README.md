# news_app
A new Flutter project.

## Flutter Version
FLutter 3.13.2

## How to build the project?
You will need to first run some flutter commands to generate some required files
1. To generate assets.dart file
```
flutter packages pub run r_flutter:generate
```
2. To Generate all the other required files using [build_runner](https://pub.dev/packages/build_runner) package
```
flutter pub run build_runner build --delete-conflicting-outputs
```

3. To create splash screen 
```
flutter pub run flutter_native_splash:create
```

4. To create app icon 
```
flutter pub run flutter_launcher_icons  
```

