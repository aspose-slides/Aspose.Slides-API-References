---
title: SetSize()
second_title: Aspose.Slides pro C++ API Reference
description: "Nastaví velikost snímku podle typu a škáluje existující obsah. Přiřazením jakékoli hodnoty jiné než SlideSizeType::Custom se upraví ISlideSize::get_Size podle vybraného typu, přičemž se zachová ISlideSize::get_Orientation."
type: docs
weight: 53
url: /cs/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) metoda


Nastaví velikost snímku podle typu a škáluje existující obsah. Přiřazením jakékoli hodnoty jiné než [SlideSizeType::Custom](../../slidesizetype/) se upraví [ISlideSize::get_Size](../get_size/) podle vybraného typu, přičemž se zachová [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Předdefinovaná velikost snímku, která se má použít. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Režim škálování obsahu, který se má použít. |
## Poznámky


Přiřazením jakékoli hodnoty jiné než [SlideSizeType::Custom](../../slidesizetype/) se upraví [System::Drawing::Size](../../../system.drawing/size/) podle vybraného typu, přičemž se zachová [Orientation](../../orientation/). 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) metoda


Nastaví rozměry snímku explicitně a škáluje existující obsah. Toto resetuje hodnotu [ISlideSize::get_Type](../get_type/) na [SlideSizeType::Custom](../../slidesizetype/) a nastaví [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| width | **float** | Nová šířka snímku v bodech. |
| height | **float** | Nová výška snímku v bodech. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Režim škálování obsahu, který se má použít. |
## Poznámky


Toto resetuje vlastnost [ISlideSize::get_Type](../get_type/) na [SlideSizeType::Custom](../../slidesizetype/) a nastaví [Orientation](../../orientation/). 

## Viz také

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Třída [ISlideSize](../)
* Jmenný prostor [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)