---
title: SetSubSuperscriptOnTheRight()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea subíndice y superíndice a la derecha
type: docs
weight: 105
url: /es/aspose.slides.mathtext/imathelement/setsubsuperscriptontheright/
---
## IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) método


Crea subíndice y superíndice a la derecha

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::SharedPtr<IMathElement> subscript, System::SharedPtr<IMathElement> superscript)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subíndice (índice inferior a la derecha) |
| superscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Superíndice (índice superior a la derecha) |

### Valor de retorno

Nuevo elemento matemático de tipo [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Observaciones



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(subscript, superscript);
```

## IMathElement::SetSubSuperscriptOnTheRight(System::String, System::String) método


Crea subíndice y superíndice a la derecha

```cpp
virtual System::SharedPtr<IMathRightSubSuperscriptElement> Aspose::Slides::MathText::IMathElement::SetSubSuperscriptOnTheRight(System::String subscript, System::String superscript)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subíndice (índice inferior a la derecha) |
| superscript | [System::String](../../../system/string/) | Superíndice (índice superior a la derecha) |

### Valor de retorno

Nuevo elemento matemático de tipo [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
## Observaciones



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"N");
auto subsuperscript = baseElement->SetSubSuperscriptOnTheRight(u"i", u"j");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathRightSubSuperscriptElement](../../imathrightsubsuperscriptelement/)
* Clase [IMathElement](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)