---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Java API Referansı
description: Kaynağı temsil eder.
type: docs
url: /tr/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Bu [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) kaynağını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getToken()](#getToken--) | Bu [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) için yeni token döndürür. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Kesinti istenmişse true, aksi takdirde false döndürür. |
| [interrupt()](#interrupt--) | Kesinti isteğini başlatır. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

Bu [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource) için yeni token döndürür.

**Döndürür:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Kesinti istenmişse true, aksi takdirde false döndürür.

**Döndürür:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

Kesinti isteğini başlatır.