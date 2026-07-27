---
title: Radical()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica la raíz matemática del grado dado a partir del argumento especificado.
type: docs
weight: 118
url: /es/aspose.slides.mathtext/mathelementbase/radical/
---
## MathElementBase::Radical(System::SharedPtr\<IMathElement\>) método

Especifica la raíz matemática del grado dado a partir del argumento especificado.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::SharedPtr<IMathElement> degree) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Argumento del radical |

### Valor de retorno

Nueva instancia del tipo [IMathRadical](../../imathradical/)

## Observaciones

Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## MathElementBase::Radical(System::String) método

Especifica la raíz matemática del grado dado a partir del argumento especificado.

```cpp
System::SharedPtr<IMathRadical> Aspose::Slides::MathText::MathElementBase::Radical(System::String degree) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argumento del radical |

### Valor de retorno

Nueva instancia del tipo [IMathRadical](../../imathradical/)

## Observaciones

Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathRadical](../../imathradical/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathElementBase](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)