---
title: Remove()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Odstraňuje první výskyt konkrétního objektu z ICollection.
type: docs
weight: 339
url: /cs/aspose.slides.effects/imagetransformoperationcollection/remove/
---
## ImageTransformOperationCollection::Remove(const System::SharedPtr\<IImageTransformOperation\>\&) metoda

Odstraňuje první výskyt konkrétního objektu z [ICollection](../../../system.collections.generic/icollection/).

```cpp
bool Aspose::Slides::Effects::ImageTransformOperationCollection::Remove(const System::SharedPtr<IImageTransformOperation> &item) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\& | Objekt, který má být odstraněn ze [ICollection](../../../system.collections.generic/icollection/). |

### Návratová hodnota

true pokud byl *item* úspěšně odstraněn z [ICollection](../../../system.collections.generic/icollection/); jinak false. Tato metoda také vrací false, pokud *item* není nalezen v původním [ICollection](../../../system.collections.generic/icollection/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImageTransformOperation](../../iimagetransformoperation/)
* Class [ImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)