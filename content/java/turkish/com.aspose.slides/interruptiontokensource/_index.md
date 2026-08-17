---
title: InterruptionTokenSource
second_title: Aspose.Slides for Java API Referansı
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
| [getToken()](#getToken--) | Bu [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) ile bağlanmış yeni token döndürür. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Kesme istenmişse doğru, aksi takdirde yanlış döndürür. |
| [interrupt()](#interrupt--) | Kesme isteği başlatır. |
### InterruptionTokenSource() {#InterruptionTokenSource--}
```
public InterruptionTokenSource()
```


Yeni bir [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) oluşturur.

### getToken() {#getToken--}
```
public final InterruptionToken getToken()
```


Bu [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource) ile bağlanmış yeni token döndürür.

**Döndürür:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```


Kesme istenmişse doğru, aksi takdirde yanlış döndürür.

**Döndürür:**
boolean
### interrupt() {#interrupt--}
```
public final void interrupt()
```


Kesme isteği başlatır.