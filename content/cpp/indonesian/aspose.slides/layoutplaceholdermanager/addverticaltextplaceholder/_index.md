---
title: AddVerticalTextPlaceholder()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten teks dalam arah vertikal.
type: docs
weight: 40
url: /id/aspose.slides/layoutplaceholdermanager/addverticaltextplaceholder/
---
## LayoutPlaceholderManager::AddVerticalTextPlaceholder(float, float, float, float) metode


Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung konten teks dalam arah vertikal.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddVerticalTextPlaceholder(float x, float y, float width, float height) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat X dari bentuk placeholder baru. |
| y | **float** | Koordinat Y dari bentuk placeholder baru. |
| width | **float** | Lebar dari bentuk placeholder baru. |
| height | **float** | Tinggi dari bentuk placeholder baru. |

### Nilai Kembalian

Membuat [IAutoShape](../../iautoshape/) dengan placeholder Teks (Vertikal).
## Catatan



Contoh berikut menunjukkan cara menambahkan bentuk placeholder Teks (Vertikal) ke slide tata letak. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddVerticalTextPlaceholder(20.0f, 20.0f, 300.0f, 500.0f);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAutoShape](../../iautoshape/)
* Kelas [LayoutPlaceholderManager](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)