---
title: AddVerticalContentPlaceholder()
second_title: Aspose.Slides untuk Referensi API C++
description: Menambahkan shape placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media, atau teks dalam arah vertikal.
type: docs
weight: 14
url: /id/aspose.slides/layoutplaceholdermanager/addverticalcontentplaceholder/
---
## LayoutPlaceholderManager::AddVerticalContentPlaceholder(float, float, float, float) metode


Menambahkan shape placeholder baru ke slide tata letak untuk menampung konten, seperti gambar, tabel, media, atau teks dalam arah vertikal.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalContentPlaceholder(float x, float y, float width, float height) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat X dari shape placeholder baru. |
| y | **float** | Koordinat Y dari shape placeholder baru. |
| width | **float** | Lebar dari shape placeholder baru. |
| height | **float** | Tinggi dari shape placeholder baru. |

### Nilai Kembalian

Membuat [IAutoShape](../../iautoshape/) dengan placeholder Konten (Vertikal).

## Keterangan



Contoh berikut menunjukkan cara menambahkan shape placeholder Konten (Vertikal) ke slide tata letak. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalContentPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAutoShape](../../iautoshape/)
* Kelas [LayoutPlaceholderManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)