---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math border box
type: docs
url: /es/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Permite crear un cuadro de borde matemático

--------------------

Para compatibilidad COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Crear un cuadro de borde matemático aplicándolo al elemento |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Crear un cuadro de borde matemático aplicándolo al elemento |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Crear un cuadro de borde matemático aplicándolo al elemento

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que se aplicará el cuadro de borde |

**Devuelve:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nuevo elemento de cuadro de borde
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Crear un cuadro de borde matemático aplicándolo al elemento

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que se aplicará el cuadro de borde |
| hideTop | boolean | Ocultar el borde superior |
| hideBottom | boolean | Ocultar el borde inferior |
| hideLeft | boolean | Ocultar el borde izquierdo |
| hideRight | boolean | Ocultar el borde derecho |
| strikethroughHorizontal | boolean | Tachado horizontal del cuadro de borde |
| strikethroughVertical | boolean | Tachado vertical del cuadro de borde |
| strikethroughBottomLeftToTopRight | boolean | Tachado del cuadro de borde de abajo-izquierda a arriba-derecha |
| strikethroughTopLeftToBottomRight | boolean | Tachado del cuadro de borde de arriba-izquierda a abajo-derecha |

**Devuelve:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nuevo elemento de cuadro de borde