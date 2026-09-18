---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/imasterlayoutslidecollection/add/
weight: 10
---
## add(self, layout_type, layout_name) {#slidelayouttype-str}
Koleksiyonun sonuna yeni bir düzen slaytı ekler.

### Dönüş Değeri

Eklenen slayt.



```python
def add(self, layout_type, layout_name):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layout_type | [`SlideLayoutType`](/slides/python-net/tr/aspose.slides/slidelayouttype) | Yeni bir düzen için layout türü.<br/><br/> Desteklenen layout türleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/> Şu anda desteklenmeyen diğer layout türleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Yeni bir düzen için ad. Verilen ad zaten kullanılıyorsa ArgumentException fırlatılır.<br/><br/> Eğer None parametresi geçirilirse, ad verilen layout türüne göre otomatik olarak oluşturulur <br/><br/> (örneğin "Title Slide" ya da "1_Title Slide", "2_.." vb.). |

### Açıklamalar

1) `layout_type` değerinin SlideLayoutType.Custom olduğu eklenen düzen, yer tutucu ve şekil içermez.  
2) Bu yöntemin analogu, [`IPresentation.layout_slides`](/slides/python-net/tr/aspose.slides/ipresentation/layout_slides) özelliğiyle erişilen **Aspose.Slides.IGlobalLayoutSlideCollection.Add(Aspose.Slides.IMasterSlide,Aspose.Slides.SlideLayoutType,Syste** yöntemidir.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Desteklenmeyen bir `layout_type` değeri geçildiğinde fırlatılır. Şu anda desteklenmeyen layout türleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | `layout_name` değeri bu düzen koleksiyonunda zaten kullanılıyorsa fırlatılır. |



### Ayrıca Bakınız
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`IMasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/imasterlayoutslidecollection)
* enumerasyon [`SlideLayoutType`](/slides/python-net/tr/aspose.slides/slidelayouttype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)