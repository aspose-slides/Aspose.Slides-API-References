---
title: SetUpperLimit()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Ustawia górny limit
type: docs
weight: 144
url: /pl/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) metoda


Ustawia górny limit

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Wartość zwracana

Nowa instancja typu [IMathLimit](../../imathlimit/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) metoda


Ustawia górny limit

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Wartość zwracana

Nowa instancja typu [IMathLimit](../../imathlimit/)
## Uwagi



Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathLimit](../../imathlimit/)
* Klasa [IMathElement](../)
* Klasa [String](../../../system/string/)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)