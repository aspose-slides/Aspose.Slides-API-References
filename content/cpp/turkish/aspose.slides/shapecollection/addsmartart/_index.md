---
title: AddSmartArt()
second_title: Aspose.Slides için C++ API Referansı
description: Bir SmartArt diyagramı oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 79
url: /tr/aspose.slides/shapecollection/addsmartart/
---
## ShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) metodu

Bir [SmartArt](../../../aspose.slides.smartart/) diyagram oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::ShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Diagramın çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Diagramın çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Diagramın çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Diagramın çerçevesinin yüksekliği, puan cinsinden. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | [SmartArt](../../../aspose.slides.smartart/) düzen tipi. |

### Dönüş Değeri

Yeni oluşturulan [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).

## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## Bakınız

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Sınıf [ShapeCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)