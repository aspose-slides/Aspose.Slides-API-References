---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Sunuma yeni bir düzen slaytı ekler.
type: docs
weight: 14
url: /tr/aspose.slides/igloballayoutslidecollection/add/
---
## IGlobalLayoutSlideCollection::Add(System::SharedPtr\<IMasterSlide\>, SlideLayoutType, System::String) metodu


Sunuma yeni bir düzen slaytı ekler.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::Add(System::SharedPtr<IMasterSlide> master, SlideLayoutType layoutType, System::String layoutName)=0
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| master | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Yeni bir düzen için ana slayt. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Yeni bir düzen için düzen tipi. Desteklenen düzen tipleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Şu anda desteklenmeyen diğer düzen tipleri: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Yeni bir düzen için ad. Verilen ad zaten kullanılıyorsa ArgumentException fırlatılır. Eğer null parametresi verilirse, ad otomatik olarak verilen düzen tipine göre oluşturulur (örneğin "Title Slide" ya da "1_Title Slide", "2_..", vb.). |

### Dönüş Değeri

Eklenen slayt.

## Açıklamalar

1) *layoutType* değerine sahip [SlideLayoutType::Custom](../../slidelayouttype/) eklenen düzen, yer tutucu ve şekil içermez. 2) Bu yöntemin analogu, [IMasterLayoutSlideCollection::Add(SlideLayoutType, String)](../../imasterlayoutslidecollection/add/) metodu, [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) özelliğiyle erişilir. 

## İlgili

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Class [String](../../../system/string/)
* Class [IGlobalLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)