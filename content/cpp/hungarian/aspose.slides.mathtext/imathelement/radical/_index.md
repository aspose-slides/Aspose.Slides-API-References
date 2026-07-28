---
title: Radical()
second_title: Aspose.Slides for C++ API referencia
description: Megadja a megadott fokú matematikai gyököt a megadott argumentumból.
type: docs
weight: 131
url: /hu/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) metódus

Megadja a megadott fokú matematikai gyököt a megadott argumentumból.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argument of Radical |

### Visszatérési érték

Új példány a(z) [IMathRadical](../../imathradical/) típusú

## Megjegyzések



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) metódus

Megadja a megadott fokú matematikai gyököt a megadott argumentumból.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument of Radical |

### Visszatérési érték

Új példány a(z) [IMathRadical](../../imathradical/) típusú

## Megjegyzések



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathRadical](../../imathradical/)
* Osztály [IMathElement](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)