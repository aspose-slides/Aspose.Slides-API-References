---
title: IndexOf()
second_title: Aspose.Slides C++ API referencia
description: Megállapítja egy adott IMathBlock indexét a gyűjteményben.
type: docs
weight: 79
url: /hu/aspose.slides.mathtext/imathblockcollection/indexof/
---
## IMathBlockCollection::IndexOf(System::SharedPtr\<IMathBlock\>) metódus

Meghatározza egy adott [IMathBlock](../../imathblock/) indexét a gyűjteményben.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::IndexOf(System::SharedPtr<IMathBlock> item)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Az elem, amelyet a gyűjteményben keresni kell. |

### Visszatérési érték

Az *item* indexe, ha megtalálható a gyűjteményben; egyébként -1.

## Megjegyzések

Példa:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
int32_t index = blockCollection->IndexOf(block);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathBlock](../../imathblock/)
* Osztály [IMathBlockCollection](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)