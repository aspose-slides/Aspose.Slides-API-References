---
title: add method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/igloballayoutslidecollection/add/
weight: 10
---
## add(self, master, layout_type, layout_name) {#imasterslide-slidelayouttype-str}
Sunuma yeni bir düzen slaytı ekler.

### Returns

Eklenen slayt.



```python
def add(self, master, layout_type, layout_name):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| master | [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide) | Yeni bir düzen için ana slayt. |
| layout_type | [`SlideLayoutType`](/slides/python-net/tr/aspose.slides/slidelayouttype) | Yeni bir düzen için düzen türü.<br/><br/>            Desteklenen düzen türleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Şu anda desteklenmeyen diğer düzen türleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Yeni bir düzen için ad. Verilen ad zaten kullanılıyorsa ArgumentException fırlatılır.<br/><br/>            Eğer None parametresi geçirilirse, ad verilen düzen türüne göre otomatik olarak oluşturulur<br/><br/>            (örneğin "Title Slide" ya da "1_Title Slide", "2_..", vb.). |

### Remarks

1) `layout_type` için SlideLayoutType.Custom değerine sahip eklenen düzen, yer tutucu içermez ve şekil içermez.  
2) Bu yöntemin analoğu, **Aspose.Slides.IMasterLayoutSlideCollection.Add(Aspose.Slides.SlideLayoutType,Syste** yöntemi olup, [`IMasterSlide.layout_slides`](/slides/python-net/tr/aspose.slides/imasterslide/layout_slides) özelliği aracılığıyla erişilir.

### Exceptions

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | Desteklenmeyen bir `layout_type` parametresi değeri geçirilirse fırlatılır. Şu anda desteklenmeyen düzen türleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentNullException))** | `master` None ise fırlatılır. |
| **RuntimeError(Proxy error(ArgumentException))** | `master` başka bir sunuma aitse fırlatılır. |
| **RuntimeError(Proxy error(ArgumentException))** | `layout_name` değerinin `master`'ın düzen koleksiyonunda zaten kullanılıyor olması durumunda fırlatılır. |



### See Also
* sınıf [`IGlobalLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/igloballayoutslidecollection)
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`IMasterSlide`](/slides/python-net/tr/aspose.slides/imasterslide)
* enum [`SlideLayoutType`](/slides/python-net/tr/aspose.slides/slidelayouttype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)