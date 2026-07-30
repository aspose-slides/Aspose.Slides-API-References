---
title: Remove()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove la prima occorrenza di un oggetto specifico dalla collezione.
type: docs
weight: 131
url: /it/aspose.slides.mathtext/mathblock/remove/
---
## MathBlock::Remove(System::SharedPtr\<IMathElement\>) metodo


Rimuove la prima occorrenza di un oggetto specifico dalla collezione.

```cpp
bool Aspose::Slides::MathText::MathBlock::Remove(System::SharedPtr<IMathElement> item) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'oggetto da rimuovere dalla collezione. |

### Valore restituito

true se *item* è stato rimosso con successo dalla collezione; altrimenti, false. Questo metodo restituisce anche false se *item* non è presente nella collezione originale.
## Osservazioni



Esempio: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
mathBlock->Remove(plusElement);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IMathElement](../../imathelement/)
* classe [MathBlock](../)
* spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)