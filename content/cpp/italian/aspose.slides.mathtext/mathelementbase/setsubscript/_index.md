---
title: SetSubscript()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea pedice
type: docs
weight: 66
url: /it/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) metodo

Crea pedice

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Pedice (indice inferiore a destra) |

### Valore restituito

Nuovo elemento matematico di tipo [IMathSubscriptElement](../../imathsubscriptelement/)
## Osservazioni



Esempio: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) metodo

Crea pedice

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Pedice (indice inferiore a destra) |

### Valore restituito

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
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)