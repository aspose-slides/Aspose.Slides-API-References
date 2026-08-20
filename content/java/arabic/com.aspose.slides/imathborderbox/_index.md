---
title: IMathBorderBox
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يرسم حدودًا مستطيلة أو حدودًا أخرى حول IMathElement.
type: docs
url: /ar/com.aspose.slides/imathborderbox/
---
**جميع الواجهات التي تم تنفيذها:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

يرسم حدودًا مستطيلة أو حدودًا أخرى حول IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getHideTop()](#getHideTop--) | Hide Top Edge (default is false) - specifies the hidden or shown state of the top edge of border box. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Hide Top Edge (default is false) - specifies the hidden or shown state of the top edge of border box. |
| [getHideBottom()](#getHideBottom--) | Hide Bottom Edge (default is false) - specifies the hidden or shown state of the bottom edge of border box. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Hide Bottom Edge (default is false) - specifies the hidden or shown state of the bottom edge of border box. |
| [getHideLeft()](#getHideLeft--) | Hide Left Edge (default is false) - specifies the hidden or shown state of the left edge of border box. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Hide Left Edge (default is false) - specifies the hidden or shown state of the left edge of border box. |
| [getHideRight()](#getHideRight--) | Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Hide Right Edge (default is false) - specifies the hidden or shown state of the right edge of border box. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Strikethrough Horizontal (default is false) - specifies the hidden or shown state of a strikethrough horizontal line. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Strikethrough Horizontal (default is false) - specifies the hidden or shown state of a strikethrough horizontal line. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Strikethrough Vertical (default is false) - specifies the hidden or shown state of a strikethrough vertical line. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Strikethrough Top-Left to Bottom-Right (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Strikethrough Top-Left to Bottom-Right (default is false). |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

المعامل الأساسي

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  IMathElement base = borderBox.getBase();
> ```

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

إخفاء الحافة العلوية (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة العليا لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**القيمة المرجعة:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

إخفاء الحافة العلوية (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة العليا لصندوق الحدود.

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

إخفاء الحافة السفلية (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة السفلية لصندوق الحدود.

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**القيمة المرجعة:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

إخفاء الحافة السفلية (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة السفلية لصندوق الحدود.

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

إخفاء الحافة اليسرى (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة اليسرى لصندوق الحدود.

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**القيمة المرجعة:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

إخفاء الحافة اليسرى (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة اليسرى لصندوق الحدود.

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

إخفاء الحافة اليمنى (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة اليمنى لصندوق الحدود.

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**القيمة المرجعة:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

إخفاء الحافة اليمنى (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة اليمنى لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

شطب أفقي (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة لخط الشطب الأفقي.

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**القيمة المرجعة:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

شطب أفقي (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة لخط الشطب الأفقي.

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

شطب عمودي (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة لخط الشطب العمودي.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**القيمة المرجعة:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

شطب عمودي (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة لخط الشطب العمودي.

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

شطب من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى (الافتراضي هو false). يحدد الحالة المخفية أو الظاهرة لخط شطب قطري من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى لصندوق الحدود.

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**القيمة المرجعة:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

شطب من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى (الافتراضي هو false). يحدد الحالة المخفية أو الظاهرة لخط شطب قطري من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى لصندوق الحدود.

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

شطب من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى (الافتراضي هو false). يحدد الحالة المخفية أو الظاهرة لخط شطب قطري من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى لصندوق الحدود.

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**القيمة المرجعة:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

شطب من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى (الافتراضي هو false). يحدد الحالة المخفية أو الظاهرة لخط شطب قطري من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى لصندوق الحدود.

--------------------

> ```
> مثال:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |