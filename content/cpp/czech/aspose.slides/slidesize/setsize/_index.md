---
title: SetSize()
second_title: Aspose.Slides pro C++ API Reference
description: Nastaví velikost snímku podle typu a přepočítá existující obsah.
type: docs
weight: 53
url: /cs/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) metoda

Nastaví velikost snímku podle typu a přepočítá existující obsah.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Předdefinovaná velikost snímku, která se použije. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Režim škálování obsahu, který se použije. |

## Poznámky

Přiřazením jakékoli hodnoty kromě [SlideSizeType::Custom](../../slidesizetype/) se upraví [SlideSize::get_Size](../get_size/) podle vybraného typu při zachování [SlideSize::get_Orientation](../get_orientation/). 

## SlideSize::SetSize(float, float, SlideSizeScaleType) metoda

Nastaví rozměry snímku explicitně a přepočítá existující obsah.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| width | **float** | Nová šířka snímku v bodech. |
| height | **float** | Nová výška snímku v bodech. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Režim škálování obsahu, který se použije. |

## Poznámky

Tím se nastaví vlastnost [SlideSize::get_Type](../get_type/) na [SlideSizeType::Custom](../../slidesizetype/) a nastaví se [Orientation](../../orientation/). 

## Viz také

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Třída [SlideSize](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)