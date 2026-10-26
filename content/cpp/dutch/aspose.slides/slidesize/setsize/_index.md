---
title: SetSize()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de dia-grootte in op type en schaalt bestaande inhoud.
type: docs
weight: 53
url: /nl/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) methode

Stelt de diaformaat in op type en schaalt bestaande inhoud.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | De vooraf gedefinieerde diaformaat die moet worden toegepast. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | De inhoudsschaalmodus die moet worden gebruikt. |
## Opmerkingen

Het instellen van een andere waarde dan [SlideSizeType::Custom](../../slidesizetype/) past de [SlideSize::get_Size](../get_size/) aan op basis van het geselecteerde type, terwijl [SlideSize::get_Orientation](../get_orientation/) behouden blijft. 

## SlideSize::SetSize(float, float, SlideSizeScaleType) methode

Stelt de dia-afmetingen expliciet in en schaalt bestaande inhoud.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| width | **float** | De nieuwe dia-breedte, in punten. |
| height | **float** | De nieuwe dia-hoogte, in punten. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | De inhoudsschaalmodus die moet worden gebruikt. |
## Opmerkingen

Dit reset de [SlideSize::get_Type](../get_type/) eigenschap naar [SlideSizeType::Custom](../../slidesizetype/) en stelt de [Orientation](../../orientation/) in. 

## Zie ook

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Klasse [SlideSize](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)