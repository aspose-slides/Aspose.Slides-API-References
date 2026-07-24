---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir Summary Zoom çerçevesi oluşturur ve belirtilen dizindeki şekil koleksiyonuna ekler.
type: docs
weight: 157
url: /tr/aspose.slides/ishapecollection/insertsummaryzoomframe/
---
## IShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) metodu

Yeni bir Summary Zoom çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

```cpp
virtual System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::IShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Summary Zoom çerçevesinin ekleneceği sıfırdan başlayan dizin. |
| x | **float** | Yeni Summary Zoom çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni Summary Zoom çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni Summary Zoom çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni Summary Zoom çerçevesinin yüksekliği, puan cinsinden. |

### Dönüş Değeri

Yeni oluşturulan [ISummaryZoomFrame](../../isummaryzoomframe/).

## Açıklamalar

Bu metod, sunumdaki tüm bölümler için özet bağlantılarını toplayan bir Summary Zoom çerçevesi oluşturur.

Bu örnek, bir koleksiyonun belirtilen dizininde Summary Zoom nesnesi oluşturmayı ve eklemeyi gösterir (\"Presentation.pptx\" sunumunda en az iki bölüm olduğunu varsayalım):
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```

## İlgili Bilgiler

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISummaryZoomFrame](../../isummaryzoomframe/)
* Sınıf [IShapeCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)