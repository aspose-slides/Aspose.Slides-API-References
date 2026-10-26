---
title: AddSmartArt()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat diagram SmartArt dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 79
url: /id/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) metode

Membuat diagram [SmartArt](../../../aspose.slides.smartart/) dan menambahkannya ke akhir koleksi shape.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari bingkai diagram, dalam poin. |
| y | **float** | Koordinat y dari bingkai diagram, dalam poin. |
| width | **float** | Lebar bingkai diagram, dalam poin. |
| height | **float** | Tinggi bingkai diagram, dalam poin. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Tipe tata letak [SmartArt](../../../aspose.slides.smartart/). |

### Nilai Kembalian

[SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/) yang baru dibuat.

## Catatan

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## Lihat Juga

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Kelas [ShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)