---
title: Delimit()
second_title: Aspose.Slides for C++ API Referencia
description: Elválasztja a paramétereket a megadott elválasztó karakter használatával
type: docs
weight: 144
url: /hu/aspose.slides.mathtext/imathdelimiter/delimit/
---
## IMathDelimiter::Delimit(char16_t) metódus

Elválasztja a paramétereket a megadott elválasztó karakter használatával

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathDelimiter::Delimit(char16_t separatorCharacter)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separatorCharacter | char16_t | elválasztó karakter |

### Visszatérési érték

Ez az objektum az elválasztó karakter alkalmazása után
## Megjegyzések



Példa: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->Delimit(u'|');
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathDelimiter](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)