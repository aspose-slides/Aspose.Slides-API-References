---
title: MathArray
second_title: Aspose.Slides برای مرجع API جاوا
description: یک آرایهٔ عمودی از معادلات یا هر شیء ریاضی را مشخص می‌کند
type: docs
url: /fa/com.aspose.slides/matharray/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)  
```
public final class MathArray extends MathElementBase implements IMathArray
```

یک آرایهٔ عمودی از معادلات یا هر شیء ریاضی را مشخص می‌کند

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | یک آرایهٔ ریاضی ایجاد می‌کند و عنصر مشخص‌شده را در آن قرار می‌دهد |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | یک آرایهٔ ریاضی ایجاد می‌کند و عناصر مشخص‌شده را در آن قرار می‌دهد |
## متدها

| متد | توضیح |
| --- | --- |
| [getArguments()](#getArguments--) | مجموعهٔ آیتم‌های آرایه |
| [getBaseJustification()](#getBaseJustification--) | ترازبندی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌راستا شود. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | ترازبندی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌راستا شود. |
| [getMaximumDistribution()](#getMaximumDistribution--) | توزیع حداکثری. وقتی مقدار true باشد، آرایه به حداکثر عرض عنصر حاوی (صفحه، ستون، سلول و غیره) تنظیم می‌شود. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | توزیع حداکثری. وقتی مقدار true باشد، آرایه به حداکثر عرض عنصر حاوی (صفحه، ستون، سلول و غیره) تنظیم می‌شود. |
| [getObjectDistribution()](#getObjectDistribution--) | توزیع شیء. وقتی مقدار true باشد، محتویات آرایه به حداکثر عرض شیء آرایه تنظیم می‌شود. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | توزیع شیء. وقتی مقدار true باشد، محتویات آرایه به حداکثر عرض شیء آرایه تنظیم می‌شود. |
| [getRowSpacingRule()](#getRowSpacingRule--) | نوع فاصلهٔ عمودی بین عناصر آرایه. پیش‌فرض: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | نوع فاصلهٔ عمودی بین عناصر آرایه. پیش‌فرض: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | فاصلهٔ بین ردیف‌های آرایه. فقط زمانی استفاده می‌شود که RowSpacingRule برابر 3 باشد؛ در این حالت واحد اندازه‌گیری نقطه است یا در حالت Multiple نصف‌خط‌ها. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | فاصلهٔ بین ردیف‌های آرایه. فقط زمانی استفاده می‌شود که RowSpacingRule برابر 3 باشد؛ در این حالت واحد اندازه‌گیری نقطه است یا در حالت Multiple نصف‌خط‌ها. |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |

### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

یک آرایهٔ ریاضی ایجاد می‌کند و عنصر مشخص‌شده را در آن قرار می‌دهد

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که در آرایه قرار می‌گیرد |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

یک آرایهٔ ریاضی ایجاد می‌کند و عناصر مشخص‌شده را در آن قرار می‌دهد

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | عناصری که در آرایه قرار می‌گیرند |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

مجموعهٔ آیتم‌های آرایه

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**بازگشت:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)

### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

ترازبندی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌راستا شود. مقدار پیش‌فرض: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**بازگشت:**
int

### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

ترازبندی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌راستا شود. مقدار پیش‌فرض: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public final boolean getMaximumDistribution()
```

توزیع حداکثری. وقتی مقدار true باشد، آرایه به حداکثر عرض عنصر حاوی (صفحه، ستون، سلول و غیره) تنظیم می‌شود.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**بازگشت:**
boolean

### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

توزیع حداکثری. وقتی مقدار true باشد، آرایه به حداکثر عرض عنصر حاوی (صفحه، ستون، سلول و غیره) تنظیم می‌شود.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public final boolean getObjectDistribution()
```

توزیع شیء. وقتی مقدار true باشد، محتویات آرایه به حداکثر عرض شیء آرایه تنظیم می‌شود.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**بازگشت:**
boolean

### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

توزیع شیء. وقتی مقدار true باشد، محتویات آرایه به حداکثر عرض شیء آرایه تنظیم می‌شود.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public final int getRowSpacingRule()
```

نوع فاصلهٔ عمودی بین عناصر آرایه. پیش‌فرض: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**بازگشت:**
int

### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

نوع فاصلهٔ عمودی بین عناصر آرایه. پیش‌فرض: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public final long getRowSpacing()
```

فاصلهٔ بین ردیف‌های آرایه. فقط زمانی استفاده می‌شود که RowSpacingRule برابر 3 باشد؛ در این حالت واحد اندازه‌گیری نقطه است یا در حالت Multiple نصف‌خط‌ها. پیش‌فرض: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**بازگشت:**
long

### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

فاصلهٔ بین ردیف‌های آرایه. فقط زمانی استفاده می‌شود که RowSpacingRule برابر 3 باشد؛ در این حالت واحد اندازه‌گیری نقطه است یا در حالت Multiple نصف‌خط‌ها. پیش‌فرض: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

دریافت عناصر فرزند

**بازگشت:**
com.aspose.slides.IMathElement[]