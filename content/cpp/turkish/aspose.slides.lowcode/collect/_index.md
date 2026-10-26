---
title: Collect
second_title: Aspose.Slides for C++ API Referansı
description: Presentation'dan farklı türlerde model nesnelerini toplamak için tasarlanmış bir grup yöntemi temsil eder.
type: docs
weight: 1
url: /tr/aspose.slides.lowcode/collect/
---
## Collect sınıfı


Farklı türlerde model nesnelerini [Presentation](../../aspose.slides/presentation/)'den toplamak için tasarlanmış bir grup yöntemi temsil eder.

```cpp
class Collect
```

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
|  [Collect](./collect/)() |  |
| static [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[Shape](../../aspose.slides/shape/)\>\>\> [Shapes](./shapes/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>) | Tüm [Shape](../../aspose.slides/shape/) örneklerini [Presentation](../../aspose.slides/presentation/) içinde toplar. |
## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // ... şekil biçimlendirmesini veya diğer özellikleri değiştir
}
```

## Ayrıca Bakınız

* Ad alanı [Aspose::Slides::LowCode](../)
* Kütüphane [Aspose.Slides](../../)