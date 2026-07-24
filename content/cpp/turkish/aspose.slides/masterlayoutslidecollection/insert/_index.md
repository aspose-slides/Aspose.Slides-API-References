---
title: Insert()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun belirtilen konumuna yeni bir yerleşim slaytı ekler.
type: docs
weight: 40
url: /tr/aspose.slides/masterlayoutslidecollection/insert/
---
## MasterLayoutSlideCollection::Insert(int32_t, SlideLayoutType, System::String) yöntemi


Koleksiyonun belirtilen konumuna yeni bir yerleşim slaytı ekler.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Insert(int32_t index, SlideLayoutType layoutType, System::String layoutName) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni slaytın indeksi. |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Yeni bir yerleşim için düzen türü. Desteklenen düzen türleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Diğer düzen türleri şu anda desteklenmemektedir: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Yeni bir yerleşim için ad. Geçerli ad zaten kullanılıyorsa ArgumentException fırlatılır. Null parametre geçirilirse ad, verilen düzen türüne göre otomatik olarak üretilir (örneğin "Title Slide" ya da "1_Title Slide", "2_..", vb.). |

### Dönüş Değeri

Eklelen slayt.

## Açıklamalar

Eklene yerleşim, *layoutType* değer [SlideLayoutType::Custom](../../slidelayouttype/) için hiçbir yer tutucu ve şekil içermez. 

## Ayrıca Bakınız

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ILayoutSlide](../../ilayoutslide/)
* Sınıf [String](../../../system/string/)
* Sınıf [MasterLayoutSlideCollection](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)