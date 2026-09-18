---
title: insert method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/imasterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Koleksiyonun belirtilen konumuna yeni bir layout slaytı ekler.

### Döndürür

Eklenen slayt.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Yeni slaytın index'i. |
| layout_type | [`SlideLayoutType`](/slides/python-net/tr/aspose.slides/slidelayouttype) | Yeni bir layout için düzen tipi.<br/><br/> Desteklenen düzen tipleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/> Şu anda desteklenmeyen diğer düzen tipleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Yeni bir layout için ad. Geçilen ad zaten kullanılıyorsa ArgumentException fırlatılacak.<br/><br/> None parametresi geçirilirse, ad, verilen layout_type'a göre otomatik olarak oluşturulur.<br/><br/> (örneğin "Title Slide" veya "1_Title Slide", "2_..", vb.). |

### Açıklamalar

SlideLayoutType.Custom değerine sahip eklenen layout, hiçbir placeholder ve şekil içermez.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Desteklenmeyen bir `layout_type` değeri geçirilirse fırlatılır. Şu anda desteklenmeyen düzen tipleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | `layout_name` değerinin bu layout koleksiyonunda zaten kullanıldığı durumlarda fırlatılır. |

### Ayrıca Bakınız
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`IMasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/imasterlayoutslidecollection)
* enum [`SlideLayoutType`](/slides/python-net/tr/aspose.slides/slidelayouttype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)