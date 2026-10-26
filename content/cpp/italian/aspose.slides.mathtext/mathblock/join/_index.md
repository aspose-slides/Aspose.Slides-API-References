---
title: Join()
second_title: Riferimento API di Aspose.Slides per C++
description: Unisce un elemento matematico a questo blocco matematico
type: docs
weight: 183
url: /it/aspose.slides.mathtext/mathblock/join/
---
## MathBlock::Join(System::SharedPtr\<IMathElement\>) metodo


Unisce un elemento matematico a questo blocco matematico

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::SharedPtr<IMathElement> mathElement) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | L'elemento da unire |

### Valore di ritorno

L'istanza corrente di [IMathBlock](../../imathblock/)
## Osservazioni



Esempio: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
auto block = element1->Join(element2);
```

## MathBlock::Join(System::String) metodo


Unisce un testo matematico a questo blocco matematico

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::Join(System::String mathText) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | [System::String](../../../system/string/) | Testo matematico da unire |

### Valore di ritorno

Un nuovo [IMathBlock](../../imathblock/) contenente questa istanza e l'argomento specificato
## Osservazioni



Esempio: 
```cpp
System::SharedPtr<IMathElement> element = System::MakeObject<MathematicalText>(u"x");
auto block = element->Join(u"+y");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathElement](../../imathelement/)
* Class [MathBlock](../)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)