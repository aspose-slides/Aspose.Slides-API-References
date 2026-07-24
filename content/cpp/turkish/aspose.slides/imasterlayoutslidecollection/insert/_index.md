---
title: Insert()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun belirtilen konumuna yeni bir yerleşim slaytı ekler.
type: docs
weight: 40
url: /tr/aspose.slides/imasterlayoutslidecollection/insert/
---
## IMasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) yöntemi


Koleksiyonun belirtilen konumuna yeni bir yerleşim slaytı ekler.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni slaytın indeksi. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Yeni bir yerleşim için düzen türü. Desteklenen düzen türleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Diğer düzen türleri şu anda desteklenmiyor: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Yeni bir yerleşim için ad. Geçilen ad zaten kullanılıyorsa ArgumentException fırlatılır. Null parametre geçilirse, ad, geçilen yerleşim türüne göre otomatik olarak oluşturulur (örneğin "Title Slide" veya "1_Title Slide", "2_..", vb.). |

### Dönüş Değeri

Eklenen slayt.

## Açıklamalar



[SlideLayoutType::Custom](../../slidelayouttype/) değerindeki *layoutType* için eklenen yerleşim yer tutucu ve şekil içermez. 

## Diğer Bağlantılar

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)