---
title: MathematicalText
second_title: Referencia de API de Aspose.Slides para Android vía Java
description: Texto matemático
type: docs
url: /es/com.aspose.slides/mathematicaltext/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas las interfaces implementadas:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Texto matemático

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Constructores

| Constructor | Descripción |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Constructor predeterminado (crea el valor String.Empty) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Crear MathText con un solo símbolo |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Crear MathematicalText a partir de texto |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Crear MathematicalText a partir de texto y configuraciones de formato |
## Métodos

| Método | Descripción |
| --- | --- |
| [getValue()](#getValue--) | Valor de texto |
| [setValue(String value)](#setValue-java.lang.String-) | Valor de texto |
| [getFormat()](#getFormat--) | Propiedades de formato de texto |
| [getChildren()](#getChildren--) | Obtener elementos hijos |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


Constructor predeterminado (crea el valor String.Empty)

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText();
> ```

### MathematicalText(char mathSymbol) {#MathematicalText-char-}
```
public MathematicalText(char mathSymbol)
```


Crear MathText con un solo símbolo

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathSymbol | char | símbolo único |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


Crear MathematicalText a partir de texto

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | java.lang.String | valor de texto |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


Crear MathematicalText a partir de texto y configuraciones de formato

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mathText | java.lang.String | valor de texto |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | configuraciones de formato de texto |

### getValue() {#getValue--}
```
public final String getValue()
```


Valor de texto

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Devuelve:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


Valor de texto

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


Propiedades de formato de texto

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Devuelve:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Obtener elementos hijos

**Devuelve:**
com.aspose.slides.IMathElement[]