---
title: IInterruptionToken
second_title: Aspose.Slides for Android via Java API Reference
description: Ez az osztály azt a tokent képviseli, amelyet a hosszú ideig futó feladatok számára a megszakítás kérésének jelzésére használnak.
type: docs
url: /hu/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Ez az osztály azt a tokent képviseli, amelyet a hosszú ideig futó feladatok számára a megszakítás kérésének jelzésére használnak.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Igaz értéket ad vissza, ha a megszakításra kérés történt. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Kivételt dob, ha a megszakításra kérés történt. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Igaz értéket ad vissza, ha a megszakításra kérés történt.

**Visszatér:**
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Kivételt dob, ha a megszakításra kérés történt.