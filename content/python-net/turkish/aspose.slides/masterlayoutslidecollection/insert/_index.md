---
title: insert method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/masterlayoutslidecollection/insert/
weight: 40
---
## insert(self, index, layout_type, layout_name) {#int-slidelayouttype-str}
Koleksiyonun belirtilen konumuna yeni bir yerleşim slaydı ekler.

### Döndürür

Ekleme yapılan slayt.

```python
def insert(self, index, layout_type, layout_name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Yeni slaydın indeksi. |
| layout_type | [`SlideLayoutType`](/slides/python-net/tr/aspose.slides/slidelayouttype) | Yeni bir yerleşim için yerleşim türü.<br/><br/>            Desteklenen yerleşim türleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom.<br/><br/>            Şu anda desteklenmeyen diğer yerleşim türleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layout_name | **str** | Yeni bir yerleşim için ad. Eğer verilen ad zaten kullanılıyorsa ArgumentException atılacak.<br/><br/>            Eğer None parametresi verilirse, ad verilen yerleşim türüne göre otomatik olarak oluşturulur <br/><br/>            (örneğin "Title Slide" veya "1_Title Slide", "2_..", vb.). |

### Açıklama

SlideLayoutType.Custom değerine sahip `layout_type` için eklenen yerleşimde yer tutucu ve şekil yoktur.

### İstisnalar

| İstisna | Açıklama |
| :- | :- |
| **RuntimeError(Proxy error(NotImplementedException))** | `layout_type` parametresine desteklenmeyen bir değer gönderildiğinde atılır. Şu anda desteklenmeyen yerleşim türleri: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| **RuntimeError(Proxy error(ArgumentException))** | `layout_name` değerinin bu yerleşim koleksiyonunda zaten kullanılıyor olması durumunda atılır. |

### Ayrıca Bakınız
* sınıf [`ILayoutSlide`](/slides/python-net/tr/aspose.slides/ilayoutslide)
* sınıf [`MasterLayoutSlideCollection`](/slides/python-net/tr/aspose.slides/masterlayoutslidecollection)
* enum [`SlideLayoutType`](/slides/python-net/tr/aspose.slides/slidelayouttype)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)