---
title: SetSubSuperscriptOnTheLeft()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea subíndice y superíndice a la izquierda
type: docs
weight: 118
url: /es/aspose.slides.mathtext/imathelement/setsubsuperscriptontheleft/
---
## IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método


Crea subíndice y superíndice a la izquierda

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subíndice (índice inferior a la izquierda) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superíndice (índice superior a la izquierda) |

### Valor de retorno

Nuevo elemento matemático de tipo [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Observaciones



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheLeft(System::String, System::String) método


Crea subíndice y superíndice a la izquierda

```cpp
virtual System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subíndice (índice inferior a la izquierda) |
| superscript | [System::String](../../../system/string/) | Superíndice (índice superior a la izquierda) |

### Valor de retorno

Nuevo elemento matemático de tipo [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
## Observaciones



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Clase [IMathElement](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)