---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun sonuna yeni bir düzen slaytı ekler.
type: docs
weight: 27
url: /tr/aspose.slides/imasterlayoutslidecollection/add/
---
## IMasterLayoutSlideCollection::Add(SlideLayoutType, System::String) yöntemi

Koleksiyonun sonuna yeni bir düzen slaytı ekler.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Yeni bir düzen için düzen türü. Desteklenen düzen türleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Şu anda desteklenmeyen diğer düzen türleri: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Yeni bir düzen için ad. Verilen ad zaten kullanılıyorsa ArgumentException fırlatılır. Null parametre verilirse, verilen düzen türüne göre otomatik olarak ad oluşturulur (örneğin "Title Slide" veya "1_Title Slide", "2_..", vb.). |

### Dönüş Değeri

Eklenen slayt.

## Açıklamalar

1) *layoutType*'in [SlideLayoutType::Custom](../../slidelayouttype/) değerine sahip eklenen düzen yer tutucu ve şekil içermez. 2) Bu yöntemin analogu, [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) özelliğiyle erişilen [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) yöntemidir. 

## Diğer Bağlantılar

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ILayoutSlide](../../ilayoutslide/)
* Sınıf [String](../../../system/string/)
* Sınıf [IMasterLayoutSlideCollection](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)