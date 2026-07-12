---
title: MathBorderBoxFactory
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Permite crear un cuadro de borde matemático
type: docs
url: /es/com.aspose.slides/mathborderboxfactory/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Permite crear un cuadro de borde matemático

--------------------

Para compatibilidad con COM
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Crear un cuadro de borde matemático aplicándolo al elemento |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Crear un cuadro de borde matemático aplicándolo al elemento |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Crear un cuadro de borde matemático aplicándolo al elemento

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que aplicar el cuadro de borde |

**Devuelve:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nuevo elemento de cuadro de borde
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Crear un cuadro de borde matemático aplicándolo al elemento

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que aplicar el cuadro de borde |
| hideTop | boolean | Ocultar borde superior |
| hideBottom | boolean | Ocultar borde inferior |
| hideLeft | boolean | Ocultar borde izquierdo |
| hideRight | boolean | Ocultar borde derecho |
| strikethroughHorizontal | boolean | Tachar cuadro de borde horizontalmente |
| strikethroughVertical | boolean | Tachar cuadro de borde verticalmente |
| strikethroughBottomLeftToTopRight | boolean | Tachar cuadro de borde de abajo-izquierda a arriba-derecha |
| strikethroughTopLeftToBottomRight | boolean | Tachar cuadro de borde de arriba-izquierda a abajo-derecha |

**Devuelve:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - nuevo elemento de cuadro de borde