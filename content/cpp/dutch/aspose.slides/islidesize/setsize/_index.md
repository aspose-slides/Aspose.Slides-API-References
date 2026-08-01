---
title: SetSize()
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt de diagrootte in op type en schaalt bestaande inhoud. Het toekennen van een waarde anders dan SlideSizeType::Custom past de ISlideSize::get_Size aan op basis van het geselecteerde type, terwijl ISlideSize::get_Orientation behouden blijft."
type: docs
weight: 53
url: /nl/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) methode

Stelt de diagrootte in op type en schaalt bestaande inhoud. Het toekennen van een waarde anders dan [SlideSizeType::Custom](../../slidesizetype/) past de [ISlideSize::get_Size](../get_size/) aan op basis van het geselecteerde type, terwijl [ISlideSize::get_Orientation](../get_orientation/) behouden blijft.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | The predefined slide size to apply. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |
## Opmerkingen

Het toekennen van een waarde anders dan [SlideSizeType::Custom](../../slidesizetype/) past de [System::Drawing::Size](../../../system.drawing/size/) aan op basis van het geselecteerde type, terwijl [Orientation](../../orientation/) behouden blijft.

## ISlideSize::SetSize(float, float, SlideSizeScaleType) methode

Stelt de dia-afmetingen expliciet in en schaalt bestaande inhoud. Dit reset de [ISlideSize::get_Type](../get_type/)-waarde naar [SlideSizeType::Custom](../../slidesizetype/) en stelt de [ISlideSize::get_Orientation](../get_orientation/) in.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | **float** | The new slide width, in points. |
| height | **float** | The new slide height, in points. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | The content scaling mode to use. |
## Opmerkingen

Dit reset de [ISlideSize::get_Type](../get_type/)-eigenschap naar [SlideSizeType::Custom](../../slidesizetype/) en stelt de [Orientation](../../orientation/) in. 

## Zie ook

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Klasse [ISlideSize](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)