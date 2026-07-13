---
title: IBiLevelEffectiveData
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Niezmienny obiekt reprezentujący efekt Bi-Level czarno-biały.
type: docs
url: /pl/com.aspose.slides/ibileveleffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Niezmienny obiekt reprezentujący efekt Bi-Level (czarny/biały). Kolory wejściowe, których luminancja jest mniejsza niż podana wartość progowa, są zmieniane na czarne. Kolory wejściowe, których luminancja jest większa lub równa podanej wartości, są ustawiane na białe. Wartości alfa nie są wpływane przez ten efekt.
## Metody

| Metoda | Opis |
| --- | --- |
| [getThreshold()](#getThreshold--) | Zwraca wartość progową. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Zwraca wartość progową. Float tylko do odczytu.

**Zwraca:**
float