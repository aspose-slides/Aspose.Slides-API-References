---
title: Remove()
second_title: Aspose.Slides C++ API Referansı
description: Belirli bir nesnenin ICollection içindeki ilk oluşumunu kaldırır.
type: docs
weight: 339
url: /tr/aspose.slides.effects/imagetransformoperationcollection/remove/
---
## ImageTransformOperationCollection::Remove(const System::SharedPtr\<IImageTransformOperation\>\&) metodu

Belirli bir nesnenin ilk oluşumunu [ICollection](../../../system.collections.generic/icollection/)'den kaldırır.

```cpp
bool Aspose::Slides::Effects::ImageTransformOperationCollection::Remove(const System::SharedPtr<IImageTransformOperation> &item) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| item | const [System::SharedPtr](../../../system/sharedptr/)\<[IImageTransformOperation](../../iimagetransformoperation/)\>\& | [ICollection](../../../system.collections.generic/icollection/)'den kaldırılacak nesne. |

### Dönüş Değeri

Eğer *item*  [ICollection](../../../system.collections.generic/icollection/)'den başarıyla kaldırıldıysa true; aksi takdirde false. Bu metot ayrıca *item*  orijinal [ICollection](../../../system.collections.generic/icollection/) içinde bulunamazsa false döndürür.

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImageTransformOperation](../../iimagetransformoperation/)
* Class [ImageTransformOperationCollection](../)
* Namespace [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)