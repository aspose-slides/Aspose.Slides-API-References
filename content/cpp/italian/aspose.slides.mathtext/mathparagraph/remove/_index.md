---
title: Remove()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove la prima occorrenza di un oggetto specifico dalla collezione/>
type: docs
weight: 105
url: /it/aspose.slides.mathtext/mathparagraph/remove/
---
## MathParagraph::Remove(System::SharedPtr\<IMathBlock\>) metodo


Rimuove la prima occorrenza di un oggetto specifico dalla collezione/>.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Remove(System::SharedPtr<IMathBlock> mathBlock) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | L'oggetto da rimuovere dalla collezione. |

### Valore restituito

true se *mathBlock* è stato rimosso con successo dalla collezione; altrimenti, false. Questo metodo restituisce anche false se *mathBlock* non è presente nella collezione originale/>.

## Note



Esempio: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
mathParagraph->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x")));
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
mathParagraph->Remove(block);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)