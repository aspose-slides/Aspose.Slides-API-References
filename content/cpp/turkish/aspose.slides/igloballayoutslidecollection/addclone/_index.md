---
title: AddClone()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen bir layout slaytının bir kopyasını sunuma ekler.
type: docs
weight: 1
url: /tr/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method


Belirtilen bir layout slaytının bir kopyasını sunuma ekler.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) klonlamak için. |

### Dönüş Değeri

Eklenen slayt.
## Açıklamalar



Farklı sunumlar arasında bir layout kopyalanırken, kaynak biçimlendirmesini korumak için layout'un master'ı da klonlanabilir. Otomatik olarak klonlanan master'ları takip etmek ve aynı master slaytının birden fazla klonunun oluşturulmasını önlemek için dahili bir kayıt defteri kullanılır. Master slaytların manuel klonlanması ne engellenir ne de kaydedilir. 
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) method


Belirtilen bir layout slaytının bir kopyasını sunuma ekler.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```


### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) klonlamak için. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Yeni bir layout için master slayt. |

### Dönüş Değeri

Eklenen slayt.
## Açıklamalar



Yeni layout, hedef sunumdaki tanımlı master ile bağlantılanacaktır. Bu nedenle PowerPoint’te “Use Destination Theme” seçeneğiyle yapılan kopyala/yapıştır işleminin bir benzeri olarak düşünülebilir. 
## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IGlobalLayoutSlideCollection](../)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)