---
title: IMathBorderBox
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يرسم حدًا مستطيلًا أو حدًا آخر حول IMathElement.
type: docs
url: /ar/com.aspose.slides/imathborderbox/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBorderBox extends IMathElement
```

Draws a rectangular or some other border around the IMathElement.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | المعامل الأساسي |
| [getHideTop()](#getHideTop--) | إخفاء الحافة العلوية (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة العلوية لصندوق الحدود. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | إخفاء الحافة العلوية (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة العلوية لصندوق الحدود. |
| [getHideBottom()](#getHideBottom--) | إخفاء الحافة السفلية (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة السفلية لصندوق الحدود. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | إخفاء الحافة السفلية (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة السفلية لصندوق الحدود. |
| [getHideLeft()](#getHideLeft--) | إخفاء الحافة اليسرى (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة اليسرى لصندوق الحدود. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | إخفاء الحافة اليسرى (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة اليسرى لصندوق الحدود. |
| [getHideRight()](#getHideRight--) | إخفاء الحافة اليمنى (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة اليمنى لصندوق الحدود. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | إخفاء الحافة اليمنى (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة اليمنى لصندوق الحدود. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | خط أفقي شطب (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة لخط الشطب الأفقي. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | خط أفقي شطب (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة لخط الشطب الأفقي. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | خط عمودي شطب (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة لخط الشطب العمودي. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | خط عمودي شطب (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة لخط الشطب العمودي. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | شطب من أسفل اليسار إلى أعلى اليمين (القيمة الافتراضية هي false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | شطب من أسفل اليسار إلى أعلى اليمين (القيمة الافتراضية هي false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | شطب من أعلى اليسار إلى أسفل اليمين (القيمة الافتراضية هي false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | شطب من أعلى اليسار إلى أسفل اليمين (القيمة الافتراضية هي false). |

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

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public abstract boolean getHideTop()
```

إخفاء الحافة العلوية (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة العلوية لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**الإرجاع:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public abstract void setHideTop(boolean value)
```

إخفاء الحافة العلوية (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة العلوية لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideTop(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public abstract boolean getHideBottom()
```

إخفاء الحافة السفلية (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة السفلية لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**الإرجاع:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public abstract void setHideBottom(boolean value)
```

إخفاء الحافة السفلية (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة السفلية لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideBottom(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public abstract boolean getHideLeft()
```

إخفاء الحافة اليسرى (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة اليسرى لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**الإرجاع:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public abstract void setHideLeft(boolean value)
```

إخفاء الحافة اليسرى (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة اليسرى لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideLeft(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public abstract boolean getHideRight()
```

إخفاء الحافة اليمنى (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة اليمنى لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**الإرجاع:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public abstract void setHideRight(boolean value)
```

إخفاء الحافة اليمنى (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة للحافة اليمنى لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setHideRight(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public abstract boolean getStrikethroughHorizontal()
```

خط أفقي شطب (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة لخط الشطب الأفقي.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**الإرجاع:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public abstract void setStrikethroughHorizontal(boolean value)
```

خط أفقي شطب (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة لخط الشطب الأفقي.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughHorizontal(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public abstract boolean getStrikethroughVertical()
```

خط عمودي شطب (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة لخط الشطب العمودي.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**الإرجاع:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public abstract void setStrikethroughVertical(boolean value)
```

خط عمودي شطب (القيمة الافتراضية هي false) - يحدد الحالة المخفية أو الظاهرة لخط الشطب العمودي.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughVertical(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public abstract boolean getStrikethroughBottomLeftToTopRight()
```

شطب من أسفل اليسار إلى أعلى اليمين (القيمة الافتراضية هي false). يحدد الحالة المخفية أو الظاهرة لخط الشطب القطري من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**الإرجاع:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public abstract void setStrikethroughBottomLeftToTopRight(boolean value)
```

شطب من أسفل اليسار إلى أعلى اليمين (القيمة الافتراضية هي false). يحدد الحالة المخفية أو الظاهرة لخط الشطب القطري من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public abstract boolean getStrikethroughTopLeftToBottomRight()
```

شطب من أعلى اليسار إلى أسفل اليمين (القيمة الافتراضية هي false). يحدد الحالة المخفية أو الظاهرة لخط الشطب القطري من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**الإرجاع:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public abstract void setStrikethroughTopLeftToBottomRight(boolean value)
```

شطب من أعلى اليسار إلى أسفل اليمين (القيمة الافتراضية هي false). يحدد الحالة المخفية أو الظاهرة لخط الشطب القطري من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى لصندوق الحدود.

--------------------

> ```
> Example:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |