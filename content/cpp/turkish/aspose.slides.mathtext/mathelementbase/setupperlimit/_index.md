---
title: SetUpperLimit()
second_title: Aspose.Slides for C++ API Referansı
description: Üst sınırı alır
type: docs
weight: 131
url: /tr/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) metodu

Üst sınırı alır

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Dönüş Değeri

Yeni [IMathLimit](../../imathlimit/) tipinde örnek

## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) metodu

Üst sınırı alır

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Dönüş Değeri

Yeni [IMathLimit](../../imathlimit/) tipinde örnek

## Açıklamalar



Örnek: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathLimit](../../imathlimit/)
* Class [IMathElement](../../imathelement/)
* Class [MathElementBase](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)