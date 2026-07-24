---
title: SetSize()
second_title: Aspose.Slides für C++ API-Referenz
description: Legt die Foliengröße anhand des Typs fest und skaliert den vorhandenen Inhalt.
type: docs
weight: 53
url: /de/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) Methode

Legt die Foliengröße anhand des Typs fest und skaliert den vorhandenen Inhalt.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Die anzuwendende vordefinierte Foliengröße. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Der zu verwendende Skalierungsmodus des Inhalts. |
## Bemerkungen

Durch Zuweisen eines anderen Werts als [SlideSizeType::Custom](../../slidesizetype/) wird die [SlideSize::get_Size](../get_size/) basierend auf dem gewählten Typ angepasst, während [SlideSize::get_Orientation](../get_orientation/) erhalten bleibt.

## SlideSize::SetSize(float, float, SlideSizeScaleType) Methode

Legt die Folienabmessungen explizit fest und skaliert den vorhandenen Inhalt.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | **float** | Die neue Folienbreite in Punkt. |
| height | **float** | Die neue Folienhöhe in Punkt. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Der zu verwendende Skalierungsmodus des Inhalts. |
## Bemerkungen

Dies setzt die [SlideSize::get_Type](../get_type/)-Eigenschaft auf [SlideSizeType::Custom](../../slidesizetype/) zurück und legt die [Orientation](../../orientation/) fest.

## Siehe auch

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Klasse [SlideSize](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)