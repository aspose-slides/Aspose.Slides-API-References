---
title: MathBlockFactory
second_title: Referencia de API de Aspose.Slides para Java
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
| [createMathBlock()](#createMathBlock--) | Crear un bloque matemático |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Crear un bloque matemático y colocar el elemento en él |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Crear un bloque matemático y colocar los elementos en él |
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