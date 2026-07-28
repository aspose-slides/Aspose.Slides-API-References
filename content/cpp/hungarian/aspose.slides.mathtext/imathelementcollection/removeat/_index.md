---
title: RemoveAt()
second_title: Aspose.Slides C++ API-referencia
description: Eltávolítja az elemet a gyűjtemény megadott indexén.
type: docs
weight: 105
url: /hu/aspose.slides.mathtext/imathelementcollection/removeat/
---
## IMathElementCollection::RemoveAt(int32_t) metódus


Eltávolítja az elemet a gyűjtemény megadott indexén.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::RemoveAt(int32_t index)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az eltávolítandó elem nullaalapú indexe. |
## Megjegyzések



Példa: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->RemoveAt(2);
```

## Lásd még

* Osztály [IMathElementCollection](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)