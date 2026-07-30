---
title: SetSubSuperscriptOnTheLeft()
second_title: Aspose.Slides per C++ - Riferimento API
description: Crea pedice e apice a sinistra
type: docs
weight: 105
url: /it/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metodo


Crea pedice e apice a sinistra

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Pedice (indice inferiore a sinistra) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Apice (indice superiore a sinistra) |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Osservazioni



Esempio: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) metodo


Crea pedice e apice a sinistra

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Pedice (indice inferiore a sinistra) |
| superscript | [System::String](../../../system/string/) | Apice (indice superiore a sinistra) |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Osservazioni



Esempio: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)