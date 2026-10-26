---
title: Equals()
second_title: C++ için Aspose.Slides API Referansı
description: İki IBaseSlide örneğinin eşit olup olmadığını belirler. Dönen değer, slaytın yapısı ve statik içeriğine dayanarak hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, benzersiz tanımlayıcı değerlerini, örneğin SlideId ve dinamik içeriği, örneğin Date Placeholder içindeki geçerli tarih değerini dikkate almaz.
type: docs
weight: 170
url: /tr/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) yöntemi

İki [IBaseSlide](../../ibaseslide/) örneğinin eşit olup olmadığını belirler. Dönen değer, slaytın yapısına ve statik içeriğine dayanarak hesaplanır. Tüm şekiller, stiller, metinler, animasyon ve diğer ayarlar vb. eşitse iki slayt eşittir. Karşılaştırma, benzersiz tanımlayıcı değerlerini, örneğin SlideId ve dinamik içeriği, örneğin Date [Placeholder](../../placeholder/) içindeki geçerli tarih değerini dikkate almaz.

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | Mevcut [IBaseSlide](../../ibaseslide/) ile karşılaştırılacak [IBaseSlide](../../ibaseslide/). |

### Dönüş Değeri

**true** eğer belirtilen [IBaseSlide](../../ibaseslide/) mevcut [IBaseSlide](../../ibaseslide/) ile eşitse; aksi takdirde **false**.

## Açıklamalar

Aşağıdaki örnek, iki slaytı nasıl karşılaştıracağınızı gösterir.
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IBaseSlide](../../ibaseslide/)
* Sınıf [BaseSlide](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)