![Example](https://raw.github.com/omerucel/freetts-sample-application/master/screenshot.png)

```java
Voice voice = VoiceManager.getInstance().getVoice("kevin16");
voice.allocate();
voice.speak(jTextField1.getText());
voice.deallocate();
```

# Installation

```shell
$ mvn compile
```
