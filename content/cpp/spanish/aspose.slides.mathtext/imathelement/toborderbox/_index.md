---
title: ToBorderBox()
second_title: Referencia de API de Aspose.Slides para C++
description: Coloca este elemento en una caja de borde
type: docs
weight: 261
url: /es/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() método

Coloca este elemento en una caja de borde

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```


### Valor devuelto

Caja de borde con este elemento colocado dentro
## Observaciones



Ejemplo: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) método


Coloca este elemento en una caja de borde

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| hideTop | **bool** | Ocultar borde superior |
| hideBottom | **bool** | Ocultar borde inferior |
| hideLeft | **bool** | Ocultar borde izquierdo |
| hideRight | **bool** | Ocultar borde derecho |
| strikethroughHorizontal | **bool** | Tachado horizontal de la caja de borde |
| strikethroughVertical | **bool** | Tachado vertical de la caja de borde |
| strikethroughBottomLeftToTopRight | **bool** | Tachado de la caja de borde de abajo-izquierda a arriba-derecha |
| strikethroughTopLeftToBottomRight | **bool** | Tachado de la caja de borde de arriba-izquierda a abajo-derecha |

### Valor devuelto

Caja de borde con este elemento colocado dentro
## Observaciones



Ejemplo: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathBorderBox](../../imathborderbox/)
* Clase [IMathElement](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)