---
title: idx_get()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen dizindeki öğeyi alır. Salt okunur IMathElement.
type: docs
weight: 14
url: /tr/aspose.slides.mathtext/imathelementcollection/idx_get/
---
## IMathElementCollection::idx_get(int32_t) metod


Belirtilen dizindeki öğeyi alır. Salt okunur [IMathElement](../../imathelement/).

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathElementCollection::idx_get(int32_t index)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Alınacak öğenin sıfır tabanlı dizini |
## Açıklamalar



Örnek: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = collection->idx_get(0);
```

## Ayrıca

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [IMathElementCollection](../)
* Ad Alanı [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)