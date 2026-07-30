---
title: IndexOf()
second_title: Riferimento API Aspose.Slides per C++
description: Determina l'indice di un elemento matematico specifico nella collezione.
type: docs
weight: 40
url: /it/aspose.slides.mathtext/imathelementcollection/indexof/
---
## IMathElementCollection::IndexOf(System::SharedPtr\<IMathElement\>) metodo


Determina l'indice di un elemento matematico specifico nella collezione.

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::IndexOf(System::SharedPtr<IMathElement> item)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'elemento da trovare nella collezione. |

### Valore restituito

L'indice di *item*  se trovato nella collezione; altrimenti, -1.
## Osservazioni



Esempio: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = collection->IndexOf(plusElement);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)