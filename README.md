# jedit-plugins

The jEdit plugin binaries

The purpose of this project is simply to publish various jEdit plugin binaries to a public repository so they can be easily used by plugin developers.

## Usage

For example, to publish the jEdit Common Controls plugin version 1.7.4 to Bintray, use the following command:

    $ ./gradlew -PpluginName=CommonControls -PpackageName=jedit-common-controls-plugin -Pversion=1.7.4 bintrayUpload
