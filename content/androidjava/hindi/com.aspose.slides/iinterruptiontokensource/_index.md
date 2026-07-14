---
title: IInterruptionTokenSource
second_title: Aspose.Slides Android के लिए Java API संदर्भ
description: स्रोत का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

यह [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) का स्रोत दर्शाता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getToken()](#getToken--) | इस [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) से बंधा नया टोकन लौटाता है। |
| [isInterruptionRequested()](#isInterruptionRequested--) | यदि इंटरप्शन अनुरोधित है तो true लौटाता है, अन्यथा false। |
| [interrupt()](#interrupt--) | इंटरप्शन के लिए अनुरोध को प्रारंभ करें। |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

इस [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) से बंधा नया टोकन लौटाता है।

**रिटर्न:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

यदि इंटरप्शन अनुरोधित है तो true लौटाता है, अन्यथा false।

**रिटर्न:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

इंटरप्शन के लिए अनुरोध को प्रारंभ करें।