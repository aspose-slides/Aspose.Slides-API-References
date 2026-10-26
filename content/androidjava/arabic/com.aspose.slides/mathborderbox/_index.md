---
title: MathBorderBox
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يرسم حدًا مستطيلاً أو حدًا آخر حول IMathElement.
type: docs
url: /ar/com.aspose.slides/mathborderbox/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

يرسم حدًا مستطيلاً أو حدًا آخر حول IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | ينشئ عنصر MathBorderBox بحد مستطيل |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | ينشئ عنصر MathBorderBox |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | الحجة الأساسية |
| [getHideTop()](#getHideTop--) | إخفاء الحافة العلوية (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة العلوية لصندوق الحد. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | إخفاء الحافة العلوية (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة العلوية لصندوق الحد. |
| [getHideBottom()](#getHideBottom--) | إخفاء الحافة السفلية (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة السفلية لصندوق الحد. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | إخفاء الحافة السفلية (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة السفلية لصندوق الحد. |
| [getHideLeft()](#getHideLeft--) | إخفاء الحافة اليسرى (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة اليسرى لصندوق الحد. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | إخفاء الحافة اليسرى (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة اليسرى لصندوق الحد. |
| [getHideRight()](#getHideRight--) | إخفاء الحافة اليمنى (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة اليمنى لصندوق الحد. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | إخفاء الحافة اليمنى (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة اليمنى لصندوق الحد. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | خط أفقي شطبي (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة لخط شطب أفقي. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | خط أفقي شطبي (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة لخط شطب أفقي. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | خط عمودي شطبي (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة لخط شطب عمودي. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | خط عمودي شطبي (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة لخط شطب عمودي. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | شطب من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى (الافتراضي هو false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | شطب من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى (الافتراضي هو false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | شطب من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى (الافتراضي هو false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | شطب من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى (الافتراضي هو false). |
| [getChildren()](#getChildren--) | الحصول على عناصر الأطفال |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خصائص الأحرف التحكمية |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```


ينشئ عنصر MathBorderBox بحد مستطيل

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبق عليه صندوق الحد. يمكن أن يكون null. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


ينشئ عنصر MathBorderBox

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبق عليه صندوق الحد |
| hideTop | boolean | إخفاء الحافة العلوية |
| hideBottom | boolean | إخفاء الحافة السفلية |
| hideLeft | boolean | إخفاء الحافة اليسرى |
| hideRight | boolean | إخفاء الحافة اليمنى |
| strikethroughHorizontal | boolean | شطب أفقي |
| strikethroughVertical | boolean | شطب عمودي |
| strikethroughBottomLeftToTopRight | boolean | شطب من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى |
| strikethroughTopLeftToBottomRight | boolean | شطب من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


الحجة الأساسية

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```


إخفاء الحافة العلوية (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة العلوية لصندوق الحد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**القيمة المرجعة:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```


إخفاء الحافة العلوية (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة العلوية لصندوق الحد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```


إخفاء الحافة السفلية (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة السفلية لصندوق الحد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**القيمة المرجعة:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```


إخفاء الحافة السفلية (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة السفلية لصندوق الحد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```


إخفاء الحافة اليسرى (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة اليسرى لصندوق الحد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**القيمة المرجعة:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```


إخفاء الحافة اليسرى (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة اليسرى لصندوق الحد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```


إخفاء الحافة اليمنى (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة اليمنى لصندوق الحد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**القيمة المرجعة:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```


إخفاء الحافة اليمنى (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة للحافة اليمنى لصندوق الحد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```


شطب أفقي (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة لخط شطب أفقي.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**القيمة المرجعة:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```


شطب أفقي (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة لخط شطب أفقي.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```


شطب عمودي (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة لخط شطب عمودي.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**القيمة المرجعة:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```


شطب عمودي (الافتراضي هو false) - يحدد الحالة المخفية أو المعروضة لخط شطب عمودي.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```


شطب من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى (الافتراضي هو false). يحدد الحالة المخفية أو المعروضة لخط شطب قطري من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى لصندوق الحد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**القيمة المرجعة:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```


شطب من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى (الافتراضي هو false). يحدد الحالة المخفية أو المعروضة لخط شطب قطري من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى لصندوق الحد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```


شطب من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى (الافتراضي هو false). يحدد الحالة المخفية أو المعروضة لخط شطب قطري من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى لصندوق الحد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**القيمة المرجعة:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```


شطب من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى (الافتراضي هو false). يحدد الحالة المخفية أو المعروضة لخط شطب قطري من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى لصندوق الحد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


الحصول على عناصر الأطفال

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


خصائص الأحرف التحكمية

**القيمة المرجعة:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps