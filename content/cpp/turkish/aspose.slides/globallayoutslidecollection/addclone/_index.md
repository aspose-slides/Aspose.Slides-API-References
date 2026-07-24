---
title: AddClone()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen bir yerleşim slaytının bir kopyasını sunuma ekler.
type: docs
weight: 1
url: /tr/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metot


Belirtilen bir yerleşim slaytının bir kopyasını sunuma ekler.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) klonlamak için. |

### Dönüş Değeri

Eklenen slayt.
## Açıklamalar



Farklı sunumlar arasında bir yerleşim klonlandığında, kaynak biçimlendirmeyi korumak için yerleşimin ana slaytı da klonlanabilir. Otomatik olarak klonlanan ana slaytları izlemek ve aynı ana slaytın birden fazla kopyasının oluşturulmasını önlemek için iç kayıt defteri kullanılır. Ana slaytların elle klonlanması ne önlenir ne de kaydedilir. 
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) metot


Belirtilen bir yerleşim slaytının bir kopyasını sunuma ekler.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) klonlamak için. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Yeni bir yerleşim için ana slayt. |

### Dönüş Değeri

Eklenen slayt.
## Açıklamalar



1) Yeni yerleşim, hedef sunumdaki tanımlı ana slaytla bağlantılandırılacak. Bu, PowerPoint'te \"Use Destination Theme\" seçeneğiyle kopyala/yapıştır işleminin bir benzeri gibidir. 2) Bu yöntemin bir benzeri, [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) yöntemi olup [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) özelliğiyle erişilir. 
## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ILayoutSlide](../../ilayoutslide/)
* Sınıf [GlobalLayoutSlideCollection](../)
* Sınıf [IMasterSlide](../../imasterslide/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)