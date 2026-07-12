---
title: InterruptionTokenSource
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Kaynağı temsil eder.
type: docs
url: /tr/com.aspose.slides/interruptiontokensource/
---
**Kalıtım:**
java.lang.Object
```
public class InterruptionTokenSource
```

[InterruptionToken](../../com.aspose.slides/interruptiontoken) kaynağını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [InterruptionTokenSource()](#InterruptionTokenSource--) | Yeni bir [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getToken()](#getToken--) | Bu [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)'ye bağlanan yeni token'ı döndürür. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Kesinti istendiğinde true, aksi takdirde false döndürür. |
| [interrupt()](#interrupt--) | Kesinti talebini başlatır. |
### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```

Yeni bir [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) oluşturur.

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```

Bu [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource)'ye bağlanan yeni token'ı döndürür.

**Döndürür:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Kesinti istendiğinde true, aksi takdirde false döndürür.

**Döndürür:**
boolean
### interrupt() {#interrupt--}
```
public final void interrupt()
```

Kesinti isteğini başlatır.