---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/masterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Koleksiyonun sonuna yeni bir yerleşim slaydı ekler.

### Döndürür

Eklenen slayt.

```python
def add(self, layout_type, layout_name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/tr/aspose.slides/slidelayouttype) | Yeni bir yerleşim için düzen türü.<br/><br/>            Desteklenen düzen türleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Şu anda desteklenmeyen diğer düzen türleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Yeni bir yerleşim için ad. Geçilen ad zaten kullanılıyorsa ArgumentException fırlatılır.<br/><br/>            None parametresi verilirse, ad, verilen düzen türüne göre otomatik olarak oluşturulur <br/><br/>            (örneğin "Title Slide" veya "1_Title Slide", "2_..", vb.). |

### Açıklamalar

1) `layout_type` değerinin SlideLayoutType.Custom olduğu eklenen yerleşim, yer tutucu ve şekil içermez.  
2) Bu yöntemin analogu  
method **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste**  
[`IPresentation.layout_slides`](/slides/python-net/tr/aspose.slides/ipresentation/layout_slides) özelliği ile erişilir.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Geçersiz bir `layout_type` parametresi değeri verildiğinde fırlatılır. Şu anda desteklenmeyen düzen türleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | Bu yerleşim koleksiyonunda `layout_name` değeri zaten kullanılıyorsa fırlatılır.<br/>            |

### İlgili
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`MasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection)
* enumerasyon [`SlideLayoutType`](/slides/python-net/tr/aspose.slides/slidelayouttype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)