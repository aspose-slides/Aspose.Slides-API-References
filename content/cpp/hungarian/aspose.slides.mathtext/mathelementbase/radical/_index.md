---
title: Radical()
second_title: Aspose.Slides C++ API hivatkozás
description: Megadja a megadott fokú matematikai gyököt a megadott argumentumból.
type: docs
weight: 118
url: /hu/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) metódus

Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | A Radical argumentuma |

### Visszatérési érték

Új példány a(z) [IMathRadical](../../imathradical/) típusból
## Megjegyzések



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) metódus

Meghatározza a megadott fokú matematikai gyököt a megadott argumentumból.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | A Radical argumentuma |

### Visszatérési érték

Új példány a(z) [IMathRadical](../../imathradical/) típusból
## Megjegyzések



Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathRadical](../../imathradical/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathElementBase](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)