---
title: MathRadical
second_title: Aspose.Slides لمرجع API للغة جافا
description: يحدد الدالة الجذرية المكوّنة من أساس ودرجة اختيارية.
type: docs
url: /ar/com.aspose.slides/mathradical/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathRadical](../../com.aspose.slides/imathradical), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathRadical extends MathElementBase implements IMathRadical, IHasControlCharacterProperties
```

يحدد الدالة الجذرية، المكونة من أساس، ودرجة اختيارية. مثال على كائن جذري هو \\u221a\\ud835\\udc65.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathRadical(IMathElement baseArgument, IMathElement degreeArgument)](#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | ينشئ مثيلاً جديداً من الفئة MathRadical. |

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل الأساس |
| [getDegree()](#getDegree--) | معامل الدرجة |
| [getHideDegree()](#getHideDegree--) | إخفاء الدرجة. عندما تكون true، لا تُظهر الدرجة، كما في \\u221a\\ud835\\udc65 |
| [setHideDegree(boolean value)](#setHideDegree-boolean-) | إخفاء الدرجة. عندما تكون true، لا تُظهر الدرجة، كما في \\u221a\\ud835\\udc65 |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص حرف التحكم |
| [getChildren()](#getChildren--) | جلب عناصر الأطفال |

### MathRadical(IMathElement baseArgument, IMathElement degreeArgument) {#MathRadical-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathRadical(IMathElement baseArgument, IMathElement degreeArgument)
```

ينشئ مثيلاً جديداً من الفئة MathRadical.

--------------------

> ```
> Example:
>  
>  MathRadical radical = new MathRadical(new MathematicalText("x"), new MathematicalText("3"));
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | الأساس |
| degreeArgument | [IMathElement](../../com.aspose.slides/imathelement) | الدرجة |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

معامل الأساس

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

معامل الدرجة

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

إخفاء الدرجة. عندما تكون true، لا تُظهر الدرجة، كما في \\u221a\\ud835\\udc65

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

إخفاء الدرجة. عندما تكون true، لا تُظهر الدرجة، كما في \\u221a\\ud835\\udc65

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

جلب عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]