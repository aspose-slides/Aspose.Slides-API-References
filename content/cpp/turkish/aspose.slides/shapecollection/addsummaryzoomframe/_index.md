---
title: AddSummaryZoomFrame()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir Summary Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.
type: docs
weight: 157
url: /tr/aspose.slides/shapecollection/addsummaryzoomframe/
---
## ShapeCollection::AddSummaryZoomFrame(float, float, float, float) yöntemi

Yeni bir Summary Zoom çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::AddSummaryZoomFrame(float x, float y, float width, float height) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni Summary Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni Summary Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni Summary Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni Summary Zoom çerçevesinin yüksekliği, puan cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [ISummaryZoomFrame](../../isummaryzoomframe/).

## Açıklamalar

Bu yöntem yeni bir Summary Zoom oluşturur ve bu sunumdaki tüm bölümler için nesneler koleksiyonunu içine koyar.

Bu örnek, bir Summary Zoom nesnesinin bir koleksiyonun sonuna eklenmesini gösterir ("Presentation.pptx" sunumunda en az iki bölüm olduğunu varsayın): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->AddSummaryZoomFrame(150.0f, 20.0f, 500.0f, 250.0f);
```

## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISummaryZoomFrame](../../isummaryzoomframe/)
* Sınıf [ShapeCollection](../)
* Ad Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)