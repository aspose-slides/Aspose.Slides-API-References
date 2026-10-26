---
title: InsertSummaryZoomFrame()
second_title: Aspose.Slides için C++ API Referansı
description: Yeni bir Summary Zoom çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.
type: docs
weight: 170
url: /tr/aspose.slides/shapecollection/insertsummaryzoomframe/
---
## ShapeCollection::InsertSummaryZoomFrame(int32_t, float, float, float, float) method


Yeni bir Summary Zoom çerçevesi oluşturur ve belirtilen dizinde şekil koleksiyonuna ekler.

```cpp
System::SharedPtr<ISummaryZoomFrame> Aspose::Slides::ShapeCollection::InsertSummaryZoomFrame(int32_t index, float x, float y, float width, float height) override
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Summary Zoom çerçevesinin ekleneceği sıfırdan başlayan dizin. |
| x | **float** | Yeni Summary Zoom çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni Summary Zoom çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni Summary Zoom çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni Summary Zoom çerçevesinin yüksekliği, nokta cinsinden. |

### Return Value

Yeni oluşturulan [ISummaryZoomFrame](../../isummaryzoomframe/).

## Remarks


Bu yöntem, sunumdaki tüm bölümler için özet bağlantılarını toplayan bir Summary Zoom çerçevesi oluşturur. 

Bu örnek, bir koleksiyonun belirtilen dizinine Summary Zoom nesnesi oluşturup eklemeyi gösterir (\"Presentation.pptx\" sunumunda en az iki bölüm olduğunu varsayın): 
```cpp
auto pres = System::MakeObject<Presentation>(u"Presentation.pptx");
auto shapes = pres->get_Slides()->idx_get(0)->get_Shapes();

auto zoomFrame = shapes->InsertSummaryZoomFrame(2, 150.0f, 20.0f, 50.0f, 50.0f)
```


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISummaryZoomFrame](../../isummaryzoomframe/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)