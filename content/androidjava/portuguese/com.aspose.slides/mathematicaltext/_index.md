---
title: MathematicalText
second_title: Referência da API Java via Aspose.Slides para Android
description: Texto matemático
type: docs
url: /pt/com.aspose.slides/mathematicaltext/
---
**Herança:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Texto Matemático

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

## Construtores

| Construtor | Descrição |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Construtor padrão (cria String.Empty Valor) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Cria MathText com símbolo único |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Cria MathematicalText a partir do texto |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Cria MathematicalText a partir do texto e configurações de formato |
## Métodos

| Método | Descrição |
| --- | --- |
| [getValue()](#getValue--) | Valor de texto |
| [setValue(String value)](#setValue-java.lang.String-) | Valor de texto |
| [getFormat()](#getFormat--) | Propriedades de formatação de texto |
| [getChildren()](#getChildren--) | Obter elementos filhos |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```

Construtor padrão (cria String.Empty Valor)

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

Cria MathText com símbolo único

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathSymbol | char | símbolo único |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```

Cria MathematicalText a partir do texto

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```


**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | java.lang.String | valor de texto |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```

Cria MathematicalText a partir do texto e configurações de formato

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| mathText | java.lang.String | valor de texto |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | configurações de formato de texto |

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

**Retorno:**
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

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```

Propriedades de formatação de texto

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Retorno:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Obter elementos filhos

**Retorno:**
com.aspose.slides.IMathElement[]