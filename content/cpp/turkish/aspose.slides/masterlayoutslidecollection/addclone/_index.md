---
title: AddClone()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen yerleşim slaytının bir kopyasını koleksiyonun sonuna ekler.
type: docs
weight: 1
url: /tr/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method


Belirtilen yerleşim slaytının bir kopyasını koleksiyonun sonuna ekler.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) klonlamak için. |

### Dönüş Değeri

Eklenmiş slayt.

## Açıklama



1) Yeni yerleşim, bu yerleşim slaytları koleksiyonu için üst ana slaytla bağlantılı olacak. Bu nedenle, PowerPoint'te \"Use Destination Theme\" seçeneğiyle yapılan kopyala/yiğit işleminin bir benzeridir. 2) Bu yöntemin benzeri, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) yöntemi, [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) özelliğiyle erişilir. 
## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)