---
title: Remove()
second_title: Aspose.Slides C++ API-referencia
description: Eltávolítja egy adott objektum első előfordulását az ICollection-ből.
type: docs
weight: 339
url: /hu/aspose.slides.effects/imagetransformoperationcollection/remove/
---
## ImageTransformOperationCollection::Remove(const System::SharedPtr\<IImageTransformOperation\>\&) metódus

Eltávolítja egy adott objektum első előfordulását a [ICollection](../../../system.collections.generic/icollection/)-ból.

```cpp
bool Aspose::Slides::Effects::ImageTransformOperationCollection::Remove(const System::SharedPtr<IImageTransformOperation> &item) override
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\& | Az objektum, amelyet el kell távolítani a [ICollection](../../../system.collections.generic/icollection/)-ból. |

### Visszatérési érték

true, ha az *item* sikeresen el lett távolítva a [ICollection](../../../system.collections.generic/icollection/)-ból; egyébként false. Ez a metódus szintén false értéket ad vissza, ha az *item* nem található az eredeti [ICollection](../../../system.collections.generic/icollection/)-ban.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IImageTransformOperation](../../iimagetransformoperation/)
* Osztály [ImageTransformOperationCollection](../)
* Névtér [Aspose::Slides::Effects](../../)
* Könyvtár [Aspose.Slides](../../../)