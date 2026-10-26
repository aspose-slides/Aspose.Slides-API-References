---
title: IDuotoneEffectiveData
second_title: Aspose.Slides dla Java – referencja API
description: Niepodlegający zmianie obiekt reprezentujący efekt Duotone.
type: docs
url: /pl/com.aspose.slides/iduotoneeffectivedata/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IDuotoneEffectiveData extends IEffectEffectiveData
```

Niepodlegający zmianie obiekt reprezentujący efekt Duotone. Dla każdego piksela łączy clr1 i clr2 za pomocą interpolacji liniowej, aby określić nowy kolor tego piksela.
## Metody

| Metoda | Opis |
| --- | --- |
| [getColor1()](#getColor1--) | Zwraca format koloru docelowego dla ciemnych pikseli. |
| [getColor2()](#getColor2--) | Zwraca format koloru docelowego dla jasnych pikseli. |
### getColor1() {#getColor1--}
```
public abstract Color getColor1()
```


Zwraca format koloru docelowego dla ciemnych pikseli. Tylko do odczytu java.awt.Color.

**Zwraca:**
java.awt.Color
### getColor2() {#getColor2--}
```
public abstract Color getColor2()
```


Zwraca format koloru docelowego dla jasnych pikseli. Tylko do odczytu java.awt.Color.

**Zwraca:**
java.awt.Color