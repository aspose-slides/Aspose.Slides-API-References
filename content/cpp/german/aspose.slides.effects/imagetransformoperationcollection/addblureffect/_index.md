---
title: AddBlurEffect()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt den neuen Unschärfe-Effekt am Ende einer Sammlung hinzu.
type: docs
weight: 157
url: /de/aspose.slides.effects/imagetransformoperationcollection/addblureffect/
---
## ImageTransformOperationCollection::AddBlurEffect(double, bool) Methode


Fügt den neuen [Blur](../../blur/) Effekt am Ende einer Sammlung hinzu.

```cpp
System::SharedPtr<IBlur> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBlurEffect(double radius, bool grow) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| radius | **double** | Der Radius der Unschärfe. |
| grow | **bool** | Gibt an, ob die Begrenzungen des Objekts infolge der Unschärfe vergrößert werden sollen. True bedeutet, dass die Begrenzungen vergrößert werden, während false bedeutet, dass sie nicht vergrößert werden. |

### Rückgabewert

Index des neuen Bildeffekts in einer Sammlung.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IBlur](../../iblur/)
* Klasse [ImageTransformOperationCollection](../)
* Namensraum [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)