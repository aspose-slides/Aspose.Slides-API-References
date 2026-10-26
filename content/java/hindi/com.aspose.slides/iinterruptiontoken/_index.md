---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: यह क्लास टोकन का प्रतिनिधित्व करती है जिसका उपयोग लंबी चलने वाले कार्यों को संकेत देने के लिए किया जाता है कि क्या बाधा का अनुरोध किया गया है।
type: docs
url: /hi/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

यह क्लास टोकन का प्रतिनिधित्व करती है जिसका उपयोग लंबी चलने वाले कार्यों को संकेत देने के लिए किया जाता है कि क्या बाधा का अनुरोध किया गया है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | यदि बाधा का अनुरोध किया गया हो तो true लौटाता है। |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | यदि बाधा का अनुरोध किया गया हो तो अपवाद फेंकता है। |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

यदि बाधा का अनुरोध किया गया हो तो true लौटाता है।

**वापसी:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

यदि बाधा का अनुरोध किया गया हो तो अपवाद फेंकता है।