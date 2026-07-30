---
title: Remove()
second_title: Riferimento API Aspose.Slides per C++
description: Rimuove la prima occorrenza di un oggetto specifico dalla collezione/>
type: docs
weight: 40
url: /it/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) metodo

Rimuove la prima occorrenza di un oggetto specifico dalla collezione/>.

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | L'oggetto da rimuovere dalla collezione. |

### Valore restituito

true se *item* è stato rimosso con successo dalla collezione; altrimenti, false. Questo metodo restituisce anche false se *item* non è presente nella collezione originale/>.

## Osservazioni

Esempio: 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathBlockCollection](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)