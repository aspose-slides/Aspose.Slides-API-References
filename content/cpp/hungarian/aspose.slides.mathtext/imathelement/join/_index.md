---
title: Join()
second_title: Aspose.Slides for C++ API referenciája
description: Összeilleszt egy matematikai elemet és egy matematikai blokkot hoz létre
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) metódus

Összeilleszt egy matematikai elemet és egy matematikai blokkot hoz létre

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Az összeillesztendő elem |

### Visszatérési érték

Egy új [IMathBlock](../../imathblock/), amely tartalmazza ezt a példányt és a megadott argumentumot

## Megjegyzés



Példa: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) metódus


Összeilleszt egy matematikai szöveget és egy matematikai blokkot hoz létre

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Az összeillesztendő matematikai szöveg |

### Visszatérési érték

Egy új [IMathBlock](../../imathblock/), amely tartalmazza ezt a példányt és a megadott argumentumot

## Megjegyzés



Példa: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [IMathElement](../)
* Osztály [String](../../../system/string/)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)