# React-Navigation
how to install React Navigation in project code
Cara menggunakan React Navigation v6.x

1. Install node.js & expo
```
npm install --global expo-cli
```
2. Cek version expo
```
expo --version
```
Note : pilih lokasi folder untuk menepatkan file project

3. New project React Native
```
expo init nama_project
```
Next: jalankan didalam folder project || cd nama_project 

4. Install React Navigation
```
npm install @react-navigation/native
```
```
expo install react-native-screens react-native-safe-area-context
```

5. Install Stack Navigator
```
npm install @react-navigation/native-stack
```

6. Start Project
```
expo start
```

add :
```
import { NavigationContainer } from '@react-navigation/native';
import { createNativeStackNavigator } from '@react-navigation/native-stack';
```
or 

copy template app.js
