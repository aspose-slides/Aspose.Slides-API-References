---
title: MathArray
second_title: Aspose.Slides for Android عبر مرجع API لجافا
description: يحدد مصفوفة رأسية من المعادلات أو أي كائنات رياضية
type: docs
url: /ar/com.aspose.slides/matharray/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)  
```
public final class MathArray extends MathElementBase implements IMathArray
```

يحدد مصفوفة رأسية من المعادلات أو أي كائنات رياضية

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## المنشئون

| المنشىء | الوصف |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | ينشئ مصفوفة رياضية ويضع العنصر المحدد فيها |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | ينشئ مصفوفة رياضية ويضع العناصر المحددة فيها |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getArguments()](#getArguments--) | مجموعة عناصر المصفوفة |
| [getBaseJustification()](#getBaseJustification--) | يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى أسفل أو أعلى أو وسط كائن المصفوفة. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى أسفل أو أعلى أو وسط كائن المصفوفة. |
| [getMaximumDistribution()](#getMaximumDistribution--) | التوزيع الأقصى. عندما تكون true، يتم توزيع المصفوفة لتملأ العرض الأقصى للعنصر الحاوي (صفحة، عمود، خلية، إلخ). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | التوزيع الأقصى. عندما تكون true، يتم توزيع المصفوفة لتملأ العرض الأقصى للعنصر الحاوي (صفحة، عمود، خلية، إلخ). |
| [getObjectDistribution()](#getObjectDistribution--) | توزيع الكائن. عندما تكون true، يتم توزيع محتويات المصفوفة لتملأ العرض الأقصى لكائن المصفوفة. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | توزيع الكائن. عندما تكون true، يتم توزيع محتويات المصفوفة لتملأ العرض الأقصى لكائن المصفوفة. |
| [getRowSpacingRule()](#getRowSpacingRule--) | نوع التباعد العمودي بين عناصر المصفوفة. الافتراضية: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | نوع التباعد العمودي بين عناصر المصفوفة. الافتراضية: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | التباعد بين صفوف المصفوفة. يُستخدم فقط عندما تكون RowSpacingRule مضبوطة على 3. في هذه الحالة وحدة القياس هي النقاط أو Multiple حيث تكون وحدة القياس نصف أسطر. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | التباعد بين صفوف المصفوفة. يُستخدم فقط عندما تكون RowSpacingRule مضبوطة على 3. في هذه الحالة وحدة القياس هي النقاط أو Multiple حيث تكون وحدة القياس نصف أسطر. |
| [getChildren()](#getChildren--) | احصل على العناصر الفرعية |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

ينشئ مصفوفة رياضية ويضع العنصر المحدد فيها

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الذي سيُضع في المصفوفة |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

ينشئ مصفوفة رياضية ويضع العناصر المحددة فيها

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | العناصر التي تُوضع في المصفوفة |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
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
public final int getBaseJustification()
```

يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى أسفل أو أعلى أو وسط كائن المصفوفة. القيمة الافتراضية: Center

--------------------

> ```
> مثال:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**القيمة المرجعة:**  
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى أسفل أو أعلى أو وسط كائن المصفوفة. القيمة الافتراضية: Center

--------------------

> ```
> مثال:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

التوزيع الأقصى. عندما تكون true، يتم توزيع المصفوفة لتملأ العرض الأقصى للعنصر الحاوي (صفحة، عمود، خلية، إلخ).

--------------------

> ```
> مثال:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**القيمة المرجعة:**  
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

التوزيع الأقصى. عندما تكون true، يتم توزيع المصفوفة لتملأ العرض الأقصى للعنصر الحاوي (صفحة، عمود، خلية، إلخ).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

توزيع الكائن. عندما تكون true، يتم توزيع محتويات المصفوفة لتملأ العرض الأقصى لكائن المصفوفة.

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
public final void setObjectDistribution(boolean value)
```

توزيع الكائن. عندما تكون true، يتم توزيع محتويات المصفوفة لتملأ العرض الأقصى لكائن المصفوفة.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

نوع التباعد العمودي بين عناصر المصفوفة. الافتراضية: SingleLineGap

--------------------

> ```
> مثال:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**القيمة المرجعة:**  
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

نوع التباعد العمودي بين عناصر المصفوفة. الافتراضية: SingleLineGap

--------------------

> ```
> مثال:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

التباعد بين صفوف المصفوفة. يُستخدم فقط عندما تكون RowSpacingRule مضبوطة على 3. في هذه الحالة وحدة القياس هي النقاط أو Multiple حيث تكون وحدة القياس نصف أسطر. الافتراضية: 0

--------------------

> ```
> مثال:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**القيمة المرجعة:**  
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

التباعد بين صفوف المصفوفة. يُستخدم فقط عندما تكون RowSpacingRule مضبوطة على 3. في هذه الحالة وحدة القياس هي النقاط أو Multiple حيث تكون وحدة القياس نصف أسطر. الافتراضية: 0

--------------------

> ```
> مثال:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

احصل على العناصر الفرعية

**القيمة المرجعة:**  
com.aspose.slides.IMathElement[]