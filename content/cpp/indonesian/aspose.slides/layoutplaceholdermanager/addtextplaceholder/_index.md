---
title: AddTextPlaceholder()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan bentuk placeholder baru ke slide tata letak untuk menyimpan konten teks.
type: docs
weight: 27
url: /id/aspose.slides/layoutplaceholdermanager/addtextplaceholder/
---
## LayoutPlaceholderManager::AddTextPlaceholder(float, float, float, float) method

Menambahkan bentuk placeholder baru ke slide tata letak untuk memuat konten teks.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddTextPlaceholder(float x, float y, float width, float height) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat X dari bentuk placeholder baru. |
| y | **float** | Koordinat Y dari bentuk placeholder baru. |
| width | **float** | Lebar bentuk placeholder baru. |
| height | **float** | Tinggi bentuk placeholder baru. |

### Nilai Kembalian

Membuat [IAutoShape](../../iautoshape/) dengan placeholder Teks.
## Catatan

Contoh berikut menunjukkan cara menambahkan bentuk placeholder Teks ke slide tata letak. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddTextPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)