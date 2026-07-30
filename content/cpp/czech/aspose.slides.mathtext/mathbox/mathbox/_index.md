---
title: MathBox()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Inicializuje MathBox se zadaným prvkem jako argumentem
type: docs
weight: 144
url: /cs/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) konstruktor

Inicializuje [MathBox](../) zadaným prvkem jako argument

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Základní prvek, na který se box aplikuje. Může být null. |

## Poznámky

Příklad:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IMathElement](../../imathelement/)
* Třída [MathBox](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)