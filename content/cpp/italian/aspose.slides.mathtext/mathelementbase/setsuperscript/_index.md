---
title: SetSuperscript()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea apice
type: docs
weight: 79
url: /it/aspose.slides.mathtext/mathelementbase/setsuperscript/
---
## MathElementBase::SetSuperscript(System::SharedPtr\<IMathElement\>) metodo


Crea apice

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::SharedPtr<IMathElement> superscript) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Apice (indice superiore a destra) |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Osservazioni



Esempio:
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## MathElementBase::SetSuperscript(System::String) metodo


Crea apice

```cpp
System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSuperscript(System::String superscript) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Apice (indice superiore a destra) |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Osservazioni



Esempio:
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)