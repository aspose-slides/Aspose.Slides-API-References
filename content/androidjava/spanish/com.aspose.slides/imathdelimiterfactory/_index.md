---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math delimiter
type: docs
url: /es/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Permite crear un delimitador matemático

--------------------

Para compatibilidad con COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Create a math delimiter by applying to the element |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Create a math delimiter by applying to the element |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```


Crear un delimitador matemático aplicándolo al elemento

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático al que aplicar delimitador |

**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nuevo delimitador matemático
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```


Crear un delimitador matemático aplicándolo al elemento

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elementos matemáticos a los que aplicar delimitador |

**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nuevo delimitador matemático