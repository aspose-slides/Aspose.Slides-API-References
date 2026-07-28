---
title: Join()
second_title: Aspose.Slides C++ API referencia
description: Összevon egy matematikai elemet és létrehoz egy matematikai blokkot
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) metódus

Összevon egy matematikai elemet és egy matematikai blokkot hoz létre

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az összevonandó elem |

### Visszatérési érték

Egy új [IMathBlock](../../imathblock/) amely ezt a példányt és a megadott argumentumot tartalmaz

## Megjegyzések

Példa: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) metódus

Összevon egy matematikai szöveget és egy matematikai blokkot hoz létre

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Az összevonandó matematikai szöveg |

### Visszatérési érték

Egy új [IMathBlock](../../imathblock/) amely ezt a példányt és a megadott argumentumot tartalmaz

## Megjegyzések

Példa: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathElementBase](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)