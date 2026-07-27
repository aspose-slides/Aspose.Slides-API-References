---
title: SetSubSuperscriptOnTheRight()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea subíndice y superíndice a la derecha
type: docs
weight: 92
url: /es/aspose.slides.mathtext/mathelementbase/setsubsuperscriptontheright/
---
## MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método

Crea subíndice y superíndice a la derecha

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subíndice (índice inferior a la derecha) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Superíndice (índice superior a la derecha) |

### Valor devuelto

Nuevo elemento matemático del tipo [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)

## Observaciones

Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## MathElementBase::SetSubSuperscriptOnTheRight(System::String, System::String) método

Crea subíndice y superíndice a la derecha

```cpp
System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subíndice (índice inferior a la derecha) |
| superscript | [System::String](../../../system/string/) | Superíndice (índice superior a la derecha) |

### Valor devuelto

Nuevo elemento matemático del tipo [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)

## Observaciones

Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathElementBase](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)