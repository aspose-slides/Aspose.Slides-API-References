---
title: SetLowerLimit()
second_title: Aspose.Slides pro C++ API Reference
description: Přijímá dolní mez
type: docs
weight: 144
url: /cs/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) metoda

Přijímá dolní mez

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Návratová hodnota

Nová instance typu [IMathLimit](../../imathlimit/)

## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) metoda

Přijímá dolní mez

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Návratová hodnota

Nová instance typu [IMathLimit](../../imathlimit/)

## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathLimit](../../imathlimit/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathElementBase](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)