---
title: AddSmartArtPlaceholder()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung diagram SmartArt.
type: docs
weight: 92
url: /id/aspose.slides/ilayoutplaceholdermanager/addsmartartplaceholder/
---
## ILayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) metode

Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung diagram [SmartArt](../../../aspose.slides.smartart/).

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat X dari bentuk placeholder baru. |
| y | **float** | Koordinat Y dari bentuk placeholder baru. |
| width | **float** | Lebar dari bentuk placeholder baru. |
| height | **float** | Tinggi dari bentuk placeholder baru. |

### Nilai Kembali

Membuat [IAutoShape](../../iautoshape/) dengan placeholder [SmartArt](../../../aspose.slides.smartart/).

## Catatan

Contoh berikut menunjukkan cara menambahkan bentuk placeholder [SmartArt](../../../aspose.slides.smartart/) ke slide tata letak. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAutoShape](../../iautoshape/)
* Kelas [ILayoutPlaceholderManager](../)
* Ruang nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)