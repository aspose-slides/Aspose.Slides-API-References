---
title: IBiLevelEffectiveData
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Niezmienny obiekt reprezentujący dwupoziomowy efekt czarno-biały.
type: docs
url: /pl/com.aspose.slides/ibileveleffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Niezmienny obiekt reprezentujący efekt dwupoziomowy (czarny/biały). Kolory wejściowe, których luminancja jest mniejsza niż podana wartość progowa, są zmieniane na czarny. Kolory wejściowe, których luminancja jest większa lub równa podanej wartości, są ustawiane na biały. Wartości efektu alfa nie są przez ten efekt zmieniane.
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