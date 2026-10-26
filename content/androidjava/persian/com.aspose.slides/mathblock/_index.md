---
title: MathBlock
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک نمونه از متن ریاضی که در داخل یک MathParagraph قرار دارد و در خط خود شروع می‌شود را مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/mathblock/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

یک نمونه از متن ریاضی را که در داخل یک MathParagraph قرار دارد و در خط خود شروع می‌شود، مشخص می‌کند. تمام نواحی ریاضی، از جمله معادلات، عبارات، آرایه‌های معادلات یا عبارات و فرمول‌ها توسط بلاک ریاضی (math block) نمایان شده‌اند.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [MathBlock()](#MathBlock--) | یک نمونه جدید از کلاس MathBlock را مقداردهی اولیه می‌کند. |
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | یک بلاک ریاضی جدید ایجاد می‌کند و عنصر مشخص‌شده را در آن قرار می‌دهد |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | یک بلاک ریاضی جدید ایجاد می‌کند و عناصر مشخص‌شده را در آن قرار می‌دهد |
## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد عناصر ریاضی بچه‌ای که در واقع در مجموعه موجود هستند را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | دریافت یا تنظیم IMathElement در ایندکس مشخص‌شده. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | دریافت یا تنظیم IMathElement در ایندکس مشخص‌شده. |
| [isReadOnly()](#isReadOnly--) | به دلیل امکان تغییر مجموعه عناصر بچه‌ای، مقدار false را برمی‌گرداند. |
| [getChildren()](#getChildren--) | دریافت عناصر بچه‌ای |
| [getParent_Immediate()](#getParent-Immediate--) | شیء Parent_Immediate را برمی‌گرداند. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | یک عنصر ریاضی را به انتهای مجموعه اضافه می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | تعیین می‌کند آیا مجموعه شامل مقدار خاصی است یا خیر. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | کپی به آرایه مشخص‌شده. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارنده (enumerator) که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | ایندکس یک عنصر ریاضی خاص در مجموعه را تعیین می‌کند. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | یک MathElement را در ایندکس مشخص‌شده به مجموعه وارد می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر موجود در ایندکس مشخص‌شده در مجموعه را حذف می‌کند. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | یک عنصر ریاضی را با این بلاک ریاضی پیوند می‌دهد |
| [join(String mathText)](#join-java.lang.String-) | یک متن ریاضی را با این بلاک ریاضی پیوند می‌دهد |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | بلاک ریاضی دیگری را به این بلاک پیوند می‌دهد |
| [delimit(char separatorCharacter)](#delimit-char-) | عناصر بچه‌ای را با کاراکتر جداکننده (بدون براکت) جدا می‌کند |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | عناصر بچه‌ای این بلاک را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌صورت قاب‌بندی می‌کند |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | عناصر بچه‌ای این بلاک را در کاراکترهای مشخص‌شده مانند پرانتز یا دیگر کاراکترها به‌صورت قاب‌بندی می‌کند و با کاراکتر جداکننده جدا می‌سازد |
| [toMathArray()](#toMathArray--) | عناصر بچه‌ای را در یک آرایه عمودی قرار می‌دهد |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | محتویات این [MathBlock](../../com.aspose.slides/mathblock) را به صورت MathML ذخیره می‌کند |
### MathBlock() {#MathBlock--}
```
public MathBlock()
```


یک نمونه جدید از کلاس MathBlock را مقداردهی اولیه می‌کند.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock();
> ```

### MathBlock(IMathElement mathElement) {#MathBlock-com.aspose.slides.IMathElement-}
```
public MathBlock(IMathElement mathElement)
```


یک بلاک ریاضی جدید ایجاد می‌کند و عنصر مشخص‌شده را در آن قرار می‌دهد

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی که در بلاک قرار می‌گیرد |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```


یک بلاک ریاضی جدید ایجاد می‌کند و عناصر مشخص‌شده را در آن قرار می‌دهد

--------------------

> ```
> Example:
>  
>  var elems = new IMathElement[2] { new MathematicalText("item1"), new MathematicalText("item2") };
>  MathBlock mathBlock = new MathBlock(elems);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | عناصر ریاضی که در بلاک قرار می‌گیرند |

### getCount() {#getCount--}
```
public final int getCount()
```


تعداد عناصر ریاضی بچه‌ای که در واقع در مجموعه موجود هستند را برمی‌گرداند. عدد صحیح (int) فقط خواندنی.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**بازگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```


دریافت یا تنظیم IMathElement در ایندکس مشخص‌شده.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایهٔ مورد |

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement) - عنصر ریاضی.

### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```


دریافت یا تنظیم IMathElement در ایندکس مشخص‌شده.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = mathBlock.get_Item(0);
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایهٔ مورد |
| value | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


به دلیل امکان تغییر مجموعه عناصر بچه‌ای، مقدار false را برمی‌گرداند.

**بازگشت:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


دریافت عناصر بچه‌ای

**بازگشت:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


شیء Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```


یک عنصر ریاضی را به انتهای مجموعه اضافه می‌کند.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement که باید به انتهای مجموعه اضافه شود. |

### clear() {#clear--}
```
public final void clear()
```


تمام عناصر را از مجموعه حذف می‌کند.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public final boolean contains(IMathElement item)
```


تعیین می‌کند آیا مجموعه شامل مقدار خاصی است یا خیر.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  boolean contains = mathBlock.Contains(plusElement);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | شیء‌ای که باید در مجموعه جستجو شود. |

**بازگشت:**
boolean - در صورتی که آیتم در مجموعه یافت شود true؛ در غیر این صورت false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```


کپی به آرایه مشخص‌شده.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[mathBlock.Count];
>  mathBlock.copyTo(destinationArray, 0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | آرایه‌ای که به آن کپی می‌شود. |
| arrayIndex | int | ایندکسی که کپی از آن شروع می‌شود. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```


اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.Add(plusElement);
>  mathBlock.Add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.Remove(plusElement);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | شیء‌ای که باید از مجموعه حذف شود. |

**بازگشت:**
boolean - در صورتی که آیتم با موفقیت حذف شود true؛ در غیر این صورت false. این متد همچنین false برمی‌گرداند اگر آیتم در مجموعه اصلی یافت نشود.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```


یک شمارنده (enumerator) که از طریق مجموعه پیمایش می‌کند را برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```


یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.IEnumerator - یک java.util.Iterator برای کل مجموعه.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```


ایندکس یک عنصر ریاضی خاص در مجموعه را تعیین می‌کند.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = mathBlock.indexOf(plusElement);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که باید در مجموعه پیدا شود. |

**بازگشت:**
int - ایندکس آیتم اگر در مجموعه یافت شود؛ در غیر این صورت -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```


یک MathElement را در ایندکس مشخص‌شده به مجموعه وارد می‌کند.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایهٔ جایی که باید MathElement وارد شود. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | MathElement برای وارد کردن. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


عنصر موجود در ایندکس مشخص‌شده در مجموعه را حذف می‌کند.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  mathBlock.removeAt(2);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایهٔ عنصری که باید حذف شود. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```


یک عنصر ریاضی را با این بلاک ریاضی پیوند می‌دهد

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که باید پیوند داده شود |

**بازگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - نمونه فعلی IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```


یک متن ریاضی را با این بلاک ریاضی پیوند می‌دهد

--------------------

> ```
> مثال:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathText | java.lang.String | متن ریاضی که باید پیوند داده شود |

**بازگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - یک IMathBlock جدید که این نمونه و آرگومان مشخص‌شده را شامل می‌شود
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```


یک بلاک ریاضی دیگر را به این بلاک پیوند می‌دهد

--------------------

> ```
> Example:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | بلاک پیوندی |

**بازگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - این بلاک ریاضی پس از پیوند
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```


عناصر بچه‌ای را با کاراکتر جداکننده (بدون براکت) جدا می‌کند

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separatorCharacter | char | کاراکتر جداکننده |

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter)
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```


عناصر بچه‌ای این بلاک را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌صورت قاب‌بندی می‌کند

--------------------

> ```
> Example:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char | کاراکتر آغاز (معمولاً براکت چپ) |
| endingCharacter | char | کاراکتر پایان (معمولاً براکت راست) |

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) که کاراکترهای مشخص‌شده را به‌عنوان قاب شامل می‌شود
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```


عناصر بچه‌ای این بلاک را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌صورت قاب‌بندی می‌کند و با کاراکتر جداکننده جدا می‌سازد

--------------------

> ```
> مثال:
>  
>  IMathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.enclose('{', '}', '%');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char | کاراکتر آغاز (معمولاً براکت چپ) |
| endingCharacter | char | کاراکتر پایان (معمولاً براکت راست) |
| separatorCharacter | char | کاراکتر جداکننده |

**بازگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) که کاراکترهای مشخص‌شده را به‌عنوان قاب شامل می‌شود و جداکننده نیز دارد
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```


عناصر بچه‌ای را در یک آرایه عمودی قرار می‌دهد

--------------------

> ```
> مثال:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**بازگشت:**
[IMathArray](../../com.aspose.slides/imatharray) - نمونه جدیدی از نوع [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```


محتویات این [MathBlock](../../com.aspose.slides/mathblock) را به صورت MathML ذخیره می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |