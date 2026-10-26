---
title: IMathematicalText
second_title: Java API Referansı aracılığıyla Aspose.Slides for Android
description: Matematiksel metin
type: docs
url: /tr/com.aspose.slides/imathematicaltext/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

Matematiksel metin

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getValue()](#getValue--) | Metin değeri |
| [setValue(String value)](#setValue-java.lang.String-) | Metin değeri |
| [getFormat()](#getFormat--) | Metin biçimlendirme özellikleri |
### getValue() {#getValue--}
```
public abstract String getValue()
```


Metin değeri

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
>  ```

**Döndürür:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public abstract void setValue(String value)
```


Metin değeri

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
>  ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
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