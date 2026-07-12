---
title: MathBlockFactory
second_title: Referencia de la API de Aspose.Slides para Android mediante Java
description: Permite crear un bloque matemático
type: docs
url: /es/com.aspose.slides/mathblockfactory/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

Permite crear un bloque matemático

--------------------

Para compatibilidad COM
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Create a math block |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Create a math block and place the element in it |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Create a math block and place elements in it |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


Crear un bloque matemático

**Devuelve:**
[IMathBlock](../../com.aspose.slides/imathblock) - nuevo bloque matemático
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


Crear un bloque matemático y colocar el elemento en él

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Un elemento matemático |

**Devuelve:**
[IMathBlock](../../com.aspose.slides/imathblock) - nuevo bloque matemático
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Crear un bloque matemático y colocar los elementos en él

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elementos matemáticos |

**Devuelve:**
[IMathBlock](../../com.aspose.slides/imathblock) - nuevo bloque matemático