---
title: GetEffective()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengambil data format bullet efektif dengan pewarisan yang diterapkan.
type: docs
weight: 248
url: /id/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() metode

Mendapatkan data format bullet efektif dengan pewarisan yang diterapkan.

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```

### Nilai Kembali

Sebuah [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Keterangan

Contoh ini menunjukkan cara mendapatkan beberapa properti format bullet yang efektif. 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<Aspose::Slides::IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveBulletFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_Bullet()->GetEffective();

Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveBulletFormat->get_Type()));
if (effectiveBulletFormat->get_Type() == Aspose::Slides::BulletType::Numbered)
{
    Console::WriteLine(String(u"Numbered style: ") + ObjectExt::ToString(effectiveBulletFormat->get_NumberedBulletStyle()));
    Console::WriteLine(String(u"Starting number: ") + effectiveBulletFormat->get_NumberedBulletStartWith());
}
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Kelas [BulletFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)