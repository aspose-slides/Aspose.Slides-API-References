---
title: SetUpperLimit()
second_title: Aspose.Slides C++ API referenciája
description: Felveszi a felső határt
type: docs
weight: 144
url: /hu/aspose.slides.mathtext/imathelement/setupperlimit/
---
## IMathElement::SetUpperLimit(System::SharedPtr\<IMathElement\>) metódus

Felveszi a felső határt

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::SharedPtr<IMathElement> limit)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | limit |

### Visszatérési érték

Új példány a(z) [IMathLimit](../../imathlimit/) típusból
## Megjegyzések



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitValue = System::MakeObject<MathematicalText>(u"y?>1");
auto limitElement = baseElement->SetUpperLimit(limitValue);
```

## IMathElement::SetUpperLimit(System::String) metódus

Felveszi a felső határt

```cpp
virtual System::SharedPtr<IMathLimit> Aspose::Slides::MathText::IMathElement::SetUpperLimit(System::String limit)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| limit | [System::String](../../../system/string/) | limit |

### Visszatérési érték

Új példány a(z) [IMathLimit](../../imathlimit/) típusból
## Megjegyzések



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"y");
auto limitElement = baseElement->SetUpperLimit(u"y?>1");
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathLimit](../../imathlimit/)
* Osztály [IMathElement](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)