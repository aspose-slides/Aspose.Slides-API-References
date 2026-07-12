---
title: MathematicalTextFactory
second_title: Aspose.Slides para Android mediante referencia de API Java
description: Permite crear un elemento MathematicalText
type: docs
url: /es/com.aspose.slides/mathematicaltextfactory/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

Permite crear un elemento MathematicalText

--------------------

Para compatibilidad COM
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Crear elemento de texto matemático vacío |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Crear elemento de texto matemático con el valor especificado |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Crear elemento de texto matemático vacío con el valor especificado |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Crear elemento de texto matemático vacío con el valor especificado y propiedades de formato |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```


### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```


Crear elemento de texto matemático vacío

**Devuelve:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nuevo Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```


Crear elemento de texto matemático con el valor especificado

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathSymbol | char | símbolo único a usar como valor de texto |

**Devuelve:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nuevo Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```


Crear elemento de texto matemático vacío con el valor especificado

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | java.lang.String | valor de texto |

**Devuelve:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nuevo Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


Crear elemento de texto matemático vacío con el valor especificado y propiedades de formato

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | java.lang.String | valor de texto |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | configuración de formato de texto |

**Devuelve:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - nuevo Mathematical Text