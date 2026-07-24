---
title: SetSize()
second_title: Aspose.Slides für C++ API-Referenz
description: "Setzt die Foliengröße nach Typ und skaliert vorhandenen Inhalt. Das Zuweisen eines anderen Werts als SlideSizeType::Custom passt ISlideSize::get_Size basierend auf dem ausgewählten Typ an und bewahrt ISlideSize::get_Orientation."
type: docs
weight: 53
url: /de/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) Methode

Legt die Foliengröße nach Typ fest und skaliert vorhandenen Inhalt. Das Zuweisen eines anderen Wertes als [SlideSizeType::Custom](../../slidesizetype/) passt [ISlideSize::get_Size](../get_size/) basierend auf dem ausgewählten Typ an und behält [ISlideSize::get_Orientation](../get_orientation/) bei.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Die vordefinierte Foliengröße, die angewendet werden soll. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Der zu verwendende Skalierungsmodus für den Inhalt. |
## Anmerkungen

Das Zuweisen eines anderen Wertes als [SlideSizeType::Custom](../../slidesizetype/) passt [System::Drawing::Size](../../../system.drawing/size/) basierend auf dem ausgewählten Typ an und behält [Orientation](../../orientation/) bei. 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) Methode

Legt die Folienabmessungen explizit fest und skaliert vorhandenen Inhalt. Dies setzt den Wert [ISlideSize::get_Type](../get_type/) auf [SlideSizeType::Custom](../../slidesizetype/) zurück und legt [ISlideSize::get_Orientation](../get_orientation/) fest.

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | **float** | Die neue Folienbreite in Punkten. |
| height | **float** | Die neue Folienhöhe in Punkten. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Der zu verwendende Skalierungsmodus für den Inhalt. |
## Anmerkungen

Dies setzt die Eigenschaft [ISlideSize::get_Type](../get_type/) auf [SlideSizeType::Custom](../../slidesizetype/) zurück und legt [Orientation](../../orientation/) fest. 

## Siehe auch

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Klasse [ISlideSize](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)