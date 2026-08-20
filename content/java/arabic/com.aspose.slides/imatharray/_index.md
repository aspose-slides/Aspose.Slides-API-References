---
title: IMathArray
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يحدد مصفوفة رأسية من المعادلات أو أي كائنات رياضية
type: docs
url: /ar/com.aspose.slides/imatharray/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

يحدد مصفوفة رأسية من المعادلات أو أي كائنات رياضية

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## الطرق

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | مجموعة العناصر في المصفوفة |
| [getBaseJustification()](#getBaseJustification--) | يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو المركز بالنسبة لكائن المصفوفة. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو المركز بالنسبة لكائن المصفوفة. |
| [getMaximumDistribution()](#getMaximumDistribution--) | التوزيع الأقصى. عندما تكون true، يتم توزيع المصفوفة لتملأ أقصى عرض للعنصر الحاوي (صفحة، عمود، خلية، إلخ). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | التوزيع الأقصى. عندما تكون true، يتم توزيع المصفوفة لتملأ أقصى عرض للعنصر الحاوي (صفحة، عمود، خلية، إلخ). |
| [getObjectDistribution()](#getObjectDistribution--) | توزيع الكائن. عندما تكون true، يتم توزيع محتويات المصفوفة لتملأ أقصى عرض لكائن المصفوفة. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | توزيع الكائن. عندما تكون true، يتم توزيع محتويات المصفوفة لتملأ أقصى عرض لكائن المصفوفة. |
| [getRowSpacingRule()](#getRowSpacingRule--) | نوع التباعد العمودي بين عناصر المصفوفة |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | نوع التباعد العمودي بين عناصر المصفوفة |
| [getRowSpacing()](#getRowSpacing--) | التباعد بين صفوف المصفوفة. يُستخدم فقط عندما يكون RowSpacingRule مضبوطًا على 3؛ في هذه الحالة وحدة القياس هي النقاط أو Multiple حيث تكون وحدة القياس هي أنصاف السطور. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | التباعد بين صفوف المصفوفة. يُستخدم فقط عندما يكون RowSpacingRule مضبوطًا على 3؛ في هذه الحالة وحدة القياس هي النقاط أو Multiple حيث تكون وحدة القياس هي أنصاف السطور. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

مجموعة العناصر في المصفوفة

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**قيمة الإرجاع:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو المركز بالنسبة لكائن المصفوفة. القيمة الافتراضية: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**قيمة الإرجاع:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو المركز بالنسبة لكائن المصفوفة. القيمة الافتراضية: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

التوزيع الأقصى. عندما تكون true، يتم توزيع المصفوفة لتملأ أقصى عرض للعنصر الحاوي (صفحة، عمود، خلية، إلخ).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**قيمة الإرجاع:**
boolean

### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

التوزيع الأقصى. عندما تكون true، يتم توزيع المصفوفة لتملأ أقصى عرض للعنصر الحاوي (صفحة، عمود، خلية، إلخ).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

توزيع الكائن. عندما تكون true، يتم توزيع محتويات المصفوفة لتملأ أقصى عرض لكائن المصفوفة.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**قيمة الإرجاع:**
boolean

### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

توزيع الكائن. عندما تكون true، يتم توزيع محتويات المصفوفة لتملأ أقصى عرض لكائن المصفوفة.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

نوع التباعد العمودي بين عناصر المصفوفة

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**قيمة الإرجاع:**
int

### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

نوع التباعد العمودي بين عناصر المصفوفة

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

التباعد بين صفوف المصفوفة. يُستخدم فقط عندما يكون RowSpacingRule مضبوطًا على 3؛ في هذه الحالة وحدة القياس هي النقاط أو Multiple حيث تكون وحدة القياس هي أنصاف السطور. القيمة الافتراضية: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**قيمة الإرجاع:**
long

### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

التباعد بين صفوف المصفوة. يُستخدم فقط عندما يكون RowSpacingRule مضبوطًا على 3؛ في هذه الحالة وحدة القياس هي النقاط أو Multiple حيث تكون وحدة القياس هي أنصاف السطور. القيمة الافتراضية: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |