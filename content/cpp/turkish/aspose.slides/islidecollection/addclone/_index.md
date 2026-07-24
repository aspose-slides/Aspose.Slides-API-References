---
title: AddClone()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen bir slaytın bir kopyasını koleksiyonun sonuna ekler.
type: docs
weight: 14
url: /tr/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) metod

Belirtilen bir slaytın bir kopyasını koleksiyonun sonuna ekler.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) kopyalamak için. |

### Dönüş Değeri

Yeni slayt.

## Açıklamalar

Farklı sunumlar arasında bir slaytı kopyalarken slaytın ana taslağı da kopyalanabilir. Otomatik olarak kopyalanan ana taslakları izlemek ve aynı ana slayttan birden fazla kopya oluşturulmasını önlemek için dahili bir kayıt defteri kullanılır. Ana slaytların elle kopyalanması ne önlenir ne de kaydedilir. Kopyalama sürecinde daha fazla kontrol gerekiyorsa slaytları kopyalamak için [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) veya [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./), düzenleri kopyalamak için [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) veya [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) ve ana taslakları kopyalamak için [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) kullanın.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) metod

Belirtilen bir slaytın bir kopyasını belirtilen bölümün sonuna ekler.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) kopyalamak için. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) yeni bir slayt için. |

### Dönüş Değeri

Yeni slayt.

## Açıklamalar

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Şimdi ikinci bölüm, ilk slaydın bir kopyasını içeriyor.
```

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metod

Belirtilen bir slaytın bir kopyasını koleksiyonun sonuna ekler.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) kopyalamak için. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Yeni bir slayt için düzen slaytı. |

### Dönüş Değeri

Yeni slayt.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metod

Belirtilen bir kaynak slaytın bir kopyasını koleksiyonun sonuna ekler. Uygun düzen, belirtilen ana taslaktan otomatik olarak seçilir (uygun düzen, kaynak slaytın düzeniyle aynı Tür veya Ad'a sahip düzen olur). Eğer uygun bir düzen yoksa, kaynak slaytın düzeni kopyalanır (allowCloneMissingLayout true ise) veya allowCloneMissingLayout false ise PptxEditException fırlatılır.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) kopyalamak için. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Yeni bir slayt için ana slayt. |
| allowCloneMissingLayout | **bool** | Belirtilen ana taslakta uygun bir düzen yoksa, kaynak slaytın düzeni kopyalanır (allowCloneMissingLayout true ise) veya allowCloneMissingLayout false ise PptxEditException fırlatılır. |

### Dönüş Değeri

Yeni slayt.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Class [ISection](../../isection/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)