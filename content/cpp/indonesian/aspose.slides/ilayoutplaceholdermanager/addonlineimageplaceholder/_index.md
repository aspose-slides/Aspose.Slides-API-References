---
title: AddOnlineImagePlaceholder()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan placeholder shape baru ke slide tata letak untuk menampung gambar daring.
type: docs
weight: 118
url: /id/aspose.slides/ilayoutplaceholdermanager/addonlineimageplaceholder/
---
## ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float, float, float, float) metode


Menambahkan placeholder shape baru ke slide tata letak untuk menampung gambar daring.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddOnlineImagePlaceholder(float x, float y, float width, float height)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat X dari placeholder shape baru. |
| y | **float** | Koordinat Y dari placeholder shape baru. |
| width | **float** | Lebar dari placeholder shape baru. |
| height | **float** | Tinggi dari placeholder shape baru. |

### Nilai Kembali

Membuat [IAutoShape](../../iautoshape/) dengan placeholder Online Image.

## Keterangan



Contoh berikut menunjukkan cara menambahkan placeholder shape Online Image ke slide tata letak. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddOnlineImagePlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAutoShape](../../iautoshape/)
* Kelas [ILayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)