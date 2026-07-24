---
title: AddSmartArt()
second_title: Aspose.Slides için C++ API Referansı
description: Bir SmartArt diyagramı oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 40
url: /tr/aspose.slides/ishapecollection/addsmartart/
---
## IShapeCollection::AddSmartArt(float, float, float, float, SmartArt::SmartArtLayoutType) metod

Şekil koleksiyonunun sonuna bir [SmartArt](../../../aspose.slides.smartart/) diyagramı oluşturur ve ekler.

```cpp
virtual System::SharedPtr<SmartArt::ISmartArt> Aspose::Slides::IShapeCollection::AddSmartArt(float x, float y, float width, float height, SmartArt::SmartArtLayoutType layoutType)=0
```

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| x | **float** | Diyagram çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Diyagram çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Diyagram çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Diyagram çerçevesinin yüksekliği, puan cinsinden. |
| layoutType | [SmartArt::SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/) | [SmartArt](../../../aspose.slides.smartart/) yerleşim türü. |

### Dönüş Değeri

Yeni oluşturulan [SmartArt::ISmartArt](../../../aspose.slides.smartart/ismartart/).

## Açıklamalar

```cpp
auto pres = System::MakeObject<Presentation>();
auto slide = pres->get_Slide(0);
auto smart = slide->get_Shapes()->AddSmartArt(0.0f, 0.0f, 400.0f, 400.0f, SmartArtLayoutType::BasicBlockList);
```

## Ayrıca Bakınız

* Enum [SmartArtLayoutType](../../../aspose.slides.smartart/smartartlayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISmartArt](../../../aspose.slides.smartart/ismartart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)