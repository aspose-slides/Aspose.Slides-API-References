---
title: IMathArray
second_title: مرجع API Aspose.Slides برای Java
description: یک آرایه عمودی از معادلات یا هر شیء ریاضی را مشخص می‌کند
type: docs
url: /fa/com.aspose.slides/imatharray/
---
**تمام واسط‌های پیاده‌سازی شده:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

یک آرایه عمودی از معادلات یا هر شیء ریاضی را مشخص می‌کند

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [getArguments()](#getArguments--) | مجموعه آیتم‌های آرایه |
| [getBaseJustification()](#getBaseJustification--) | ترازبندی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالای یا مرکز یک شیء آرایه هم‌تراز شود. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | ترازبندی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالای یا مرکز یک شیء آرایه هم‌تراز شود. |
| [getMaximumDistribution()](#getMaximumDistribution--) | حداکثر توزیع. زمانی که مقدار true باشد، آرایه به حداکثر عرض عنصر حاوی (صفحه، ستون، سلول و غیره) تنظیم می‌شود. |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | حداکثر توزیع. زمانی که مقدار true باشد، آرایه به حداکثر عرض عنصر حاوی (صفحه، ستون، سلول و غیره) تنظیم می‌شود. |
| [getObjectDistribution()](#getObjectDistribution--) | توزیع شیء. زمانی که مقدار true باشد، محتویات آرایه به حداکثر عرض شیء آرایه تنظیم می‌شود. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | توزیع شیء. زمانی که مقدار true باشد، محتویات آرایه به حداکثر عرض شیء آرایه تنظیم می‌شود. |
| [getRowSpacingRule()](#getRowSpacingRule--) | نوع فاصله عمودی بین عناصر آرایه |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | نوع فاصله عمودی بین عناصر آرایه |
| [getRowSpacing()](#getRowSpacing--) | فاصله بین ردیف‌های آرایه. این مقدار تنها زمانی که RowSpacingRule برابر ۳ باشد استفاده می‌شود؛ در این حالت واحد اندازه‌گیری نقطه است یا در حالت Multiple واحد اندازه‌گیری نیم‌خط است. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | فاصله بین ردیف‌های آرایه. این مقدار تنها زمانی که RowSpacingRule برابر ۳ باشد استفاده می‌شود؛ در این حالت واحد اندازه‌گیری نقطه است یا در حالت Multiple واحد اندازه‌گیری نیم‌خط است. |
### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```


مجموعه آیتم‌های آرایه

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**باز می‌گردد:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```


ترازبندی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالای یا مرکز یک شیء آرایه هم‌تراز شود. مقدار پیش‌فرض: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**باز می‌گردد:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```


ترازبندی آرایه نسبت به متن اطراف را مشخص می‌کند. متن خارج از آرایه می‌تواند با پایین، بالای یا مرکز یک شیء آرایه هم‌تراز شود. مقدار پیش‌فرض: Center

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
public abstract boolean getMaximumDistribution()
```


حداکثر توزیع. زمانی که مقدار true باشد، آرایه به حداکثر عرض عنصر حاوی (صفحه، ستون، سلول و غیره) تنظیم می‌شود.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**باز می‌گردد:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```


حداکثر توزیع. زمانی که مقدار true باشد، آرایه به حداکثر عرض عنصر حاوی (صفحه، ستون، سلول و غیره) تنظیم می‌شود.

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
public abstract boolean getObjectDistribution()
```


توزیع شیء. زمانی که مقدار true باشد، محتویات آرایه به حداکثر عرض شیء آرایه تنظیم می‌شود.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**باز می‌گردد:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```


توزیع شیء. زمانی که مقدار true باشد، محتویات آرایه به حداکثر عرض شیء آرایه تنظیم می‌شود.

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
public abstract int getRowSpacingRule()
```


نوع فاصله عمودی بین عناصر آرایه

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**باز می‌گردد:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```


نوع فاصله عمودی بین عناصر آرایه

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
public abstract long getRowSpacing()
```


فاصله بین ردیف‌های آرایه. این مقدار تنها زمانی که RowSpacingRule برابر ۳ باشد استفاده می‌شود؛ در این حالت واحد اندازه‌گیری نقطه است یا در حالت Multiple واحد اندازه‌گیری نیم‌خط است. مقدار پیش‌فرض: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**باز می‌گردد:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```


فاصله بین ردیف‌های آرایه. این مقدار تنها زمانی که RowSpacingRule برابر ۳ باشد استفاده می‌شود؛ در این حالت واحد اندازه‌گیری نقطه است یا در حالت Multiple واحد اندازه‌گیری نیم‌خط است. مقدار پیش‌فرض: 0

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