# How to build
```
cd src/person-tracking
npm install
```

# How to run samples
```
cd src/person-tracking
npm run maketarball
```
The above step generates a person-tracking-xxx.tar.gz file.
```
mkdir ~/test
cd ~/test
npm install /path/to/person-tracking-xxx.tar.gz
```

## headless sample
```
cp ./node_modules/person-tracking/example/pt.js .
node pt.js
```
## other headless and headed samples
Other samples can be found in the following link with pt_tutorial_* prefix.
https://github.com/otcshare/realsense_samples/tree/javascript/samples/

# IDL:
the code is based on the ./idl/person-tracking.widl, ./idl/common/realsense-camera.widl, ./idl/common/geometry.widl currently.
