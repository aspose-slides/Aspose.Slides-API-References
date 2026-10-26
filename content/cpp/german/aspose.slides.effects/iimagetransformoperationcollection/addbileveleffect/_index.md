---
title: AddBiLevelEffect()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt den neuen Bi-Level (schwarz/weiß) Effekt am Ende einer Sammlung hinzu.
type: docs
weight: 118
url: /de/aspose.slides.effects/iimagetransformoperationcollection/addbileveleffect/
---
## IImageTransformOperationCollection::AddBiLevelEffect(float) Methode

Fügt den neuen Bi-Level (schwarz/weiß) Effekt am Ende einer Sammlung hinzu.

```cpp
virtual System::SharedPtr<IBiLevel> Aspose::Slides::Effects::IImageTransformOperationCollection::AddBiLevelEffect(float threshold)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | **float** | Der Luminanzschwellenwert für den Bi-Level-Effekt. Werte, die größer als oder gleich dem Schwellenwert sind, werden auf Weiß gesetzt. Werte, die kleiner als der Schwellenwert sind, werden auf Schwarz gesetzt. |

### Rückgabewert

Index des neuen Bildeffekts in einer Sammlung.

## Siehe auch

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [IBiLevel](../../ibilevel/)
* Klasse [IImageTransformOperationCollection](../)
* Namensraum [Aspose::Slides::Effects](../../)
* Bibliothek [Aspose.Slides](../../../)