---
title: MathematicalText
second_title: Riferimento API Java per Aspose.Slides per Android
description: Testo matematico
type: docs
url: /it/com.aspose.slides/mathematicaltext/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Testo matematico

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Costruttore predefinito (crea valore String.Empty) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Crea MathText con un singolo simbolo |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Crea MathematicalText dal testo |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Crea MathematicalText dal testo e dalle impostazioni di formato |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getValue()](#getValue--) | Valore del testo |
| [setValue(String value)](#setValue-java.lang.String-) | Valore del testo |
| [getFormat()](#getFormat--) | Proprietà di formattazione del testo |
| [getChildren()](#getChildren--) | Ottieni gli elementi figli |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```

Costruttore predefinito (crea valore String.Empty)

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

Crea MathText con un singolo simbolo

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathSymbol | char | simbolo singolo |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```

Crea MathematicalText dal testo

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | java.lang.String | valore del testo |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```

Crea MathematicalText dal testo e dalle impostazioni di formato

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathText | java.lang.String | valore del testo |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | impostazioni di formato del testo |

### getValue() {#getValue--}
```
public final String getValue()
```

Valore del testo

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
public final void setValue(String value)
```

Valore del testo

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
public final IPortionFormat getFormat()
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
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Ottieni gli elementi figli

**Restituisce:**
com.aspose.slides.IMathElement[]