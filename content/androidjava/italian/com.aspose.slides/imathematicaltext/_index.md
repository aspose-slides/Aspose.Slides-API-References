---
title: IMathematicalText
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Testo matematico
type: docs
url: /it/com.aspose.slides/imathematicaltext/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Testo matematico

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValue()](#getValue--) | Valore di testo |
| [setValue(String value)](#setValue-java.lang.String-) | Valore di testo |
| [getFormat()](#getFormat--) | Proprietà di formattazione del testo |
### getValue() {#getValue--}
```
public abstract String getValue()
```

Valore di testo

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Restituisce:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public abstract void setValue(String value)
```

Valore di testo

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
```

Proprietà di formattazione del testo

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Restituisce:**
[IPortionFormat](../../com.aspose.slides/iportionformat)