---
title: IMathDelimiterFactory
second_title: Aspose.Slides for Java API Reference
description: Permite crear un delimitador matemático
type: docs
url: /es/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Permite crear un delimitador matemático

--------------------

Para compatibilidad COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Crea un delimitador matemático aplicándolo al elemento |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Crea un delimitador matemático aplicándolo al elemento |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

Crea un delimitador matemático aplicándolo al elemento

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático para aplicar el delimitador |

**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nuevo delimitador matemático
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

Crea un delimitador matemático aplicándolo al elemento

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elementos matemáticos para aplicar el delimitador |

**Devuelve:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nuevo delimitador matemático