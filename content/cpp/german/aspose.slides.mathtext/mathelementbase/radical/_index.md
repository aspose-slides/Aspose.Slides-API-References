---
title: Radical()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an.
type: docs
weight: 118
url: /de/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) Methode


Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argument des Radikals |

### Rückgabewert

Neue Instanz vom Typ [IMathRadical](../../imathradical/)
## Bemerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) Methode


Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument des Radikals |

### Rückgabewert

Neue Instanz vom Typ [IMathRadical](../../imathradical/)
## Bemerkungen



Beispiel: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMathRadical](../../imathradical/)
* Klasse [IMathElement](../../imathelement/)
* Klasse [MathElementBase](../)
* Klasse [String](../../../system/string/)
* Namensraum [Aspose::Slides::MathText](../../)
* Bibliothek [Aspose.Slides](../../../)