---
title: IInterruptionTokenSource
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the source of .
type: docs
url: /tr/com.aspose.slides/iinterruptiontokensource/
---```
public interface IInterruptionTokenSource
```

Bu [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) kaynağını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getToken()](#getToken--) | Bu [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)'ye bağlanan yeni token döndürür. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Kesinti talep edildiyse true, aksi takdirde false döndürür. |
| [interrupt()](#interrupt--) | Kesinti için isteği başlatır. |
### getToken() {#getToken--}
```
public abstract IInterruptionToken getToken()
```

Bu [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource)'ye bağlanan yeni token döndürür.

**Döndürür:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Kesinti talep edildiyse true, aksi takdirde false döndürür.

**Döndürür:**
boolean
### interrupt() {#interrupt--}
```
public abstract void interrupt()
```

Kesinti için isteği başlatır.