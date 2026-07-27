---
title: MathBorderBox()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un elemento MathBorderBox con borde rectangular
type: docs
weight: 222
url: /es/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) constructor


Crea [MathBorderBox](../) elemento con borde rectangular

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | El elemento base al que se aplica la caja de borde. Puede ser nulo. |
## Observaciones



Ejemplo: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) constructor


Crea [MathBorderBox](../) elemento

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | El elemento base al que se aplica la caja de borde |
| hideTop | **bool** | Ocultar borde superior |
| hideBottom | **bool** | Ocultar borde inferior |
| hideLeft | **bool** | Ocultar borde izquierdo |
| hideRight | **bool** | Ocultar borde derecho |
| strikethroughHorizontal | **bool** | Tachado horizontal |
| strikethroughVertical | **bool** | Tachado vertical |
| strikethroughBottomLeftToTopRight | **bool** | Tachado de abajo-izquierda a arriba-derecha |
| strikethroughTopLeftToBottomRight | **bool** | Tachado de arriba-izquierda a abajo-derecha |
## Observaciones



Ejemplo: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathBorderBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)