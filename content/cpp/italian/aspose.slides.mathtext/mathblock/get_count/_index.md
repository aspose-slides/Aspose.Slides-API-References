---
title: get_Count()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene il numero di elementi matematici figlio effettivamente contenuti nella collezione. Solo lettura int32_t.
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathblock/get_count/
---
## MathBlock::get_Count() metodo

Ottiene il numero di elementi matematici figlio effettivamente contenuti nella collezione. Solo lettura **int32_t**.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::get_Count() override
```

## Osservazioni

Esempio:
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = mathBlock->get_Count();
```

## Vedi anche

* Classe [MathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)