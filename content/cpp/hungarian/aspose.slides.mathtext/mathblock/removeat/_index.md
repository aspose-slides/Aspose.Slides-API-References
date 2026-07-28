---
title: RemoveAt()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja a gyűjtemény megadott indexén lévő elemet.
type: docs
weight: 170
url: /hu/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) metódus


Eltávolítja a gyűjtemény megadott indexén lévő elemet.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az eltávolítandó elem nullárral kezdődő indexe. |
## Megjegyzések



Példa: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## Lásd még

* Osztály [MathBlock](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)