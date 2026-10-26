---
title: Reorder()
second_title: Aspose.Slides für C++ API Referenz
description: Verschiebt die Folie aus der Sammlung an die angegebene Position.
type: docs
weight: 157
url: /de/aspose.slides/slidecollection/reorder/
---
## SlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) Methode

Verschiebt die Folie aus der Sammlung an die angegebene Position.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Zielindex. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) zu verschieben. |

## SlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) Methode

Verschiebt Folien aus der Sammlung an die angegebene Position. [Slides](../../) wird beginnend mit dem Index in der Reihenfolge, in der sie in der Liste erscheinen, eingefügt.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Zielindex. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) zu verschieben. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ISlide](../../islide/)
* Klasse [SlideCollection](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)