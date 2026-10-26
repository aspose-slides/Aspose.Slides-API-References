---
title: IMathematicalText
second_title: دليل Aspose.Slides لواجهة برمجة تطبيقات Java
description: نص رياضي
type: docs
url: /ar/com.aspose.slides/imathematicaltext/
---
**جميع الواجهات المنفذة:**
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

| طريقة | الوصف |
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

**القيمة المرجعة:**
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

**المعلمات:**
| المعلمة | النوع | الوصف |
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

**القيمة المرجعة:**
[IPortionFormat](../../com.aspose.slides/iportionformat)