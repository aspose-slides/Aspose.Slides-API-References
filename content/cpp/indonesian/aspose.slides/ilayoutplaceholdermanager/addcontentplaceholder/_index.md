---
title: AddContentPlaceholder()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media, atau teks.
type: docs
weight: 1
url: /id/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) metode

Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media, atau teks.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat X dari bentuk placeholder baru. |
| y | **float** | Koordinat Y dari bentuk placeholder baru. |
| width | **float** | Lebar bentuk placeholder baru. |
| height | **float** | Tinggi bentuk placeholder baru. |

### Nilai Kembalian

Dibuat [IAutoShape](../../iautoshape/) dengan placeholder Content.

## Catatan

Contoh berikut menunjukkan cara menambahkan bentuk placeholder Content ke slide tata letak. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAutoShape](../../iautoshape/)
* Kelas [ILayoutPlaceholderManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)