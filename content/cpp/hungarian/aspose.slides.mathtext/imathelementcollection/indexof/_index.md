---
title: IndexOf()
second_title: Aspose.Slides C++ API referencia
description: Meghatározza egy adott matematikai elem indexét a gyűjteményben.
type: docs
weight: 40
url: /hu/aspose.slides.mathtext/imathelementcollection/indexof/
---
## IMathElementCollection::IndexOf(System::SharedPtr\<IMathElement\>) metódus


Meghatározza egy adott matematikai elem indexét a gyűjteményben.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::IndexOf(System::SharedPtr<IMathElement> item)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Az elem, amelyet a gyűjteményben keresni kell. |

### Visszatérési érték

*item* indexe, ha megtalálható a gyűjteményben; egyébként -1.
## Megjegyzések



Példa: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = collection->IndexOf(plusElement);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathElementCollection](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)