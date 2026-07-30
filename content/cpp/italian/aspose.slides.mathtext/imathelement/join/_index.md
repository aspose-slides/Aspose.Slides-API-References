---
title: Join()
second_title: Riferimento API Aspose.Slides per C++
description: Unisce un elemento matematico e forma un blocco matematico
type: docs
weight: 14
url: /it/aspose.slides.mathtext/imathelement/join/
---
## IMathElement::Join(System::SharedPtr\<IMathElement\>) metodo


Unisce un elemento matematico e forma un blocco matematico

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::SharedPtr<IMathElement> mathElement)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | L'elemento da unire |

### Valore restituito

Un nuovo [IMathBlock](../../imathblock/) contenente questa istanza e l'argomento specificato
## Osservazioni



Esempio: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## IMathElement::Join(System::String) metodo


Unisce un testo matematico e forma un blocco matematico

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathElement::Join(System::String mathText)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Testo matematico da unire |

### Valore restituito

Un nuovo [IMathBlock](../../imathblock/) contenente questa istanza e l'argomento specificato
## Osservazioni



Esempio: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)