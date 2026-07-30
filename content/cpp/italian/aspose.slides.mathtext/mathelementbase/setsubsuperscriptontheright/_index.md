---
title: SetSubSuperscriptOnTheRight()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea pedice e apice a destra
type: docs
weight: 92
url: /it/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) metodo


Crea pedice e apice a destra

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Pedice (indice inferiore a destra) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Apice (indice superiore a destra) |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Osservazioni



Esempio: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) metodo


Crea pedice e apice a destra

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Pedice (indice inferiore a destra) |
| superscript | [System::String](../../../system/string/) | Apice (indice superiore a destra) |

### Valore di ritorno

Nuovo elemento matematico di tipo [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Osservazioni



Esempio: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathElementBase](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)