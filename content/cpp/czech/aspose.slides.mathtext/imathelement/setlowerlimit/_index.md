---
title: SetLowerLimit()
second_title: Aspose.Slides pro C++ reference API
description: Přijímá dolní limit
type: docs
weight: 157
url: /cs/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) metoda


Přijímá dolní limit

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Návratová hodnota

Nová instance typu [IMathLimit](../../imathlimit/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) metoda


Přijímá dolní limit

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
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
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathLimit](../../imathlimit/)
* Třída [IMathElement](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)