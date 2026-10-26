---
title: IMathematicalText
second_title: Aspose.Slides para Android a través de la referencia de API Java
description: Texto matemático
type: docs
url: /es/com.aspose.slides/imathematicaltext/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Texto matemático

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## Métodos

| Método | Descripción |
| --- | --- |
| [getValue()](#getValue--) | Valor de texto |
| [setValue(String value)](#setValue-java.lang.String-) | Valor de texto |
| [getFormat()](#getFormat--) | Propiedades de formato de texto |
### getValue() {#getValue--}
```
public abstract String getValue()
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
public abstract void setValue(String value)
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
public abstract IPortionFormat getFormat()
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