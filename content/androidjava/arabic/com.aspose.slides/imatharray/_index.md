---
title: IMathArray
second_title: Aspose.Slides لنظام Android عبر دليل API لجافا
description: يحدد مصفوفة رأسية من المعادلات أو أي كائنات رياضية
type: docs
url: /ar/com.aspose.slides/imatharray/
---
**كل الواجهات المنفذة:**
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

| الطريقة | الوصف |
| --- | --- |
| [getArguments()](#getArguments--) | مجموعة عناصر المصفوفة |
| [getBaseJustification()](#getBaseJustification--) | يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو الوسط بالنسبة لكائن المصفوفة. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو الوسط بالنسبة لكائن المصفوفة. |
| [getMaximumDistribution()](#getMaximumDistribution--) | التوزيع الأقصى. عندما تكون true، يتم توزيع المصفوفة لتتناسب مع أقصى عرض للعنصر المحتوي (صفحة، عمود، خلية، إلخ). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | التوزيع الأقصى. عندما تكون true، يتم توزيع المصفوفة لتتناسب مع أقصى عرض للعنصر المحتوي (صفحة، عمود، خلية، إلخ). |
| [getObjectDistribution()](#getObjectDistribution--) | توزيع الكائن. عندما تكون true، يتم توزيع محتويات المصفوفة لتتناسب مع أقصى عرض لكائن المصفوفة. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | توزيع الكائن. عندما تكون true، يتم توزيع محتويات المصفوفة لتتناسب مع أقصى عرض لكائن المصفوفة. |
| [getRowSpacingRule()](#getRowSpacingRule--) | نوع التباعد العمودي بين عناصر المصفوفة |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | نوع التباعد العمودي بين عناصر المصفوفة |
| [getRowSpacing()](#getRowSpacing--) | التباعد بين صفوف المصفوفة. يُستخدم فقط عندما يكون RowSpacingRule مضبوطًا على 3. Exactly حيث وحدة القياس هي النقاط أو Multiple حيث وحدة القياس هي نصف السطور. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | التباعد بين صفوف المصفوفة. يُستخدم فقط عندما يكون RowSpacingRule مضبوطًا على 3. Exactly حيث وحدة القياس هي النقاط أو Multiple حيث وحدة القياس هي نصف السطور. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

مجموعة عناصر المصفوفة

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**القيمة المرجعة:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)

### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو الوسط بالنسبة لكائن المصفوفة. القيمة الافتراضية: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**القيمة المرجعة:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو الوسط بالنسبة لكائن المصفوفة. القيمة الافتراضية: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

التوزيع الأقصى. عندما تكون true، يتم توزيع المصفوفة لتتناسب مع أقصى عرض للعنصر المحتوي (صفحة، عمود، خلية، إلخ).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**القيمة المرجعة:**
boolean

### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

التوزيع الأقصى. عندما تكون true، يتم توزيع المصفوفة لتتناسب مع أقصى عرض للعنصر المحتوي (صفحة، عمود، خلية، إلخ).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

توزيع الكائن. عندما تكون true، يتم توزيع محتويات المصفوفة لتتناسب مع أقصى عرض لكائن المصفوفة.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**القيمة المرجعة:**
boolean

### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

توزيع الكائن. عندما تكون true، يتم توزيع محتويات المصفوفة لتتناسب مع أقصى عرض لكائن المصفوفة.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
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

**القيمة المرجعة:**
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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

التباعد بين صفوف المصفوفة. يُستخدم فقط عندما يكون RowSpacingRule مضبوطًا على 3. Exactly حيث وحدة القياس هي النقاط أو Multiple حيث وحدة القياس هي نصف السطور. القيمة الافتراضية: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**القيمة المرجعة:**
long

### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

التباعد بين صفوف المصفوفة. يُستخدم فقط عندما يكون RowSpacingRule مضبوطًا على 3. Exactly حيث وحدة القياس هي النقاط أو Multiple حيث وحدة القياس هي نصف السطور. القيمة الافتراضية: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | long |  |