STUDYBUDDY — FREE STARTER APP
==============================

Included:
- index.html: the app
- manifest.json: installable web-app metadata
- sw.js: basic offline caching when hosted over HTTPS

FEATURES
- Science multiple-choice quiz with feedback and best score
- Revision notes for current electricity, force/motion, and cell biology
- Personal notes that can be saved/deleted
- Daily study checklist and target
- Progress saved in the browser on the device

IMPORTANT
This is a working starter web app, not an APK and not connected to a live AI model.
It uses local browser storage, so saved data stays on that browser/device.

QUICKEST TEST
1. Unzip this folder on your computer.
2. Open index.html in Chrome to try the features.
3. For Android installation as an app-like shortcut, host the files on an HTTPS static host (for example, GitHub Pages), open the HTTPS URL in Chrome on your Android phone, then use Chrome menu > Install app or Add to Home screen.
   Note: service-worker/offline features require HTTPS or localhost.

TO CREATE A TRUE ANDROID APK
Use MIT App Inventor (https://ai2.appinventor.mit.edu/):
1. Create a project named StudyBuddy.
2. Add a WebViewer component.
3. For an app packaged around this web app, copy the HTML into an asset named index.html and set the WebViewer to open the local asset if supported by the current App Inventor WebViewer version. Alternatively, recreate the features with native App Inventor components for the most reliable result.
4. Use Build > Android App (.apk) to build an APK.
The MIT App Inventor editor/build options may change. Test the APK on your phone before sharing.

MONETIZATION
Do not add ads until the app is tested and useful. Publishing to Google Play requires developer registration and compliance with current policies. A Play Store listing is not included.
