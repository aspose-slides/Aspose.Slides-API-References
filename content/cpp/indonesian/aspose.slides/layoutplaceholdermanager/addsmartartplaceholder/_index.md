---
title: AddSmartArtPlaceholder()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan shape placeholder baru ke slide tata letak untuk menampung diagram SmartArt.
type: docs
weight: 92
url: /id/aspose.slides/layoutplaceholdermanager/addsmartartplaceholder/
---
## LayoutPlaceholderManager::AddSmartArtPlaceholder(float, float, float, float) metode


Menambahkan shape placeholder baru ke slide tata letak untuk menampung diagram [SmartArt](../../../aspose.slides.smartart/).

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddSmartArtPlaceholder(float x, float y, float width, float height) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat X dari shape placeholder baru. |
| y | **float** | Koordinat Y dari shape placeholder baru. |
| width | **float** | Lebar shape placeholder baru. |
| height | **float** | Tinggi shape placeholder baru. |

### Nilai Kembalian

Membuat [IAutoShape](../../iautoshape/) dengan placeholder [SmartArt](../../../aspose.slides.smartart/).

## Catatan

Contoh berikut menunjukkan cara menambahkan shape placeholder [SmartArt](../../../aspose.slides.smartart/) ke slide tata letak. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddSmartArtPlaceholder(20.0f, 20.0f, 200.0f, 200.0f);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)