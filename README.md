# Employee Directory: React Native Sample App

## Installation Instructions

1. Follow the React Native getting started instructions to install React Native

1. Create a new React Native app named EmployeeDirectory:
    ```
    react-native init EmployeeDirectory
    cd EmployeeDirectory
    react-native run-ios
    ```
1. Clone the sample app repository:
    ```
    git clone https://github.com/sethigourav/employee-directory-react-native.git
    ```

1. Copy the `app` folder from `employee-directory-react-native` into your `EmployeeDirectory` project folder

1. Open `index.ios.js`. Delete the existing content and replace it with:
    ```
    import {AppRegistry} from 'react-native';
     
    import EmployeeDirectoryApp from './app/EmployeeDirectoryApp';
     
    AppRegistry.registerComponent('EmployeeDirectory', () => EmployeeDirectoryApp);
    ```

1. Save index.ios.js

1. Hit Cmd + R to refresh the app in the emulator