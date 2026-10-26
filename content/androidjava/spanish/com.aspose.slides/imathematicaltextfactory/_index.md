---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a MathematicalText element
type: docs
url: /es/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

Permite crear un elemento MathematicalText

--------------------

Para compatibilidad COM
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Crear elemento MathematicalText vacío |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Crear elemento MathematicalText con el valor especificado |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Crear elemento MathematicalText vacío con el valor especificado |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Crear elemento MathematicalText vacío con el valor especificado y propiedades de formato |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```


Crear elemento MathematicalText vacío

**Devuelve:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nuevo Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```


Crear elemento MathematicalText con el valor especificado

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathSymbol | char | símbolo único para usar como valor de texto |

**Devuelve:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nuevo Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```


Crear elemento MathematicalText vacío con el valor especificado

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | java.lang.String | valor de texto |

**Devuelve:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nuevo Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Crear elemento MathematicalText vacío con el valor especificado y propiedades de formato

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | java.lang.String | valor de texto |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | configuraciones de formato de texto |

**Devuelve:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nuevo Mathematical Text