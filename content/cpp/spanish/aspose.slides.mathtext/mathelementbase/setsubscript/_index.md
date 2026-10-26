---
title: SetSubscript()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea subíndice
type: docs
weight: 66
url: /es/aspose.slides.mathtext/mathelementbase/setsubscript/
---
## MathElementBase::SetSubscript(System::SharedPtr\<IMathElement\>) método

Crea subíndice

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::SharedPtr<IMathElement> subscript) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Subíndice (índice inferior a la derecha) |

### Valor de retorno

Nuevo elemento matemático de tipo [IMathSubscriptElement](../../imathsubscriptelement/)
## Observaciones



Ejemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto index = System::MakeObject<MathematicalText>(u"i");
auto subscript = element->SetSubscript(index);
```

## MathElementBase::SetSubscript(System::String) método

Crea subíndice

```cpp
System::SharedPtr<IMathSubscriptElement> Aspose::Slides::MathText::MathElementBase::SetSubscript(System::String subscript) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| subscript | [System::String](../../../system/string/) | Subíndice (índice inferior a la derecha) |

### Valor de retorno

Nuevo elemento matemático de tipo [IMathSubscriptElement](../../imathsubscriptelement/)
## Observaciones



Ejemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"N");
auto subscript = element->SetSubscript(u"i");
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathSubscriptElement](../../imathsubscriptelement/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathElementBase](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)