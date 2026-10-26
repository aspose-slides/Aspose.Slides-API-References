---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir Summary Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 144
url: /tr/aspose.slides/ishapecollection/addsummaryzoomframe/
---
## IShapeCollection::AddSummaryZoomFrame(float, float, float, float) metodu

Yeni bir Summary Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height)=0
```

### Parametreler

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni Summary Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni Summary Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni Summary Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni Summary Zoom çerçevesinin yüksekliği, puan cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [ISummaryZoomFrame](../../isummaryzoomframe/).

## Açıklamalar

Bu metod, sunumdaki tüm bölümler için özet bağlantılarını bir araya getiren bir Summary Zoom çerçevesi oluşturur.

Bu örnek, bir Summary Zoom nesnesini bir koleksiyonun sonuna eklemeyi gösterir ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayın): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISummaryZoomFrame](../../isummaryzoomframe/)
* Sınıf [IShapeCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)