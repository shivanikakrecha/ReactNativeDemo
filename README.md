# Dependency :-
1. NodeJS
2. NPM
3. React-Native CLI
4. Expo app (install into physical mobile device)

# Installtion Steps :-
# Step 1 :-
Clone this project into your device.

# Create Your New React-Native App Installtion Steps :- 
# Step 1 :- 
Install Node.js or NPM using bellow commnad.
```
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs
```
Alternative for different version of Node.js or OS you can reffer this [link](https://nodejs.org/en/download/package-manager/) .
Now verify your version of installed NPM or Node.js using given commnad.
```
> node -v
> v10.6.0

> npm -v
> 6.2.0
```
# Step 2 :-
Install The React Native CLI.
```
npm install -g react-native-cli
```
Then run the following commands to create a new React Native project.
```
create-react-native-app <Your_AppName>
```
Now start your app with following commnads.
```
cd <Your_AppName>
npm start
```

# step 3 :-
Download Expo app into your mobile device from playstore. (Android or IOS) There is avilable app for both OS. 
More details please visit this [link](https://expo.io/) .

Now follow the steps for execute your native app on your device.
* Step 1 :- 
Open your expo app into mobile device. 
* Step 2 :-
Scan your QR code with the help of your terminal QR code while you start your server using **npm start**. 
If there is some error you have or you will not getting QR code on your terminal screen then you can run its with 
sudo. like **sudo npm start**.

You will get the output of this app on your physical device. 

For more details please visit this professional site of [React-Native](https://facebook.github.io/react-native/) .





