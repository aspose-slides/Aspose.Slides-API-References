---
title: Insert()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce un elemento matematico nella raccolta all'indice specificato.
type: docs
weight: 53
url: /it/aspose.slides.mathtext/imathelementcollection/insert/
---
## IMathElementCollection::Insert(int32_t, System::SharedPtr\<IMathElement\>) metodo

Inserisce un elemento matematico nella raccolta all'indice specificato.

```cpp
virtual void Aspose::Slides::MathText::IMathElementCollection::Insert(int32_t index, System::SharedPtr<IMathElement> item)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | L'indice basato su zero al quale [IMathElement](../../imathelement/) dovrebbe essere inserito. |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Il [IMathElement](../../imathelement/) da inserire. |
## Osservazioni



Esempio: 
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
collection->Add(plusElement);
collection->Insert(0, System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathElementCollection](../)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)