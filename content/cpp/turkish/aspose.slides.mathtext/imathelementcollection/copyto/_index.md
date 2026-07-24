---
title: CopyTo()
second_title: Aspose.Slides için C++ API Referansı
description: Belirtilen diziye kopyalar.
type: docs
weight: 118
url: /tr/aspose.slides.mathtext/imathelementcollection/copyto/
---
## IMathElementCollection::CopyTo(System::ArrayPtr\<System::SharedPtr\<IMathElement\>\>, int32_t) method

Kopyalanacak diziye kopyalar.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::CopyTo(System::ArrayPtr<System::SharedPtr<IMathElement>> array, int32_t arrayIndex)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| array | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\> | Kopyalanacak dizi. |
| arrayIndex | **int32_t** | Kopyalamanın başlayacağı indeks. |
## Açıklamalar

Örnek:
```cpp
System::SharedPtr<IMathElementCollection> collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
auto destinationArray = System::MakeArray<System::SharedPtr<IMathElement>>(collection->get_Count());
collection->CopyTo(destinationArray, 0);
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathElementCollection](../)
* İsim Alanı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)