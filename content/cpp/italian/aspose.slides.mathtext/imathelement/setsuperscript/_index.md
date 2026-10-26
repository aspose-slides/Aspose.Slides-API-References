---
title: SetSuperscript()
second_title: Riferimento API Aspose.Slides per C++
description: Crea apice
type: docs
weight: 92
url: /it/aspose.slides.mathtext/imathelement/setsuperscript/
---
## IMathElement::SetSuperscript(System::SharedPtr\<IMathElement\>) metodo


Crea apice

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::SharedPtr<IMathElement> superscript)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Apice (indice superiore a destra) |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Note



Esempio: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"4");
auto superscript = element->SetSuperscript(index);
```

## IMathElement::SetSuperscript(System::String) metodo


Crea apice

```cpp
virtual System::SharedPtr<IMathSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSuperscript(System::String superscript)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| superscript | [System::String](../../../system/string/) | Apice (indice superiore a destra) |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathSuperscriptElement](../../imathsuperscriptelement/)
## Note



Esempio: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto superscript = element->SetSuperscript(u"4");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathSuperscriptElement](../../imathsuperscriptelement/)
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)