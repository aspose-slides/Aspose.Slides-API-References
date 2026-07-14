---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: यह क्लास टोकन का प्रतिनिधित्व करती है जिसे लंबी अवधि के कार्यों के लिए संकेत देने हेतु प्रयोग किया जाता है कि क्या व्यवधान का अनुरोध किया गया था।
type: docs
url: /hi/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

यह क्लास टोकन का प्रतिनिधित्व करती है जिसे लंबी अवधि के कार्यों के लिए संकेत देने हेतु प्रयोग किया जाता है कि क्या व्यवधान का अनुरोध किया गया था।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | यदि विघटन का अनुरोध किया गया हो तो सत्य लौटाता है। |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | यदि विघटन का अनुरोध किया गया हो तो एक अपवाद फेंकता है। |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


यदि विघटन का अनुरोध किया गया हो तो सत्य लौटाता है।

**वापसी:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


यदि विघटन का अनुरोध किया गया हो तो एक अपवाद फेंकता है।