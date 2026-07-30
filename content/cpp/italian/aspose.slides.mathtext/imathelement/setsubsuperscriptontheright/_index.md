---
title: SetSubSuperscriptOnTheRight()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea pedice e apice a destra
type: docs
weight: 105
url: /it/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) method


Crea pedice e apice a destra

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Pedice (indice inferiore a destra) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Apice (indice superiore a destra) |

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

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) method


Crea pedice e apice a destra

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
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
* Classe [IMathElement](../)
* Classe [String](../../../system/string/)
* Namespace [Aspose::Slides::MathText](../../)
* Libreria [Aspose.Slides](../../../)