---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt den neuen Farbverlaufspunkt und fügt ihn am Ende der Sammlung hinzu.
type: docs
weight: 53
url: /de/aspose.slides/gradientstopcollection/add/
---
## GradientStopCollection::Add(float, System::Drawing::Color) Methode


Erstellt den neuen Farbverlaufspunkt und fügt ihn am Ende der Sammlung hinzu.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, System::Drawing::Color color) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | **float** | Position des neuen Farbverlaufspunkts. |
| color | [System::Drawing::Color](../../../system.drawing/color/) | Farbe des neuen Farbverlaufspunkts. |

### Rückgabewert

Index des neuen Farbverlaufspunkts in der Sammlung.

## GradientStopCollection::Add(float, PresetColor) Methode


Erstellt den neuen Farbverlaufspunkt und fügt ihn am Ende der Sammlung hinzu.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, PresetColor presetColor) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | **float** | Position des neuen Farbverlaufspunkts. |
| presetColor | [PresetColor](../../presetcolor/) | Farbe des neuen Farbverlaufspunkts. |

### Rückgabewert

Index des neuen Farbverlaufspunkts in der Sammlung.

## GradientStopCollection::Add(float, SchemeColor) Methode


Erstellt den neuen Farbverlaufspunkt und fügt ihn am Ende der Sammlung hinzu.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, SchemeColor schemeColor) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| position | **float** | Position des neuen Farbverlaufspunkts. |
| schemeColor | [SchemeColor](../../schemecolor/) | Farbe des neuen Farbverlaufspunkts. |

### Rückgabewert

Index des neuen Farbverlaufspunkts in der Sammlung.

## Siehe auch

* Enum [PresetColor](../../presetcolor/)
* Enum [SchemeColor](../../schemecolor/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGradientStop](../../igradientstop/)
* Class [Color](../../../system.drawing/color/)
* Class [GradientStopCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)