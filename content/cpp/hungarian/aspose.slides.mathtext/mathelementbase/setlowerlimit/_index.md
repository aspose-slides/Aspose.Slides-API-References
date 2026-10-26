---
title: SetLowerLimit()
second_title: Aspose.Slides C++ API-referencia
description: Alsó határt vesz fel
type: docs
weight: 144
url: /hu/aspose.slides.mathtext/mathelementbase/setlowerlimit/
---
## MathElementBase::SetLowerLimit(System::SharedPtr\<IMathElement\>) metódus

Alsó határt vesz fel

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::SharedPtr<IMathElement> limit) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| limit | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | limit |

### Visszatérési érték

Új példány a(z) [IMathLimit](../../imathlimit/) típusból

## Megjegyzések

Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitValue = System::MakeObject<MathematicalText>(u"\U0001d45b→∞");
auto limitElement = baseElement->SetLowerLimit(limitValue);
```

## MathElementBase::SetLowerLimit(System::String) metódus

Alsó határt vesz fel

```cpp
System::SharedPtr<IMathLimit> Aspose::Slides::MathText::MathElementBase::SetLowerLimit(System::String limit) override
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
auto baseElement = System::MakeObject<MathematicalText>(u"lim");
auto limitElement = baseElement->SetLowerLimit(u"\U0001d45b→∞");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathLimit](../../imathlimit/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathElementBase](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)