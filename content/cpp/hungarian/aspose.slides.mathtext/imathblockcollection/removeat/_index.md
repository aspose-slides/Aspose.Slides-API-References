---
title: RemoveAt()
second_title: Aspose.Slides for C++ API referenciája
description: Eltávolít egy elemet a gyűjtemény megadott indexén.
type: docs
weight: 53
url: /hu/aspose.slides.mathtext/imathblockcollection/removeat/
---
## IMathBlockCollection::RemoveAt(int32_t) metódus


Eltávolít egy elemet a gyűjtemény megadott indexén.

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::RemoveAt(int32_t index)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az eltávolítandó elem nullával kezdődő indexe. |
## Megjegyzések



Példa: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->RemoveAt(0);
```

## Lásd még

* Osztály [IMathBlockCollection](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)