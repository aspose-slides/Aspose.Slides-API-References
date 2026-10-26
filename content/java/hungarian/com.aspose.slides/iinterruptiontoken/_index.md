---
title: IInterruptionToken
second_title: Aspose.Slides for Java API Reference
description: Ez az osztály azt a tokent képviseli, amelyet a hosszú futású feladatok megszakítási kérésének jelzésére használhat.
type: docs
url: /hu/com.aspose.slides/iinterruptiontoken/
---```
public interface IInterruptionToken
```

Ez az osztály azt a tokent képviseli, amelyet a hosszú futású feladatok megszakítási kérésének jelzésére használhat.
## Módszerek

| Method | Description |
| --- | --- |
| [isInterruptionRequested()](#isInterruptionRequested--) | Igaz értéket ad vissza, ha a megszakítás kérték. |
| [throwIfInterruptionRequested()](#throwIfInterruptionRequested--) | Kivételt dob, ha a megszakítás kérték. |
### isInterruptionRequested() {#isInterruptionRequested--}
```
public abstract boolean isInterruptionRequested()
```


Igaz értéket ad vissza, ha a megszakítás kérték.

**Visszatér:**  
boolean
### throwIfInterruptionRequested() {#throwIfInterruptionRequested--}
```
public abstract void throwIfInterruptionRequested()
```


Kivételt dob, ha a megszakítás kérték.