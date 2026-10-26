---
title: MathArray()
second_title: Aspose.Slides for C++ API Referansı
description: Matematiksel bir dizi oluşturur ve belirtilen öğeyi diziye yerleştirir
type: docs
weight: 144
url: /tr/aspose.slides.mathtext/matharray/matharray/
---
## MathArray::MathArray(System::SharedPtr\<IMathElement\>) constructor

Matematiksel bir dizi oluşturur ve belirtilen öğeyi diziye yerleştirir

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<IMathElement> element)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Diziye yerleştirilecek öğe |

## Açıklamalar

Örnek: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## MathArray::MathArray(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) constructor

Matematiksel bir dizi oluşturur ve belirtilen öğeleri diziye yerleştirir

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> elements)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Diziye yerleştirilecek öğeler |

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IMathElement](../../imathelement/)
* Sınıf [MathArray](../)
* Sınıf [IEnumerable](../../../system.collections.generic/ienumerable/)
* Ad Uzayı [Aspose::Slides::MathText](../../)
* Kütüphane [Aspose.Slides](../../../)