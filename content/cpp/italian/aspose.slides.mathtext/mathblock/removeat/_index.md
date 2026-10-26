---
title: RemoveAt()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove l'elemento all'indice specificato della collezione.
type: docs
weight: 170
url: /it/aspose.slides.mathtext/mathblock/removeat/
---
## MathBlock::RemoveAt(int32_t) metodo

Rimuove l'elemento all'indice specificato della collezione.

```cpp
void Aspose::Slides::MathText::MathBlock::RemoveAt(int32_t index) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero dell'elemento da rimuovere. |
## Note

Esempio:
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->RemoveAt(2);
```

## Vedi anche

* Classe [MathBlock](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)