---
title: SetSubscript()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea subíndice
type: docs
weight: 79
url: /es/aspose.slides.mathtext/imathelement/setsubscript/
---
## IMathElement::SetSubscript(System::SharedPtr\<IMathElement\>) método

Crea subíndice

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::SharedPtr<IMathElement> subscript)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Subíndice (índice inferior a la derecha) |

### Valor devuelto

Nuevo elemento matemático del tipo [IMathSubscriptElement](../../imathsubscriptelement/)

## Observaciones

Ejemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## IMathElement::SetSubscript(System::String) método

Crea subíndice

```cpp
virtual System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::IMathElement::SetSubscript(System::String subscript)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subíndice (índice inferior a la derecha) |

### Valor devuelto

Nuevo elemento matemático del tipo [IMathSubscriptElement](../../imathsubscriptelement/)

## Observaciones

Ejemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathSubscriptElement](../../imathsubscriptelement/)
* Clase [IMathElement](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)