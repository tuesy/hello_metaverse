# Overview

Hello Metaverse is a sample Unity Project for uploading to your own Altspace Template. Follow the [guide](https://buildingthemetaverse.medium.com/how-to-make-your-own-altspace-templates-and-kits-unity-2020-3-9-uploader-2-x-5b40e92bb759) for step-by-step instructions and check the [FAQ](https://buildingthemetaverse.medium.com/altspace-unity-upgrade-faq-9c55cdaa543e) before asking for help in our [Discord](https://altvr.com/discord).

![image](https://user-images.githubusercontent.com/217022/134787263-ec07b850-e95c-4729-987b-371683fceeb0.png)

# Usage

* Clone this repo or download a zip of this repo
* Open the project with Unity Hub (2.x) and Unity (exactly 2020.3.9)
* Menu > AltspaceVR > Templates
* Sign in with your email and password (not the same as your Microsoft Account password)
* Upgrade to the latest Unity Uploader if necessary
* Click "Refresh Template List" (assumes you've already created a Template, per the guide)
* Click ">>> Select a Template" and choose one of your Templates
* Click "Choose a .unity file ------->" and find Assets > Scenes > SampleScene
* Note that "Build for platforms" should only have "Windows" checked
* Click "Build & Upload"
* After it's done, click "Open in browser" and see that a new entry has been added to the "Uploads" table with "20203" and "linear" color space. Until the Upgrade happens you'll need a Preview build (see the FAQ)
* With a preview build, enter a World using the Template you chose and you should see 4 cubes around you.

![image](https://user-images.githubusercontent.com/217022/134787278-21dd776b-c84e-4ce6-b673-3ef70d811c69.png)

# Troubleshooting

* **When I (re)open the project I see a "layout" error and it asks me to load default layout or factory settings** - Try closing the "AltspaceVR" tab before closing the project. This should avoid the bug.
* **How do I create my own Template?** - please follow the guide linked above
* **Why do my selections clear after I Build & Upload** - to avoid accidents
