---
title: IMathematicalText
second_title: Aspose.Slides لـ Android عبر مرجع API Java
description: نص رياضي
type: docs
url: /ar/com.aspose.slides/imathematicaltext/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathematicalText extends IMathElement
```

نص رياضي

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getValue()](#getValue--) | قيمة النص |
| [setValue(String value)](#setValue-java.lang.String-) | قيمة النص |
| [getFormat()](#getFormat--) | خصائص تنسيق النص |
### getValue() {#getValue--}
```
public abstract String getValue()
```

قيمة النص

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**الإرجاع:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public abstract void setValue(String value)
```

قيمة النص

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  String textValue = mathText.getValue();
> ```

**المُعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormat() {#getFormat--}
```
public abstract IPortionFormat getFormat()
```

خصائص تنسيق النص

--------------------

> ```
> Example:
>  
>  IMathematicalText mathText = new MathematicalText("x+y");
>  mathText.getFormat().setFontHeight(28);
> ```

**الإرجاع:**
[IPortionFormat](../../com.aspose.slides/iportionformat)