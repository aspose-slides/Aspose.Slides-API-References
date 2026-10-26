---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: Permite crear un bloque matemático
type: docs
url: /es/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Permite crear un bloque matemático

--------------------

Para compatibilidad con COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Crear un bloque matemático |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Crear un bloque matemático y colocar el elemento en él |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Crear un bloque matemático y colocar los elementos en él |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```


Crear un bloque matemático

**Devuelve:**
[IMathBlock](../../com.aspose.slides/imathblock) - nuevo bloque matemático
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
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
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Crear un bloque matemático y colocar los elementos en él

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elementos matemáticos |

**Devuelve:**
[IMathBlock](../../com.aspose.slides/imathblock) - nuevo bloque matemático