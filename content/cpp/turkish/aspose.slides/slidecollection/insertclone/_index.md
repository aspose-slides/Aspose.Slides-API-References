---
title: InsertClone()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler.
type: docs
weight: 66
url: /tr/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) yöntemi

Belirtilen slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni slaytın indeksi. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klonlamak için. |

### Dönüş Değeri

Eklenen slayt.

## Açıklamalar

Farklı sunumlar arasında bir slaytı klonlarken slaytın master slaytı da klonlanabilir. Aynı master slaydının birden fazla klonunun oluşmasını önlemek için otomatik olarak klonlanan master’ları izleyen dahili bir kayıt defteri kullanılır. Master slaytların manuel olarak klonlanması ne önlenir ne de kaydedilir. Klonlama süreci üzerinde daha fazla kontrol gerekirse slaytları klonlamak için [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) veya [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/), master slaytları klonlamak için ise [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) kullanın.

Aşağıdaki örnek, [Presentation](../../presentation/) içinde başka bir konuma nasıl klonlanacağını gösterir.  
```cpp
// Sunum dosyasını temsil eden Presentation sınıfını oluştur
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Aynı sunumdaki slayt koleksiyonunun sonuna istenen slaytı klonla
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Aynı sunumda belirtilen indekse istenen slaytı klonla
slides->InsertClone(2, slides->idx_get(1));
// Değiştirilmiş sunumu diske kaydet
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```  
Aşağıdaki örnek, [Presentation](../../presentation/) içinde başka bir konuma nasıl klonlanacağını gösterir.  
```cpp
// Kaynak sunum dosyasını yüklemek için Presentation sınıfını örnekle
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Hedef PPTX için Presentation sınıfını örnekle (slaytın klonlanacağı yer)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Hedef sunumu diske kaydet
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) yöntemi

Belirtilen slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni slaytın indeksi. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klonlamak için. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Yeni bir slayt için düzen slaytı. |

### Dönüş Değeri

Eklenen slayt.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) yöntemi

Belirtilen kaynak slaytı koleksiyonun belirtilen konumuna bir kopya olarak ekler. Belirtilen master’dan uygun düzen otomatik olarak seçilir (uygun düzen, kaynak slaydın düzeninin aynı Tür veya Adına sahiptir). Uygun bir düzen yoksa, kaynak slaydın düzeni klonlanır (allowCloneMissingLayout true ise) veya allowCloneMissingLayout false ise PptxEditException fırlatılır.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni slaytın indeksi. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klonlamak için. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Yeni bir slayt için master slaytı. |
| allowCloneMissingLayout | **bool** | Belirtilen master içinde uygun bir düzen yoksa, kaynak slaydın düzeni klonlanır (allowCloneMissingLayout true ise) veya allowCloneMissingLayout false ise PptxEditException fırlatılır. |

### Dönüş Değeri

Eklenen slayt.

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [SlideCollection](../)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)