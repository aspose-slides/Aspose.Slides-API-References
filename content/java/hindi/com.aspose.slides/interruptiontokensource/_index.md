---
title: InterruptionTokenSource
second_title: Aspose.Slides के लिए Java API संदर्भ
description: स्रोत का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/interruptiontokensource/
---
**Inheritance:**
java.lang.Object
```
public class InterruptionTokenSource
```

[InterruptionToken](../../com.aspose.slides/interruptiontoken) का स्रोत दर्शाता है।
## कंस्ट्रक्टर

| Constructor | Description |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | एक नया [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) बनाता है। |
## मेथड्स

| Method | Description |
| --- | --- |
| [getToken()](#getToken--) | इस [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) से बंधा नया टोकन लौटाता है। |
| [isInterruptionRequested()](#isInterruptionRequested--) | यदि विघटन का अनुरोध किया गया है तो true लौटाता है, अन्यथा false। |
| [interrupt()](#interrupt--) | विघटन के लिए अनुरोध प्रारंभ करता है। |
### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```

एक नया [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) बनाता है।

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```

नया टोकन जो इस [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) से बंधा है, लौटाता है।

**रिटर्न:**  
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

यदि विघटन का अनुरोध किया गया है तो true लौटाता है, अन्यथा false।

**रिटर्न:**  
boolean
### interrupt() {#interrupt--}
```
public final void interrupt()
```

विघटन के लिए अनुरोध को प्रारंभ करता है।