---
title: Remove()
second_title: Riferimento API di Aspose.Slides per C++
description: Rimuove la prima occorrenza di un oggetto specifico dalla collezione.
type: docs
weight: 92
url: /it/aspose.slides.mathtext/imathelementcollection/remove/
---
## IMathElementCollection::Remove(System::SharedPtr\<IMathElement\>) metodo

Rimuove la prima occorrenza di un oggetto specifico dalla collezione.

```cpp
virtual bool Aspose::Slides::MathText::IMathElementCollection::Remove(System::SharedPtr<IMathElement> item)=0
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
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
collection->Remove(plusElement);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathElementCollection](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)