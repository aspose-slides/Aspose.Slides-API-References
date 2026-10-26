---
title: Join()
second_title: Aspose.Slides C++ API hivatkozás
description: Összekapcsol egy matematikai elemet ezzel a matematikai blokkal
type: docs
weight: 183
url: /hu/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) metódus


Összekapcsol egy matematikai elemet ezzel a matematikai blokkal

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The element to be joined |

### Visszatérési érték

Az aktuális [IMathBlock](../../imathblock/) példány

## Megjegyzések



Példa: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) metódus


Összekapcsol egy matematikai szöveget ezzel a matematikai blokkal

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Mathematical text to be joined |

### Visszatérési érték

Egy új [IMathBlock](../../imathblock/), amely tartalmazza ezt a példányt és a megadott argumentumot

## Megjegyzések



Példa: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathBlock](../)
* Osztály [String](../../../system/string/)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)