---
title: ToBorderBox()
second_title: Referencia de API de Aspose.Slides para C++
description: Coloca este elemento en una caja de borde
type: docs
weight: 248
url: /es/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() método


Coloca este elemento en una caja de borde

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```


### Valor devuelto

Caja de borde con este elemento colocado dentro
## Observaciones



Ejemplo: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) método


Coloca este elemento en una caja de borde

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| hideTop | **bool** | Ocultar borde superior |
| hideBottom | **bool** | Ocultar borde inferior |
| hideLeft | **bool** | Ocultar borde izquierdo |
| hideRight | **bool** | Ocultar borde derecho |
| strikethroughHorizontal | **bool** | Tacha horizontal de la caja de borde |
| strikethroughVertical | **bool** | Tacha vertical de la caja de borde |
| strikethroughBottomLeftToTopRight | **bool** | Tacha de la caja de borde de abajo-izquierda a arriba-derecha |
| strikethroughTopLeftToBottomRight | **bool** | Tacha de la caja de borde de arriba-izquierda a abajo-derecha |

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
* Clase [MathElementBase](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)