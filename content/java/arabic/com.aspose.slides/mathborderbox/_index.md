---
title: MathBorderBox
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يرسم حدًا مستطيلًا أو حدًا آخر حول IMathElement.
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

يرسم حدًا مستطيلًا أو حدًا آخر حول IMathElement.

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
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBase()](#getBase--) | معامل أساسي |
| [getHideTop()](#getHideTop--) | Hide Top Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة العليا لصندوق الحد. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Hide Top Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة العليا لصندوق الحد. |
| [getHideBottom()](#getHideBottom--) | Hide Bottom Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة السفلية لصندوق الحد. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Hide Bottom Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة السفلية لصندوق الحد. |
| [getHideLeft()](#getHideLeft--) | Hide Left Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة اليسرى لصندوق الحد. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Hide Left Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة اليسرى لصندوق الحد. |
| [getHideRight()](#getHideRight--) | Hide Right Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة اليمنى لصندوق الحد. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Hide Right Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة اليمنى لصندوق الحد. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Strikethrough Horizontal (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة لخط شطب أفقي. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Strikethrough Horizontal (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة لخط شطب أفقي. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Strikethrough Vertical (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة لخط شطب عمودي. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Strikethrough Vertical (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة لخط شطب عمودي. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Strikethrough Bottom-Left to Top-Right (default is false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Strikethrough Top-Left to Bottom-Right (default is false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Strikethrough Top-Left to Bottom-Right (default is false). |
| [getChildren()](#getChildren--) | جلب العناصر الفرعية |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
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

**المعاملات:**
| المعامل | النوع | الوصف |
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

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الأساسي الذي يُطبق عليه صندوق الحد |
| hideTop | boolean | Hide Top Edge |
| hideBottom | boolean | Hide Bottom Edge |
| hideLeft | boolean | Hide Left Edge |
| hideRight | boolean | Hide Right Edge |
| strikethroughHorizontal | boolean | Strikethrough Horizontal |
| strikethroughVertical | boolean | Strikethrough Vertical |
| strikethroughBottomLeftToTopRight | boolean | Strikethrough Bottom-Left to Top-Right |
| strikethroughTopLeftToBottomRight | boolean | Strikethrough Top-Left to Bottom-Right |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

معامل أساسي

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

Hide Top Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة العليا لصندوق الحد.

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

Hide Top Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة العليا لصندوق الحد.

--------------------

> ```
> مثال:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

Hide Bottom Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة السفلية لصندوق الحد.

--------------------

> ```
> مثال:
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

Hide Bottom Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة السفلية لصندوق الحد.

--------------------

> ```
> مثال:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

Hide Left Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة اليسرى لصندوق الحد.

--------------------

> ```
> مثال:
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

Hide Left Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة اليسرى لصندوق الحد.

--------------------

> ```
> مثال:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

Hide Right Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة اليمنى لصندوق الحد.

--------------------

> ```
> مثال:
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

Hide Right Edge (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة للحافة اليمنى لصندوق الحد.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

Strikethrough Horizontal (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة لخط شطب أفقي.

--------------------

> ```
> مثال:
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

Strikethrough Horizontal (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة لخط شطب أفقي.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

Strikethrough Vertical (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة لخط شطب عمودي.

--------------------

> ```
> مثال:
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

Strikethrough Vertical (default is false) - (الافتراضي هو false) - يحدد الحالة المخفية أو الظاهرة لخط شطب عمودي.

--------------------

> ```
> مثال:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

Strikethrough Bottom-Left to Top-Right (default is false). يحدد الحالة المخفية أو الظاهرة لخط شطب قطري من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى لصندوق الحد.

--------------------

> ```
> مثال:
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

Strikethrough Bottom-Left to Top-Right (default is false). يحدد الحالة المخفية أو الظاهرة لخط شطب قطري من الزاوية السفلية اليسرى إلى الزاوية العلوية اليمنى لصندوق الحد.

--------------------

> ```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

Strikethrough Top-Left to Bottom-Right (default is false). يحدد الحالة المخفية أو الظاهرة لخط شطب قطري من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى لصندوق الحد.

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

Strikethrough Top-Left to Bottom-Right (default is false). يحدد الحالة المخفية أو الظاهرة لخط شطب قطري من الزاوية العلوية اليسرى إلى الزاوية السفلية اليمنى لصندوق الحد.

--------------------

> ```
> مثال:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

جلب العناصر الفرعية

**القيمة المرجعة:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**القيمة المرجعة:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps