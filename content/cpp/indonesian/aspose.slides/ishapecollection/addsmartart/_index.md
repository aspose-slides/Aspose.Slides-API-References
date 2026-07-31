---
title: AddSmartArt()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat diagram SmartArt dan menambahkannya ke akhir koleksi bentuk.
type: docs
weight: 40
url: /id/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) metode

Membuat diagram [SmartArt](../../../aspose.slides.smartart/) dan menambahkannya ke akhir koleksi bentuk.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x bingkai diagram, dalam poin. |
| y | **float** | Koordinat y bingkai diagram, dalam poin. |
| width | **float** | Lebar bingkai diagram, dalam poin. |
| height | **float** | Tinggi bingkai diagram, dalam poin. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | Tipe tata letak [SmartArt](../../../aspose.slides.smartart/). |

### Nilai Kembali

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
* Kelas [IShapeCollection](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)