---
title: InsertClone()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen bir master slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. Bağlantılı yerleşim slaytları da kopyalanacaktır.
type: docs
weight: 105
url: /tr/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) yöntemi

Belirtilen bir master slaytın bir kopyasını koleksiyonun belirtilen konumuna ekler. Bağlantılı yerleşim slaytları da kopyalanacaktır.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Yeni slaytın indeksi. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) klonlamak için. |

### Dönüş Değeri

Eklenmiş master slayt.

## Açıklamalar

Aşağıdaki örnek, başka bir PowerPoint [Presentation](../../presentation/) içinde master slaytı nasıl klonlayacağınızı gösterir.
```cpp
// Kaynak sunum dosyasını yüklemek için Presentation sınıfını örnekle
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Hedef sunum (slaytın klonlanacağı yer) için Presentation sınıfını örnekle
auto destPres = System::MakeObject<Presentation>();

// Kaynak sunumdaki slayt koleksiyonundan ISlide'ı oluştur
// Master slayt
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Hedef sunumun Master Slaytlarını al
auto masters = destPres->get_Masters();
// İstenen master slaytı kaynak sunumdan, hedefin master koleksiyonuna kopyala
// Hedef sunum
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Hedef sunumdaki slayt koleksiyonu
auto slides = destPres->get_Slides();
// Kaynak slaytı hedef slayt koleksiyonuna kopyala.
slides->AddClone(sourceSlide, iSlide, true);
// Hedef sunumu diske kaydet
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMasterSlide](../../imasterslide/)
* Sınıf [MasterSlideCollection](../)
* AdAlanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)