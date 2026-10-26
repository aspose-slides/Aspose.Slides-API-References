---
title: Radical()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an.
type: docs
weight: 131
url: /de/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) Methode

Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argument von Radical |

### Rückgabewert

Neue Instanz vom Typ [IMathRadical](../../imathradical/)

## Anmerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) Methode

Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```

### Parameter

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument von Radical |

### Rückgabewert

Neue Instanz vom Typ [IMathRadical](../../imathradical/)

## Anmerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathRadical](../../imathradical/)
* Klasse [IMathElement](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)