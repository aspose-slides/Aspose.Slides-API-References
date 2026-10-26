---
title: InterruptionToken
second_title: Aspose.Slides için Java API Referansı
description: Bu sınıf, uzun süren görevlerde kesintinin istendiğini bildirmek için kullanılacak jetonu temsil eder.
type: docs
url: /tr/com.aspose.slides/interruptiontoken/
---
**Kalıtım:**
java.lang.Object

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Bu sınıf, uzun süre çalışan görevlerin kesintinin istendiğini bildirmek için kullanılacak jetonu temsil eder.
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getNone()](#getNone--) | Boş bir kesinti jetonu temsil eder. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Kesinti istendiğinde true döner. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Kesinti istendiğinde bir istisna fırlatır. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

Boş bir kesinti jetonu temsil eder.

--------------------

Bu jetonu kullanırken uzun süren işlemler [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) aracılığıyla asla kesintiye uğramaz.

**Döndürür:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Kesinti istendiğinde true döner.

**Döndürür:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

Kesinti istendiğinde bir istisna fırlatır.