---
title: Add()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce.
type: docs
weight: 14
url: /cs/aspose.slides/igradientstopcollection/add/
---
## IGradientStopCollection::Add(float, System::Drawing::Color) metoda


Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce.

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, System::Drawing::Color color)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| position | **float** | Pozice nové gradientové zastávky. |
| color | [System::Drawing::Color](../../../system.drawing/color/) | Barva nové gradientové zastávky. |

### Návratová hodnota

Index nové gradientové zastávky v kolekci.

## IGradientStopCollection::Add(float, PresetColor) metoda


Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce.

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, PresetColor presetColor)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| position | **float** | Pozice nové gradientové zastávky. |
| presetColor | [PresetColor](../../presetcolor/) | Barva nové gradientové zastávky. |

### Návratová hodnota

Index nové gradientové zastávky v kolekci.

## IGradientStopCollection::Add(float, SchemeColor) metoda


Vytvoří novou gradientovou zastávku a přidá ji na konec kolekce.

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, SchemeColor schemeColor)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| position | **float** | Pozice nové gradientové zastávky. |
| schemeColor | [SchemeColor](../../schemecolor/) | Barva nové gradientové zastávky. |

### Návratová hodnota

Index nové gradientové zastávky v kolekci.

## Viz také

* Enum [PresetColor](../../presetcolor/)
* Enum [SchemeColor](../../schemecolor/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGradientStop](../../igradientstop/)
* Class [Color](../../../system.drawing/color/)
* Class [IGradientStopCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)