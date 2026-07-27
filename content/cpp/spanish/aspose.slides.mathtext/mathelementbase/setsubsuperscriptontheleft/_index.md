---
title: SetSubSuperscriptOnTheLeft()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea subíndice y superíndice a la izquierda
type: docs
weight: 105
url: /es/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheleft/
---
## MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método

Crea subíndice y superíndice a la izquierda

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subscript (lower index on the left) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superscript (upper index on the left) |

### Valor devuelto

New math element of type [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## Observaciones



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheLeft(System::String, System::String) método

Crea subíndice y superíndice a la izquierda

```cpp
System::SharedPtr<IMathLeftSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheLeft(System::String subscript, System::String superscript) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subscript (lower index on the left) |
| superscript | [System::String](../../../system/string/) | Superscript (upper index on the left) |

### Valor devuelto

New math element of type [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)

## Observaciones



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto leftSubsuperscript = baseElement->SetSubSuperscriptOnTheLeft(u"i", u"j");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathLeftSubSuperscriptElement](../../imathleftsubsuperscriptelement/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathElementBase](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)