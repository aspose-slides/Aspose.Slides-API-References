---
title: InterruptionToken
second_title: Aspose.Slides for Android via Java API Referansı
description: Bu sınıf, uzun süren görevlerde kesintinin istenip istenmediğini bildirmek için kullanılacak token'i temsil eder.
type: docs
url: /tr/com.aspose.slides/interruptiontoken/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
```
public class InterruptionToken implements IInterruptionToken
```

Bu sınıf, uzun süren görevlerin kesinti isteği alınıp alındığını işaretlemek için kullanılacak token'i temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNone()](#getNone--) | Boş bir kesinti jetonunu temsil eder. |
| [isInterruptionRequested()](#isInterruptionRequested--) | Kesinti isteği alındıysa true döndürür. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Kesinti isteği alındıysa bir istisna fırlatır. |
### getNone() {#getNone--}
```
public static InterruptionToken getNone()
```

Boş bir kesinti jetonunu temsil eder.

--------------------

Bu token kullanıldığında, uzun süren işlemler [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) aracılığıyla asla kesintiye uğramaz.

**Döndürür:**
[InterruptionToken](../../com.aspose.slides/interruptiontoken)
### isInterruptionRequested() {#isInterruptionRequested--}
```
public final boolean isInterruptionRequested()
```

Kesinti isteği alındıysa true döndürür.

**Döndürür:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public final void throwIfInterruptionRequested()
```

Kesinti isteği alındıysa bir istisna fırlatır.