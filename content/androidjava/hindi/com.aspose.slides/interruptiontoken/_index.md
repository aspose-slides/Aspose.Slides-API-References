---
title: InterruptionToken
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: यह क्लास टोकन का प्रतिनिधित्व करती है जिसका उपयोग लंबी चलने वाले कार्यों के लिए संकेत देने हेतु किया जाता है कि क्या रोकथाम का अनुरोध किया गया था।
type: docs
url: /hi/com.aspose.slides/interruptiontoken/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

यह क्लास टोकन का प्रतिनिधित्व करती है जिसका उपयोग लंबी चलने वाली कार्यों के लिए संकेत देने हेतु किया जाता है कि क्या रोकने का अनुरोध किया गया था।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getNone()](#getNone--) | रिक्त रोकथाम टोकन का प्रतिनिधित्व करता है। |
| [isInterruptionRequested()](#isInterruptionRequested--) | यदि रोकथाम का अनुरोध किया गया हो तो true लौटाता है। |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | यदि रोकथाम का अनुरोध किया गया हो तो एक अपवाद फेंकता है। |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


रिक्त रोकथाम टोकन का प्रतिनिधित्व करता है।

--------------------

लंबी चलने वाली प्रक्रियाएँ इस टोकन का उपयोग करते समय [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) के माध्यम से कभी बाधित नहीं होंगी।

**वापसी:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


यदि रोकथाम का अनुरोध किया गया हो तो true लौटाता है।

**वापसी:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


यदि रोकथाम का अनुरोध किया गया हो तो एक अपवाद फेंकता है।