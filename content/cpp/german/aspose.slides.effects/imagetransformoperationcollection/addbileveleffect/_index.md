---
title: AddBiLevelEffect()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt den neuen Bi-Level (schwarz/weiß) Effekt am Ende einer Sammlung hinzu.
type: docs
weight: 144
url: /de/aspose.slides.effects/imagetransformoperationcollection/addbileveleffect/
---
## ImageTransformOperationCollection::AddBiLevelEffect(float) Methode

Fügt den neuen Bi-Level (schwarz/weiß) Effekt am Ende einer Sammlung hinzu.

```cpp
System::SharedPtr<IBiLevel> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBiLevelEffect(float threshold) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | **float** | der Luminanzschwellenwert für den Bi-Level Effekt. Werte, die größer als oder gleich dem Schwellenwert sind, werden auf weiß gesetzt. Werte, die kleiner als der Schwellenwert sind, werden auf schwarz gesetzt. |

### Rückgabewert

Index des neuen Bildeffekts in einer Sammlung.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IBiLevel](../../ibilevel/)
* Klasse [ImageTransformOperationCollection](../)
* Namensraum [Aspose::Slides::Effects](../../)
* Bibliothek [Aspose.Slides](../../../)