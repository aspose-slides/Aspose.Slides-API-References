---
title: Join()
second_title: Aspose.Slides per C++ API Reference
description: Unisce un elemento matematico e forma un blocco matematico
type: docs
weight: 1
url: /it/aspose.slides.mathtext/mathelementbase/join/
---
## MathElementBase::Join(System::SharedPtr\<IMathElement\>) metodo


Unisce un elemento matematico e forma un blocco matematico

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'elemento da unire |

### Valore restituito

Un nuovo [IMathBlock](../../imathblock/) contenente questa istanza e l'argomento specificato
## Osservazioni



Esempio: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathElementBase::Join(System::String) metodo


Unisce un testo matematico e forma un blocco matematico

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathElementBase::Join(System::String mathText) override
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
auto element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBlock](../../imathblock/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)