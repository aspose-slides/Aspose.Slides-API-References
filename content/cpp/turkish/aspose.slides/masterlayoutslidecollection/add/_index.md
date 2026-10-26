---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Koleksiyonun sonuna yeni bir yerleşim slaytı ekler.
type: docs
weight: 27
url: /tr/aspose.slides/masterlayoutslidecollection/add/
---
## MasterLayoutSlideCollection::Add(SlideLayoutType, System::String) yöntemi


Koleksiyonun sonuna yeni bir yerleşim slaytı ekler.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::Add(SlideLayoutType layoutType, System::String layoutName) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| layoutType | [SlideLayoutType](../../slidelayouttype/) | Yeni bir yerleşim için yerleşim türü. Desteklenen yerleşim türleri: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Diğer yerleşim türleri şu anda desteklenmemektedir: Text, TwoColumnText, [Table](../../table/), TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | [System::String](../../../system/string/) | Yeni bir yerleşim için ad. Verilen ad zaten kullanımda ise ArgumentException fırlatılacak. Eğer null parametre verilirse, ad otomatik olarak verilen yerleşim türüne göre oluşturulur (örneğin "Title Slide" veya "1_Title Slide", "2_..", vb.). |

### Dönüş Değeri

Eklenen slayt.

## Açıklamalar

1) [SlideLayoutType::Custom](../../slidelayouttype/) değerine sahip *layoutType* için eklenen yerleşim hiçbir yer tutucu ve şekil içermiyor. 2) Bu yöntemin analogu [IGlobalLayoutSlideCollection::Add(SharedPtr<IMasterSlide>, SlideLayoutType, String)](../../igloballayoutslidecollection/add/) yöntemi olup [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) özelliğiyle erişilir. 

## Diğer Bağlantılar

* Enum [SlideLayoutType](../../slidelayouttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [String](../../../system/string/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)