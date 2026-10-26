---
title: MathGroupingCharacter
second_title: مرجع API Aspose.Slides برای جاوا
description: نماد گروه‌بندی را بالای یا زیر یک عبارت مشخص می‌کند که معمولاً برای برجسته‌سازی رابطه بین عناصر استفاده می‌شود
type: docs
url: /fa/com.aspose.slides/mathgroupingcharacter/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

نماد گروه‌بندی را بالای یا پایین یک عبارت مشخص می‌کند که معمولاً برای برجسته‌سازی رابطه بین عناصر استفاده می‌شود

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | یک نمونه جدید از کلاس MathGroupingCharacter را با کاراکتر گروه‌بندی پیش‌فرض U+23DF (کروشهٔ پایین) مقداردهی اولیه می‌کند |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | یک نمونه جدید از کلاس MathGroupingCharacter را مقداردهی اولیه می‌کند |
## متدها

| متد | توضیح |
| --- | --- |
| [getBase()](#getBase--) | آرگومان پایه |
| [getCharacter()](#getCharacter--) | کاراکتر گروه‌بندی مقدار پیش‌فرض: U+23DF (کروشهٔ پایین) |
| [setCharacter(char value)](#setCharacter-char-) | کاراکتر گروه‌بندی مقدار پیش‌فرض: U+23DF (کروشهٔ پایین) |
| [getPosition()](#getPosition--) | موقعیت کاراکتر گروه‌بندی. |
| [setPosition(int value)](#setPosition-int-) | موقعیت کاراکتر گروه‌بندی. |
| [getVerticalJustification()](#getVerticalJustification--) | تراز عمودی کاراکتر گروه. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | تراز عمودی کاراکتر گروه. |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | ویژگی‌های کاراکتر کنترل |
### MathGroupingCharacter(IMMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


یک نمونه جدید از کلاس MathGroupingCharacter را با کاراکتر گروه‌بندی پیش‌فرض U+23DF (کروشهٔ پایین) مقداردهی اولیه می‌کند

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر پایه‌ای که نوار به آن اعمال می‌شود |

### MathGroupingCharacter(IMMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


یک نمونه جدید از کلاس MathGroupingCharacter را مقداردهی اولیه می‌کند

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | عنصر پایه‌ای که نوار به آن اعمال می‌شود |
| character | char | کاراکتر گروه‌بندی |
| position | int | موقعیت کاراکتر گروه‌بندی |
| verticalJustification | int | تراز عمودی کاراکتر گروه |

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

**بازدهی:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


کاراکتر گروه‌بندی مقدار پیش‌فرض: U+23DF (کروشهٔ پایین)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // پرانتز پایین
> ```

**بازدهی:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```


کاراکتر گروه‌بندی مقدار پیش‌فرض: U+23DF (کروشهٔ پایین)

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


موقعیت کاراکتر گروه‌بندی. پیش‌فرض: پایین

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**بازدهی:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


موقعیت کاراکتر گروه‌بندی. پیش‌فرض: پایین

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


تراز عمودی کاراکتر گروه. تراز شیء نسبت به خط پایه را مشخص می‌کند. برای مثال، وقتی کاراکتر گروه بالای شیء باشد، تراز عمودی بالای (Top) به این معناست که بالای شیء بر روی خط پایه قرار گیرد؛ وقتی تراز عمودی به پایین (Bottom) تنظیم شود، پایین شیء بر روی خط پایه قرار می‌گیرد. پیش‌فرض: پایین برای Position=Top، و بالا برای Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**بازدهی:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```


تراز عمودی کاراکتر گروه. تراز شیء نسبت به خط پایه را مشخص می‌کند. برای مثال، وقتی کاراکتر گروه بالای شیء باشد، تراز عمودی بالای (Top) به این معناست که بالای شیء بر روی خط پایه قرار گیرد؛ وقتی تراز عمودی به پایین (Bottom) تنظیم شود، پایین شیء بر روی خط پایه قرار می‌گیرد. پیش‌فرض: پایین برای Position=Top، و بالا برای Position=Bottom

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

**بازدهی:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


ویژگی‌های کاراکتر کنترل

**بازدهی:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps