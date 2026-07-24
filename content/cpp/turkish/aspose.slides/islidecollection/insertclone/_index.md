---
title: InsertClone()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen bir slaydın kopyasını koleksiyonun belirtilen konumuna ekler.
type: docs
weight: 27
url: /tr/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) metodu

Belirtilen slayttan bir kopya, koleksiyonun belirtilen konumuna eklenir.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Yeni slaydın indeksi. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klonlamak için. |

### Dönüş Değeri

Eklenen slayt.

## Açıklamalar

Farklı sunumlar arasında bir slayt klonlanırken slaytın master'ı da klonlanabilir. Aynı master slaytının birden fazla kopyasının oluşturulmasını önlemek için iç kayıt defteri otomatik klonlanan master’ları izler. Master slaytların manuel klonlanması ne önlenir ne de kayıt altına alınır. Klonlama sürecini daha çok kontrol etmek istiyorsanız slaytları klonlamak için [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) veya [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./), master slaytları klonlamak için ise [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) kullanın. 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metodu

Belirtilen slayttan bir kopya, koleksiyonun belirtilen konumuna eklenir.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Yeni slaydın indeksi. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klonlamak için. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Yeni slayt için düzen slaytı. |

### Dönüş Değeri

Eklenen slayt.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metodu

Belirtilen kaynak slayttan bir kopya, koleksiyonun belirtilen konumuna eklenir. Uygun düzen, belirtilen master’dan otomatik olarak seçilir (uygun düzen, kaynak slaydın düzeniyle aynı Type ya da Name’e sahip olandır). Uygun bir düzen yoksa, kaynak slaydın düzeni klonlanır (allowCloneMissingLayout true ise) ya da PptxEditException fırlatılır (allowCloneMissingLayout false ise).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Yeni slaydın indeksi. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klonlamak için. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Yeni slayd için master slayt. |
| allowCloneMissingLayout | **bool** | Belirtilen master’da uygun bir düzen yoksa kaynak slaydın düzeni klonlanır (allowCloneMissingLayout true ise) ya da PptxEditException fırlatılır (allowCloneMissingLayout false ise). |

### Dönüş Değeri

Eklenen slayt.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)