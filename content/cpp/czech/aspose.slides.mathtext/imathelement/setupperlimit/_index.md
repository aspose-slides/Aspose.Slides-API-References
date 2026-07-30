---
title: SetUpperLimit()
second_title: Aspose.Slides pro C++ - reference API
description: Přijímá horní limit
type: docs
weight: 144
url: /cs/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) metoda


Přijímá horní limit

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
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
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) metoda


Přijímá horní limit

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
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
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathLimit](../../imathlimit/)
* Třída [IMathElement](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)