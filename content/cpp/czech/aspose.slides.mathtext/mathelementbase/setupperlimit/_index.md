---
title: SetUpperLimit()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Přijímá horní limit
type: docs
weight: 131
url: /cs/aspose.slides.mathtext/mathelementbase/setupperlimit/
---
## MathElementBase::SetUpperLimit(System::SharedPtr\<IMathElement\>) metoda


Přijímá horní limit

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::SharedPtr<IMathElement> limit) override
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Návratová hodnota

Nová instance typu [IMathLimit](../../imathlimit/)
## Poznámky



Příklad: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## MathElementBase::SetUpperLimit(System::String) metoda


Přijímá horní limit

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetUpperLimit(System::String limit) override
```


### Argumenty

| Parameter | Type | Description |
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
* Třída [IMathElement](../../imathelement/)
* Třída [MathElementBase](../)
* Třída [String](../../../system/string/)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)