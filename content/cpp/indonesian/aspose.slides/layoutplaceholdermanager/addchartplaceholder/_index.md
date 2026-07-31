---
title: AddChartPlaceholder()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung diagram.
type: docs
weight: 66
url: /id/aspose.slides/layoutplaceholdermanager/addchartplaceholder/
---
## LayoutPlaceholderManager::AddChartPlaceholder(float, float, float, float) metode


Menambahkan bentuk placeholder baru ke slide tata letak untuk menampung diagram.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddChartPlaceholder(float x, float y, float width, float height) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat X dari bentuk placeholder baru. |
| y | **float** | Koordinat Y dari bentuk placeholder baru. |
| width | **float** | Lebar bentuk placeholder baru. |
| height | **float** | Tinggi bentuk placeholder baru. |

### Nilai Kembali

Membuat [IAutoShape](../../iautoshape/) dengan placeholder Chart.
## Catatan



Contoh berikut menunjukkan cara menambahkan bentuk placeholder Chart ke slide tata letak. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddChartPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IAutoShape](../../iautoshape/)
* Kelas [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)