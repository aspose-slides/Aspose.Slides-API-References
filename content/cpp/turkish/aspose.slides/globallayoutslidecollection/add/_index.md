---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Sunuma yeni bir yerleşim slaydı ekler.
type: docs
weight: 14
url: /tr/aspose.slides/globallayoutslidecollection/add/
---
## GlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) method

Sunuma yeni bir yerleşim slaydı ekler.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Yeni bir yerleşim için ana slayt. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Yeni bir yerleşim için yerleşim tipi. Desteklenen yerleşim tipleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Şu anda desteklenmeyen diğer yerleşim tipleri: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Yeni bir yerleşim için ad. Eğer verilen ad zaten kullanılıyorsa ArgumentException fırlatılır. Eğer null parametre verilirse ad, verilen yerleşim tipine göre otomatik olarak üretilir (örneğin "Title Slide" veya "1_Title Slide", "2_..", vb.). |

### Dönüş Değeri

Eklenen slayt.

## Açıklamalar

1) *layoutType* değerinin [SlideLayoutType::Custom](../../slidelayouttype/) için eklenen yerleşim, yer tutucu ve şekil içermez. 2) Bu yöntemin analogu [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) yöntemi olup [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) özelliği ile erişilir. 

## İlgili

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Class [String](../../../system/string/)
* Class [GlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)