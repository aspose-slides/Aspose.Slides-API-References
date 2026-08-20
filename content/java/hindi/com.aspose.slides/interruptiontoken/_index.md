---
title: InterruptionToken
second_title: Aspose.Slides for Java API संदर्भ
description: यह क्लास लंबी-चलाने वाली कार्यों को संकेत देने के लिए उपयोग किए जाने वाले टोकन को दर्शाती है कि क्या इंटरप्शन का अनुरोध किया गया था।
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

यह क्लास लंबी-चलाने वाली कार्यों के लिए संकेत देने हेतु टोकन को दर्शाती है कि इंटरप्शन का अनुरोध किया गया था या नहीं।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [getNone()](#getNone--) | खाली इंटरप्शन टोकन को दर्शाता है। |
| [isInterruptionRequested()](#isInterruptionRequested--) | यदि इंटरप्शन का अनुरोध किया गया है तो true लौटाता है। |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | यदि इंटरप्शन का अनुरोध किया गया है तो एक exception फेंकता है। |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```


खाली इंटरप्शन टोकन को दर्शाता है।

--------------------

जब इस टोकन का उपयोग किया जाता है, तो दीर्घकालिक संचालन [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) के माध्यम से कभी बाधित नहीं होगा।

**वापसी:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


यदि इंटरप्शन का अनुरोध किया गया है तो true लौटाता है।

**वापसी:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```


यदि इंटरप्शन का अनुरोध किया गया है तो एक exception फेंकता है।