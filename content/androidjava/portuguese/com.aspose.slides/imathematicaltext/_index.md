---
title: IMathematicalText
second_title: Aspose.Slides para Android via Referência da API Java
description: Texto matemático
type: docs
url: /pt/com.aspose.slides/imathematicaltext/
---
**Todas as Interfaces Implementadas:**
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

| Método | Descrição |
| --- | --- |
| [getValue()](#getValue--) | Valor de texto |
| [setValue(String value)](#setValue-java.lang.String-) | Valor de texto |
| [getFormat()](#getFormat--) | Propriedades de formatação de texto |
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

**Retorna:**
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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
```


Propriedades de formatação de texto

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Retorna:**
[IPortionFormat](../../com.aspose.slides/iportionformat)