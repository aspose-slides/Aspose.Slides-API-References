---
title: IMathArray
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک آرایهٔ عمودی از معادلات یا هر شیء ریاضی را مشخص می‌کند
type: docs
url: /fa/com.aspose.slides/imatharray/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

یک آرایهٔ عمودی از معادلات یا هر شیء ریاضی را مشخص می‌کند

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getArguments()](#getArguments--) | مجموعهٔ آیتم‌های آرایه |
| [getBaseJustification()](#getBaseJustification--) | هم‌ترازی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌تراز شود. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | هم‌ترازی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌تراز شود. |
| [getMaximumDistribution()](#getMaximumDistribution--) | توزیع حداکثری؛ وقتی مقدار true باشد، آرایه به عرض حداکثری عنصر حاوی (صفحه، ستون، سلول، و غیره) فاصله‌گذاری می‌شود. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | توزیع حداکثری؛ وقتی مقدار true باشد، آرایه به عرض حداکثری عنصر حاوی (صفحه، ستون، سلول، و غیره) فاصله‌گذاری می‌شود. |
| [getObjectDistribution()](#getObjectDistribution--) | توزیع شیء؛ وقتی مقدار true باشد، محتویات آرایه به عرض حداکثری شیء آرایه فاصله‌گذاری می‌شوند. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | توزیع شیء؛ وقتی مقدار true باشد، محتویات آرایه به عرض حداکثری شیء آرایه فاصله‌گذاری می‌شوند. |
| [getRowSpacingRule()](#getRowSpacingRule--) | نوع فاصلهٔ عمودی بین عناصر آرایه |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | نوع فاصلهٔ عمودی بین عناصر آرایه |
| [getRowSpacing()](#getRowSpacing--) | فاصله بین ردیف‌های آرایه. فقط زمانی استفاده می‌شود که RowSpacingRule برابر 3 باشد؛ در این صورت واحد اندازه‌گیری نقطه است یا اگر Multiple باشد، واحد نیم‌خط است. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | فاصله بین ردیف‌های آرایه. فقط زمانی استفاده می‌شود که RowSpacingRule برابر 3 باشد؛ در این صورت واحد اندازه‌گیری نقطه است یا اگر Multiple باشد، واحد نیم‌خط است. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

مجموعهٔ آیتم‌های آرایه

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Returns:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

هم‌ترازی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌تراز شود. مقدار پیش‌فرض: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Returns:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

هم‌ترازی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالا یا مرکز یک شیء آرایه هم‌تراز شود. مقدار پیش‌فرض: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

توزیع حداکثری؛ وقتی مقدار true باشد، آرایه به عرض حداکثری عنصر حاوی (صفحه، ستون، سلول، و غیره) فاصله‌گذاری می‌شود.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Returns:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

توزیع حداکثری؛ وقتی مقدار true باشد، آرایه به عرض حداکثری عنصر حاوی (صفحه، ستون، سلول، و غیره) فاصله‌گذاری می‌شود.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

توزیع شیء؛ وقتی مقدار true باشد، محتویات آرایه به عرض حداکثری شیء آرایه فاصله‌گذاری می‌شوند.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Returns:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

توزیع شیء؛ وقتی مقدار true باشد، محتویات آرایه به عرض حداکثری شیء آرایه فاصله‌گذاری می‌شوند.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

نوع فاصلهٔ عمودی بین عناصر آرایه

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Returns:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

نوع فاصلهٔ عمودی بین عناصر آرایه

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

فاصله بین ردیف‌های آرایه. فقط زمانی استفاده می‌شود که RowSpacingRule برابر 3 باشد؛ در این صورت واحد اندازه‌گیری نقطه است یا اگر Multiple باشد، واحد نیم‌خط است. مقدار پیش‌فرض: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Returns:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

فاصله بین ردیف‌های آرایه. فقط زمانی استفاده می‌شود که RowSpacingRule برابر 3 باشد؛ در این صورت واحد اندازه‌گیری نقطه است یا اگر Multiple باشد، واحد نیم‌خط است. مقدار پیش‌فرض: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |