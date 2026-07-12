---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: This class represents the token to use for signaling long running tasks whether the interruption was requested.
type: docs
url: /tr/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Bu sınıf, uzun süren görevlerin kesintinin istenip istenmediğini belirtmek için kullanılacak token'ı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Kesintinin istendiği durumda true döndürür. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Kesintinin istendiği durumda bir istisna fırlatır. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Kesintinin istendiği durumda true döndürür.

**Döndürür:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Kesintinin istendiği durumda bir istisna fırlatır.