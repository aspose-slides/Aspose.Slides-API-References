---
title: get_InkEffectImages()
second_title: Aspose.Slides for C++ API Referansı
description: Mürekkep fırçaları için görsel efektleri simüle etmek amacıyla kullanılan özel görüntü koleksiyonunu alır. Bu görüntüler, Galaxy, Rainbow vb. gibi belirli InkEffectType değerleriyle mürekkep oluşturulduğunda kullanılır. Kendi görüntülerinizi sağlayarak, her bir mürekkep efektinin nasıl görüneceğini kontrol edebilirsiniz.
type: docs
weight: 14
url: /tr/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() metot

Mürekkep fırçaları için görsel efektleri simüle etmek amacıyla kullanılan özel görüntü koleksiyonunu alır. Bu görüntüler, Galaxy, Rainbow vb. gibi belirli [InkEffectType](../../inkeffecttype/) değerleriyle mürekkep oluşturulduğunda kullanılır. Kendi görüntülerinizi sağlayarak, her bir mürekkep efektinin nasıl görüneceğini kontrol edebilirsiniz.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## Açıklamalar

Bu özellik, varsayılan mürekkep efekt dokularını kullanıcı tanımlı olanlarla değiştirmeye olanak tanır; bu, varsayılan varlıkların lisans kısıtlamaları nedeniyle erişilemez veya çalışma zamanında bulunamaz olması durumunda özellikle yararlıdır.

Sözlüğün her bir girdisi, bir [InkEffectType](../../inkeffecttype/) değerini ilgili bir [IImage](../../../aspose.slides/iimage/) nesnesiyle (ör. Bitmap veya bir **Aspose** görüntü arabirimi) ilişkilendirmelidir.

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## Ayrıca Bakınız

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [IImage](../../../aspose.slides/iimage/)
* Class [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)