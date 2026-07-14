---
title: MathGroupingCharacter
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: یک نماد گروه‌بندی را بالای یا پایین یک عبارت مشخص می‌کند که معمولاً برای برجسته‌سازی رابطه بین عناصر استفاده می‌شود
type: docs
url: /fa/com.aspose.slides/mathgroupingcharacter/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

نماد گروه‌بندی را بالای یا پایین یک عبارت مشخص می‌کند، معمولاً برای برجسته‌سازی رابطه بین عناصر

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس MathGroupingCharacter را با کاراکتر گروه‌بندی پیش‌فرض U+23DF (پران‌پشت‌کروشه) مقداردهی اولیه می‌کند |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | یک نمونه جدید از کلاس MathGroupingCharacter را مقداردهی اولیه می‌کند |
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getCharacter()](#getCharacter--) | کاراکتر گروه‌بندی مقدار پیش‌فرض: U+23DF (پران‌پشت‌کروشه) |
| [setCharacter(char value)](#setCharacter-char-) | کاراکتر گروه‌بندی مقدار پیش‌فرض: U+23DF (پران‌پشت‌کروشه) |
| [getPosition()](#getPosition--) | موقعیت کاراکتر گروه‌بندی |
| [setPosition(int value)](#setPosition-int-) | موقعیت کاراکتر گروه‌بندی |
| [getVerticalJustification()](#getVerticalJustification--) | تنظیم عمودی کاراکتر گروه |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | تنظیم عمودی کاراکتر گروه |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | خواص کاراکتر کنترل |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


یک نمونه جدید از کلاس MathGroupingCharacter را با کاراکتر گروه‌بندی پیش‌فرض U+23DF (پران‌پشت‌کروشه) مقداردهی اولیه می‌کند

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر پایه‌ای که میله به آن اعمال می‌شود |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


یک نمونه جدید از کلاس MathGroupingCharacter را مقداردهی اولیه می‌کند.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر پایه‌ای که میله به آن اعمال می‌شود |
| character | char | کاراکتر گروه‌بندی |
| position | int | موقعیت کاراکتر گروه‌بندی |
| verticalJustification | int | تنظیم عمودی کاراکتر گروه |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


آرگومان پایه

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**برمی‌گرداند:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


کاراکتر گروه‌بندی مقدار پیش‌فرض: U+23DF (پران‌پشت‌کروشه)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // پرانتز پایین
> ```

**برمی‌گرداند:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```


کاراکتر گروه‌بندی مقدار پیش‌فرض: U+23DF (پران‌پشت‌کروشه)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // پرانتز پایین
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


موقعیت کاراکتر گروه‌بندی. پیش‌فرض: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**برمی‌گرداند:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


موقعیت کاراکتر گروه‌بندی. پیش‌فرض: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```


تنظیم عمودی کاراکتر گروه. تعیین هم‌ترازی شیء نسبت به خط اصلی. به عنوان مثال، وقتی کاراکتر گروه بالای شیء باشد، تنظیم عمودی Top به این معناست که بالای شیء روی خط اصلی قرار می‌گیرد؛ وقتی تنظیم عمودی Bottom باشد، پایین شیء روی خط اصلی قرار می‌گیرد. پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**برمی‌گرداند:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```


تنظیم عمودی کاراکتر گروه. تعیین هم‌ترازی شیء نسبت به خط اصلی. به عنوان مثال، وقتی کاراکتر گروه بالای شیء باشد، تنظیم عمودی Top به این معناست که بالای شیء روی خط اصلی قرار می‌گیرد؛ وقتی تنظیم عمودی Bottom باشد، پایین شیء روی خط اصلی قرار می‌گیرد. پیش‌فرض: Bottom برای Position=Top و Top برای Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


دریافت عناصر فرزند

**برمی‌گرداند:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


خواص کاراکتر کنترل

**برمی‌گرداند:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps