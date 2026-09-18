---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/globallayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Sunuma yeni bir yerleşim slaytı ekler.

### Döndürdüğü Değer

Eklenen slayt.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide) | Yeni bir yerleşim için ana slayt. |
| layout_type | [`SlideLayoutType`](/slides/python-net/tr/aspose.slides/slidelayouttype) | Yeni bir yerleşim için yerleşim tipi.<br/><br/>            Desteklenen yerleşim tipleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Diğer yerleşim tipleri şu anda desteklenmiyor: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Yeni bir yerleşim için ad. Verilen ad zaten kullanılıyorsa ArgumentException fırlatılır.<br/><br/>            Eğer None parametresi geçilirse, ad verilen yerleşim tipine göre otomatik olarak oluşturulur (örneğin "Title Slide" veya "1_Title Slide", "2_..", vb.). |

### Açıklamalar

1) `layout_type` değerinin SlideLayoutType.Custom olduğu eklenen yerleşim hiç yer tutucu ve şekil içermez.  
2) Bu yöntemin analoğu, [`IMasterSlide.layout_slides`](/slides/python-net/tr/aspose.slides/imasterslide/layout_slides) özelliğiyle erişilen **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** yöntemidir.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Geçersiz bir `layout_type` parametresi değeri verildiğinde fırlatılır. Şu anda desteklenmeyen yerleşim tipleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | `master` None ise fırlatılır. |
| **RuntimeError(Proxy error(ArgumentException))** | `master` başka bir sunuma ait ise fırlatılır. |
| **RuntimeError(Proxy error(ArgumentException))** | `master`'ın yerleşim koleksiyonunda `layout_name` değeri zaten kullanılıyorsa fırlatılır. |



### Bkz.
* sınıf [`GlobalLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/globallayoutslidecollection)
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide)
* enum [`SlideLayoutType`](/slides/python-net/tr/aspose.slides/slidelayouttype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)