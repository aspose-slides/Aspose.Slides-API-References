---
title: RemoveAt()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove un elemento all'indice specificato della collezione.
type: docs
weight: 157
url: /it/aspose.slides.mathtext/mathparagraph/removeat/
---
## MathParagraph::RemoveAt(int32_t) metodo


Rimuove un elemento all'indice specificato della collezione.

```cpp
void Aspose::Slides::MathText::MathParagraph::RemoveAt(int32_t index) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice a base zero dell'elemento da rimuovere. |
## Osservazioni



Esempio: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->RemoveAt(0);
```

## Vedi anche

* Classe [MathParagraph](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)