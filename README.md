Xatkit Releases
======

This repository contains the releases of the Xatkit framework. You can download the latest release [here](https://github.com/xatkit-bot-platform/xatkit-releases/releases/tag/2.0.0-SNAPSHOT), or pick the one you need from the [release list](https://github.com/xatkit-bot-platform/xatkit-releases/releases).

 # What's in the box?

Each release contains two artifacts:

- **xatkit_X.Y.Z.zip**: the Xatkit runtime bundled with a list of preset platforms. The Xatkit runtime runs your digital assistants, stores logs and monitoring information, and manages your assistant's life-cycle. The list of bundled platforms is available in the release description.
- **xatkit-update-site_X.Y.Z.zip**: an Eclipse update site containing the Xatkit language editors. The editors allows to define intent libraries, platform specifications, and mix them in complex execution logic that can be executed by the Xatkit runtime. 

# Quick Start

1- Download the [latest release](https://github.com/xatkit-bot-platform/xatkit-releases/releases/tag/2.0.0-SNAPSHOT) and extract *xatkit_X.Y.Z*.

2- Setup the environment variable

**Windows**

Execute `xatkit/install-windows.bat` with administrative rights

**Ubuntu**

Execute `xatkit/install-linux.sh`

*Xatkit Tip: don't waste your time!*

> This operation is only required the first time you install Xatkit

3- Navigate to `xatkit/bin` and start the example digital assistant

The example assistant is a basic web-based bot that greets users, it is defined in `xatkit/examples/GreetingsBot`.

**Windows**

```bash
./start-xatkit-windows.sh ../examples/GreetingsBot/GreetingsBot.properties
```

**Ubuntu**

```bash
./start-xatkit-linux.sh ../examples/GreetingsBot/GreetingsBot.properties
```

The console will log some initialization information, and after a few seconds you should see the following message:

```bash
You can test your chatbot here http://localhost:5000/admin (note that the bots behavior can be slightly different on the test page than when it is deployed on a server)
```

Open your browser and navigate to http://localhost:5000/admin to test your deployed web-based bot!

![Greetings Bot Chatbox](https://raw.githubusercontent.com/wiki/xatkit-bot-platform/xatkit-releases/img/greetings-bot-chatbox-example.png)

# What's Next?

Congratulations, you just started your first Xatkit digital assistant!

You can now have a look at the [tutorial](https://github.com/xatkit-bot-platform/xatkit-dev/blob/master) to learn how assistants are defined with the Xatkit language, or if you are already familiar with it you can take a look at the [documentation](https://github.com/xatkit-bot-platform/xatkit-dev/blob/master) for additional information on Xatkit capabilities. Note that the example Greetings Bot relies on regular expressions to process user inputs, you can take a look at [this tutorial article](https://github.com/xatkit-bot-platform/xatkit-dev/blob/master) to empower your bots with advanced Natural Language Processing and Machine Learning intent extraction.

# Troubleshooting

If you experience any issue with Xatkit you can open an issue on [our tracker](https://github.com/xatkit-bot-platform/xatkit-releases/issues) and we will be happy to help you! Note that we may move your issue to a different repository based on the impacted components.

# Contributing

You want to contribute to Xatkit? We would love to hear from you and provide all the assistance we can! To ease the process we have created the [*Xatkit Development Toolkit* (XDK)](https://github.com/xatkit-bot-platform/xatkit-dev), an all-in-one repository to build, test, and bundle Xatkit.

You can use the XDK to clone the Xatkit repositories and add your awesome contributions. Once you are ready, you can open a pull-request on the repository you updated and we will be happy to review your code and help you!

You have created a brand new platform for Xatkit? You can [contact us]() and we will take a look at it! If you want to increase the visibility of your contribution we can create a dedicated repository for it in the Xatkit organization on Github.