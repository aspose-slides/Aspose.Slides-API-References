---
title: MathematicalText
second_title: Aspose.Slides لنظام Android عبر مرجع API لـ Java
description: نص رياضي
type: docs
url: /ar/com.aspose.slides/mathematicaltext/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathematicalText](../../com.aspose.slides/imathematicaltext)
```
public final class MathematicalText extends MathElementBase implements IMathematicalText
```

نص رياضي

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```
## المنشئون

| Constructor | Description |
| --- | --- |
| [MathematicalText()](#MathematicalText--) | المنشئ الافتراضي (إنشاء قيمة String.Empty) |
| [MathematicalText(char mathSymbol)](#MathematicalText-char-) | إنشاء MathText برمز واحد |
| [MathematicalText(String mathText)](#MathematicalText-java.lang.String-) | إنشاء MathematicalText من نص |
| [MathematicalText(String mathText, IPortionFormat portionFormat)](#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | إنشاء MathematicalText من نص وإعدادات التنسيق |
## الطرق

| Method | Description |
| --- | --- |
| [getValue()](#getValue--) | قيمة النص |
| [setValue(String value)](#setValue-java.lang.String-) | قيمة النص |
| [getFormat()](#getFormat--) | خصائص تنسيق النص |
| [getChildren()](#getChildren--) | جلب عناصر الأطفال |
### MathematicalText() {#MathematicalText--}
```
public MathematicalText()
```


المنشئ الافتراضي (إنشاء قيمة String.Empty)

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


إنشاء MathText برمز واحد

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText('$');
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathSymbol | char | رمز واحد |

### MathematicalText(String mathText) {#MathematicalText-java.lang.String-}
```
public MathematicalText(String mathText)
```


إنشاء MathematicalText من نص

--------------------

> ```
> Example:
>  
>  MathematicalText mathText = new MathematicalText("x+y");
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | قيمة النص |

### MathematicalText(String mathText, IPortionFormat portionFormat) {#MathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public MathematicalText(String mathText, IPortionFormat portionFormat)
```


إنشاء MathematicalText من نص وإعدادات التنسيق

--------------------

> ```
> Example:
>  
>  IPortionFormat format = new PortionFormat();
>  format.setFontHeight(12);
>  MathematicalText mathText = new MathematicalText("x+y", format);
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathText | java.lang.String | قيمة النص |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | إعدادات تنسيق النص |

### getValue() {#getValue--}
```
public final String getValue()
```


قيمة النص

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**القيمة المرجعة:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public final void setValue(String value)
```


قيمة النص

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public final IPortionFormat getFormat()
```


خصائص تنسيق النص

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**القيمة المرجعة:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


جلب عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]