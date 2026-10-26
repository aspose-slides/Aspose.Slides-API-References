---
title: MathematicalText
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Matematiksel metin
type: docs
url: /tr/com.aspose.slides/mathematicaltext/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

Matematiksel metin

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | Varsayılan yapıcı (String.Empty değeri oluşturur) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | Tek sembolle MathText oluştur |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | Metinden MathematicalText oluştur |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Metinden ve biçim ayarlarından MathematicalText oluştur |
## Yöntemler

| Metot | Açıklama |
| --- | --- |
| [getValue()](#getValue--) | Metin değeri |
| [setValue(String value)](#setValue-java.lang.String-) | Metin değeri |
| [getFormat()](#getFormat--) | Metin biçimlendirme özellikleri |
| [getChildren()](#getChildren--) | Alt öğeleri al |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```

Varsayılan yapıcı (String.Empty değeri oluşturur)

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

Tek sembolle MathText oluştur

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathSymbol | char | tek sembol |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```

Metinden MathematicalText oluştur

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | java.lang.String | metin değeri |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```

Metinden ve biçim ayarlarından MathematicalText oluştur

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathText | java.lang.String | metin değeri |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | metin biçim ayarları |

### getValue() {#getValue--}
```
public final String getValue()
```

Metin değeri

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Döndürür:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```

Metin değeri

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```

Metin biçimlendirme özellikleri

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**Döndürür:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Alt öğeleri al

**Döndürür:**
com.aspose.slides.IMathElement[]