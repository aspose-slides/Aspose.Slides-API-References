---
title: AddClone()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen bir slaytın bir kopyasını koleksiyonun sonuna ekler.
type: docs
weight: 53
url: /tr/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) method


Belirtilen slaytın bir kopyasını koleksiyonun sonuna ekler.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) kopyalamak için. |

### Dönüş Değeri

Yeni slayt.
## Açıklamalar



Farklı sunumlar arasında bir slaytı kopyalarken slaytın master'ı da kopyalanabilir. Otomatik olarak kopyalanan master'ları takip etmek ve aynı master slaytının birden çok kopyasının oluşturulmasını önlemek için dahili bir kayıt defteri kullanılır. Master slaytların manuel kopyalanması ne engellenir ne de kayıt altına alınır. Kopyalama süreci üzerinde daha fazla kontrol gerektiriyorsanız slaytları kopyalamak için [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) veya [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/), düzenleri kopyalamak için [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) veya [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) ve master'ları kopyalamak için [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) kullanın. 
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) method


Belirtilen slaytın bir kopyasını belirtilen bölümün sonuna ekler.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
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
// Şimdi ikinci bölüm, birinci slaydın bir kopyasını içeriyor.
```


## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method


Belirtilen slaytın bir kopyasını koleksiyonun sonuna ekler.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) kopyalamak için. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Yeni bir slayt için yerleşim slaytı. |

### Dönüş Değeri

Yeni slayt.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method


Belirtilen kaynak slaytın bir kopyasını koleksiyonun sonuna ekler. Uygun yerleşim, belirtilen master'dan otomatik olarak seçilecektir (uygun yerleşim, kaynak slaytın yerleşimiyle aynı Tür veya Ad'a sahip yerleşimdir). Eğer uygun bir yerleşim yoksa, kaynak slaytın yerleşimi (allowCloneMissingLayout true ise) kopyalanır veya (allowCloneMissingLayout false ise) PptxEditException fırlatılır.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) kopyalamak için. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Yeni bir slayt için master slayt. |
| allowCloneMissingLayout | **bool** | Belirtilen master içinde uygun bir yerleşim yoksa, kaynak slaytın yerleşimi (allowCloneMissingLayout true ise) kopyalanır veya (allowCloneMissingLayout false ise) PptxEditException fırlatılır. |

### Dönüş Değeri

Yeni slayt.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlide](../../islide/)
* Sınıf [SlideCollection](../)
* Sınıf [ISection](../../isection/)
* Sınıf [ILayoutSlide](../../ilayoutslide/)
* Sınıf [IMasterSlide](../../imasterslide/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)