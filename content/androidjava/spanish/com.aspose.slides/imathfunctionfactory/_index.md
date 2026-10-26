---
title: IMathFunctionFactory
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Permite crear una función matemática
type: docs
url: /es/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Permite crear una función matemática

--------------------

Para compatibilidad COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea una función matemática |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Crea una función matemática |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Crea una función matemática

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usado como nombre de la función |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usado como argumento de la función |

**Devuelve:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nueva función matemática
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Crea una función matemática

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| funcName | java.lang.String | Nombre de la función |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usado como argumento de la función |

**Devuelve:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nueva función matemática