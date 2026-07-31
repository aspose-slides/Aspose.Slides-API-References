---
title: AddVerticalContentPlaceholder()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan shape placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media, atau teks dalam arah vertikal.
type: docs
weight: 14
url: /id/aspose.slides/ilayoutplaceholdermanager/addverticalcontentplaceholder/
---
## ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) metode

Menambahkan shape placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media, atau teks dalam arah vertikal.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height)=0
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | Koordinat X dari bentuk placeholder baru. |
| y | **float** | Koordinat Y dari bentuk placeholder baru. |
| width | **float** | Lebar dari bentuk placeholder baru. |
| height | **float** | Tinggi dari bentuk placeholder baru. |

### Nilai Kembalian

Membuat [IAutoShape](../../iautoshape/) dengan placeholder Konten (Vertikal).

## Catatan



Contoh berikut menunjukkan cara menambahkan bentuk placeholder Konten (Vertikal) ke slide tata letak. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAutoShape](../../iautoshape/)
* Kelas [ILayoutPlaceholderManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)