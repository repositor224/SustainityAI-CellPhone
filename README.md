

📁 **Android_ChatGPT Repository**

Welcome to the Android_ChatGPT repository! This repository contains the source code for a chat application that utilizes the OpenAI API and integrates with OkHttp. The app enables users to have conversations with an AI model powered by OpenAI's GPT-3 language model.


![presentationopen-ai-chat-gpt4-3pptx-1-2048](https://github.com/usamahussaindev/NextGPT-OpenAi-API/assets/118635657/efa601d2-3cd3-4fce-bccc-14373791a209)





🎉 **Features**

- Chat with an AI model using OpenAI's powerful GPT-3 language model.
- Utilizes OkHttp library for seamless API integration.
- Simple and user-friendly interface for smooth conversation flow.<br>  
![Screenshot 2023-07-07 155733](https://github.com/Usamahussain56/NextGPT/assets/118635657/b537ac88-229d-4a95-b254-c61694b0b274)<br>

📋 **Requirements**

To run this app, you will need the following:

- An OpenAI API key to access the language model.
- Android Studio or any other Android development environment to work with the project.
- A device or emulator running Android 4.4 or higher.

🚀 **Getting Started**

To get started with the Android_ChatGPT app, follow these steps:

1. Open the project in Android Studio.
2. In the `MainActivity.java` file, locate the line `Replace YOUR_API_KEY` and replace `YOUR_API_KEY` with your own OpenAI API key.
3. Build and run the app on an Android device or emulator.

**Common Error**
1. Dependency 'androidx.activity:activity:1.9.1' requires libraries and applications that depend on it to compile against version 34 or later of the Android APIs.

Solution: go to the build.gradle (Easy ChatGPT) and change the following line:

`plugins {
   id 'com.android.application' version '7.3.0' apply false
   id 'com.android.library' version '7.3.0' apply false
}
`
into

`plugins {
   id 'com.android.application' version '8.0.2' apply false
   id 'com.android.library' version '8.0.2' apply false
}`

For gradle.app file, change Line 7 from compileSdk 34 to compileSdk 35, change Line 12 from targetSdk 34 to targetSdk 35.

2. Failed to Load responses due to internal error

This error represents that your OpenAI account does not have sufficient funds. Add more funds in your account to solve this problem




🤝 **Special Thanks**

Special Thanks would be given to usamahussaindev for his project in NextGPT-OpenAI-Development, which has the following link: https://github.com/usamahussaindev/NextGPT-OpenAI-API-Integration.

"# SustainityAI-CellPhone" 
