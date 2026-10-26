---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
url: /tr/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Bu sınıf, uzun süren görevlerde kesintinin talep edilip edilmediğini bildirmek için kullanılacak token'ı temsil eder.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Kesintinin talep edilip edilmediğini gösteren true değerini döndürür. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Kesinti talep edildiğinde bir istisna fırlatır. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```

Kesintinin talep edilip edilmediğini gösteren true değerini döndürür.

**Döndürür:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```

Kesinti talep edildiğinde bir istisna fırlatır.