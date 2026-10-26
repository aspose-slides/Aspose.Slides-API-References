---
title: MathRadical
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يحدد الدالة الجذرية التي تتكون من قاعدة ودرجة اختيارية.
type: docs
url: /ar/com.aspose.slides/mathradical/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

يحدد الدالة الجذرية، التي تتكون من قاعدة ودرجة اختيارية. مثال على كائن جذري هو \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | يقوم بإنشاء نسخة جديدة من فئة MathRadical. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معلمة القاعدة |
| [getDegree()](#getDegree--) | معلمة الدرجة |
| [getHideDegree()](#getHideDegree--) | Hide degree عندما تكون true، لا تُظهر الدرجة، كما في \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | Hide degree عندما تكون true، لا تُظهر الدرجة، كما في \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |
| [getChildren()](#getChildren--) | احصل على عناصر الأطفال |
### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```

يقوم بإنشاء نسخة جديدة من فئة MathRadical.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | القاعدة |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | الدرجة |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

معلمة القاعدة

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement baseElem = radical.getBase();
> ```

**القيمة المرجعة:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getDegree() {#getDegree--}
```
public final IMathElement getDegree()
```

معلمة الدرجة

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  IMathElement degreeElem = radical.getDegree();
> ```

**القيمة المرجعة:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getHideDegree() {#getHideDegree--}
```
public final boolean getHideDegree()
```

Hide degree عندما تكون true، لا تُظهر الدرجة، كما في \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**القيمة المرجعة:**  
boolean
### setHideDegree(boolean value) {#setHideDegree-boolean-}
```
public final void setHideDegree(boolean value)
```

Hide degree عندما تكون true، لا تُظهر الدرجة، كما في \\u221a\\ud835\\udc65

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
>  radical.setHideDegree(true);
> ```

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

خصائص حرف التحكم

**القيمة المرجعة:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

احصل على عناصر الأطفال

**القيمة المرجعة:**  
com.aspose.slides.IMathElement[]