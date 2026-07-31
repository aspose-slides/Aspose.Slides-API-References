---
title: Shapes()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengumpulkan semua instance Shape dalam Presentation.
type: docs
weight: 1
url: /id/aspose.slides.lowcode/collect/shapes/
---
## Collect::Shapes(System::SharedPtr\<Presentation\>) metode

Mengumpulkan semua instance dari [Shape](../../../aspose.slides/shape/) dalam [Presentation](../../../aspose.slides/presentation/).

```cpp
static System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<Shape>>> Aspose::Slides::LowCode::Collect::Shapes(System::SharedPtr<Presentation> pres)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | [Presentation](../../../aspose.slides/presentation/) untuk mengumpulkan bentuk |

### Nilai Kembalian

Koleksi semua bentuk yang terdapat dalam presentasi
## Catatan

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto& shape : Collect::Shapes(pres))
{
    // jika bentuk adalah AutoShape, tambahkan batas hitam padat
    if (System::ObjectExt::Is<AutoShape>(shape))
    {
        auto autoShape = System::AsCast<AutoShape>(shape);
        autoShape->get_LineFormat()->set_Style(LineStyle::Single);
        autoShape->get_LineFormat()->set_Width(10.0f);
        autoShape->get_LineFormat()->get_FillFormat()->set_FillType(FillType::Solid);
        autoShape->get_LineFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(Color::get_Black());
    }
}

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IEnumerable](../../../system.collections.generic/ienumerable/)
* Kelas [Shape](../../../aspose.slides/shape/)
* Kelas [Presentation](../../../aspose.slides/presentation/)
* Kelas [Collect](../)
* Ruang Nama [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)