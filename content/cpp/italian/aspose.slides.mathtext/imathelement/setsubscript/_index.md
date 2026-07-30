---
title: SetSubscript()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea pedice
type: docs
weight: 79
url: /it/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) metodo

Crea pedice

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Pedice (indice inferiore a destra) |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathSubscriptElement](../../imathsubscriptelement/)
## Osservazioni



Esempio: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) metodo

Crea pedice

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Pedice (indice inferiore a destra) |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathSubscriptElement](../../imathsubscriptelement/)
## Osservazioni



Esempio: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathSubscriptElement](../../imathsubscriptelement/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)