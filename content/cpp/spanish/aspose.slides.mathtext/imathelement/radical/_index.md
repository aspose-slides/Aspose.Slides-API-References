---
title: Radical()
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica la raíz matemática del grado dado a partir del argumento especificado.
type: docs
weight: 131
url: /es/aspose.slides.mathtext/imathelement/radical/
---
## IMathElement::Radical(System::SharedPtr\<IMathElement\>) método

Especifica la raíz matemática del grado dado a partir del argumento especificado.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::SharedPtr<IMathElement> degree)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| degree | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../)\> | Argument of Radical |

### Valor de retorno

Nueva instancia del tipo [IMathRadical](../../imathradical/)

## Comentarios



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto degree = System::MakeObject<MathematicalText>(u"y");
auto radical = baseElement->Radical(degree);
```

## IMathElement::Radical(System::String) método

Especifica la raíz matemática del grado dado a partir del argumento especificado.

```cpp
virtual System::SharedPtr<IMathRadical> Aspose::Slides::MathText::IMathElement::Radical(System::String degree)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| degree | [System::String](../../../system/string/) | Argument of Radical |

### Valor de retorno

Nueva instancia del tipo [IMathRadical](../../imathradical/)

## Comentarios



Ejemplo: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"2px");
auto radical = baseElement->Radical(u"3");
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathRadical](../../imathradical/)
* Clase [IMathElement](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)