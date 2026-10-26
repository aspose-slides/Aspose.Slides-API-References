---
title: SetLowerLimit()
second_title: Aspose.Slides C++ API Referenciája
description: Alsó határt vesz fel
type: docs
weight: 157
url: /hu/aspose.slides.mathtext/imathelement/setlowerlimit/
---
## IMathElement::SetLowerLimit(System::SharedPtr\<IMathElement\>) metódus

Alsó határt vesz fel

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::SharedPtr<IMathElement> limit)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | határ |

### Visszatérési érték

Új példány a(z) [IMathLimit](../../imathlimit/) típusból

## Megjegyzések



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## IMathElement::SetLowerLimit(System::String) metódus

Alsó határt vesz fel

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetLowerLimit(System::String limit)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | határ |

### Visszatérési érték

Új példány a(z) [IMathLimit](../../imathlimit/) típusból

## Megjegyzések



Példa: 
```cpp
System::SharedPtr<IMathElement> baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathLimit](../../imathlimit/)
* Class [IMathElement](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)