---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Reference
description: स्रोत का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

स्रोत का प्रतिनिधित्व करता है [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken).
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getToken()](#getToken--) | इस [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) से बांधा हुआ नया टोकन वापस देता है। |
| [isInterruptionRequested()](#isInterruptionRequested--) | यदि बाधा का अनुरोध किया गया हो तो true लौटाता है, अन्यथा false। |
| [interrupt()](#interrupt--) | बाधा के लिए अनुरोध को प्रारंभ करता है। |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```


इस [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) से बांधा हुआ नया टोकन वापस देता है।

**वापसी:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


यदि बाधा का अनुरोध किया गया हो तो true लौटाता है, अन्यथा false।

**वापसी:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```


बाधा के लिए अनुरोध को प्रारंभ करता है।