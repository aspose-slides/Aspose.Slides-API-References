---
title: MathArray
second_title: Aspose.Slides – مرجع واجهة برمجة تطبيقات Java
description: يحدد مصفوفة رأسية من المعادلات أو أي كائنات رياضية
type: docs
url: /ar/com.aspose.slides/matharray/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**جميع الواجهات المنفذة:**  
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
## المنشئات

| Constructor | Description |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | تنشئ مصفوفة رياضية وتضع العنصر المحدد فيها |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | تنشئ مصفوفة رياضية وتضع العناصر المحددة فيها |
## الطرق

| Method | Description |
| --- | --- |
| [getArguments()](#getArguments--) | مجموعة عناصر المصفوفة |
| [getBaseJustification()](#getBaseJustification--) | يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو الوسط لكائن المصفوفة. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو الوسط لكائن المصفوفة. |
| [getMaximumDistribution()](#getMaximumDistribution--) | التوزيع الأقصى. عندما يكون true، يتم توزيع المصفوفة لتغطي العرض الأقصى للعنصر الحاوي (صفحة، عمود، خلية، إلخ). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | التوزيع الأقصى. عندما يكون true، يتم توزيع المصفوفة لتغطي العرض الأقصى للعنصر الحاوي (صفحة، عمود، خلية، إلخ). |
| [getObjectDistribution()](#getObjectDistribution--) | توزيع الكائن. عندما يكون true، يتم توزيع محتويات المصفوفة لتغطي العرض الأقصى لكائن المصفوفة. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | توزيع الكائن. عندما يكون true، يتم توزيع محتويات المصفوفة لتغطي العرض الأقصى لكائن المصفوفة. |
| [getRowSpacingRule()](#getRowSpacingRule--) | نوع التباعد الرأسي بين عناصر المصفوفة. القيمة الافتراضية: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | نوع التباعد الرأسي بين عناصر المصفوفة. القيمة الافتراضية: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | تباعد بين صفوف المصفوفة. يُستخدم فقط عندما تكون RowSpacingRule مساوية للـ 3 حيث تكون وحدة القياس نقاطًا أو متعددة حيث تكون وحدة القياس نصف سطر. القيمة الافتراضية: 0 |
| [setRowSpacing(long value)](#setRowSpacing-long-) | تباعد بين صفوف المصفوفة. يُستخدم فقط عندما تكون RowSpacingRule مساوية للـ 3 حيث تكون وحدة القياس نقاطًا أو متعددة حيث تكون وحدة القياس نصف سطر. القيمة الافتراضية: 0 |
| [getChildren()](#getChildren--) | الحصول على عناصر الأطفال |

### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

تنشئ مصفوفة رياضية وتضع العنصر المحدد فيها

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**المعاملات:**  
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الذي يُوضع في المصفوفة |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

تنشئ مصفوفة رياضية وتضع العناصر المحددة فيها

**المعاملات:**  
| Parameter | Type | Description |
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
>  IMMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**القيمة المرجعة:**  
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو الوسط لكائن المصفوفة. القيمة الافتراضية: Center

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
public final void setBaseJustification(int value)
```

يحدد محاذاة المصفوفة بالنسبة للنص المحيط. يمكن محاذاة النص خارج المصفوفة إلى الأسفل أو الأعلى أو الوسط لكائن المصفوفة. القيمة الافتراضية: Center

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
public final boolean getMaximumDistribution()
```

التوزيع الأقصى. عندما يكون true، يتم توزيع المصفوفة لتغطي العرض الأقصى للعنصر الحاوي (صفحة، عمود، خلية، إلخ).

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
public final void setMaximumDistribution(boolean value)
```

التوزيع الأقصى. عندما يكون true، يتم توزيع المصفوفة لتغطي العرض الأقصى للعنصر الحاوي (صفحة، عمود، خلية، إلخ).

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
public final boolean getObjectDistribution()
```

توزيع الكائن. عندما يكون true، يتم توزيع محتويات المصفوفة لتغطي العرض الأقصى لكائن المصفوفة.

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

توزيع الكائن. عندما يكون true، يتم توزيع محتويات المصفوفة لتغطي العرض الأقصى لكائن المصفوفة.

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
public final int getRowSpacingRule()
```

نوع التباعد الرأسي بين عناصر المصفوفة. القيمة الافتراضية: SingleLineGap

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
public final void setRowSpacingRule(int value)
```

نوع التباعد الرأسي بين عناصر المصفوفة. القيمة الافتراضية: SingleLineGap

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
public final long getRowSpacing()
```

تباعد بين صفوف المصفوفة. يُستخدم فقط عندما تكون RowSpacingRule مساوية للـ 3 حيث تكون وحدة القياس نقاطًا أو متعددة حيث تكون وحدة القياس نصف سطر. القيمة الافتراضية: 0

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
public final void setRowSpacing(long value)
```

تباعد بين صفوف المصفوفة. يُستخدم فقط عندما تكون RowSpacingRule مساوية للـ 3 حيث تكون وحدة القياس نقاطًا أو متعددة حيث تكون وحدة القياس نصف سطر. القيمة الافتراضية: 0

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

الحصول على عناصر الأطفال

**القيمة المرجعة:**  
com.aspose.slides.IMathElement[]