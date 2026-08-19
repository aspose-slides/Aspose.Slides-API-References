---
title: MathBlock
second_title: Aspose.Slides برای Java - مرجع API
description: یک نمونه از متن ریاضی را که در داخل یک MathParagraph قرار دارد و در خط خودش شروع می‌شود، مشخص می‌کند.
type: docs
url: /fa/com.aspose.slides/mathblock/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IMathBlock](../../com.aspose.slides/imathblock), com.aspose.slides.IDOMObject  
```
public final class MathBlock extends MathElementBase implements IMathBlock, IDOMObject
```

یک نمونه از متن ریاضی که درون یک MathParagraph قرار دارد و در خط خودش شروع می‌شود را مشخص می‌کند. تمام نواحی ریاضی، از جمله معادله‌ها، عبارات، آرایه‌های معادله یا عبارت، و فرمول‌ها توسط بلاک ریاضی نمایش داده می‌شوند.

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
| [MathBlock(IMathElement mathElement)](#MathBlock-com.aspose.slides.IMathElement-) | یک بلاک ریاضی جدید ایجاد می‌کند و عنصر مشخص‌شده را داخل آن قرار می‌دهد. |
| [MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)](#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | یک بلاک ریاضی جدید ایجاد می‌کند و عناصر مشخص‌شده را داخل آن قرار می‌دهد. |

## متدها

| متد | توضیح |
| --- | --- |
| [getCount()](#getCount--) | تعداد عناصر ریاضی فرزند واقعاً موجود در مجموعه را بر می‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | دریافت یا تعیین IMathElement در ایندکس مشخص‌شده. |
| [set_Item(int index, IMathElement value)](#set-Item-int-com.aspose.slides.IMathElement-) | دریافت یا تعیین IMathElement در ایندکس مشخص‌شده. |
| [isReadOnly()](#isReadOnly--) | مقدار false را برمی‌گرداند زیرا مجموعه عناصر فرزند قابل اصلاح است. |
| [getChildren()](#getChildren--) | دریافت عناصر فرزند |
| [getParent_Immediate()](#getParent-Immediate--) | شیء Parent_Immediate را برمی‌گرداند. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | یک عنصر ریاضی را به انتهای مجموعه اضافه می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | تعیین می‌کند آیا مجموعه شامل مقدار خاصی است یا خیر. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | به آرایه مشخص‌شده کپی می‌کند. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [iterator()](#iterator--) | یک enumerator که از طریق مجموعه تکرار می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | اندیس یک عنصر ریاضی خاص را در مجموعه تعیین می‌کند. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | یک MathElement را در ایندکس مشخص‌شده به مجموعه وارد می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر موجود در ایندکس مشخص‌شده از مجموعه را حذف می‌کند. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | یک عنصر ریاضی را به این بلاک ریاضی پیوست می‌کند. |
| [join(String mathText)](#join-java.lang.String-) | یک متن ریاضی را به این بلاک ریاضی پیوست می‌کند. |
| [joinBlock(IMathBlock other)](#joinBlock-com.aspose.slides.IMathBlock-) | یک بلاک ریاضی دیگر را به این بلاک پیوست می‌کند. |
| [delimit(char separatorCharacter)](#delimit-char-) | عناصر فرزند را با کاراکتر جداکننده (بدون براکت) محدود می‌کند. |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | عناصر فرزند این بلاک را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد. |
| [enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)](#enclose-char-char-char-) | عناصر فرزند این بلاک را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد و با کاراکتر جداکننده محدود می‌کند. |
| [toMathArray()](#toMathArray--) | عناصر فرزند را در یک آرایه عمودی قرار می‌دهد. |
| [writeAsMathMl(OutputStream stream)](#writeAsMathMl-java.io.OutputStream-) | محتوای این [MathBlock](../../com.aspose.slides/mathblock) را به‌صورت MathML ذخیره می‌کند. |

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

یک بلاک ریاضی جدید ایجاد می‌کند و عنصر مشخص‌شده را داخل آن قرار می‌دهد.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی برای قرار دادن در بلاک |

### MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements) {#MathBlock-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathBlock(System.Collections.Generic.IGenericEnumerable<IMathElement> mathElements)
```

یک بلاک ریاضی جدید ایجاد می‌کند و عناصر مشخص‌شده را داخل آن قرار می‌دهد.

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
| mathElements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | عناصر ریاضی برای قرار دادن در بلاک |

### getCount() {#getCount--}
```
public final int getCount()
```

تعداد عناصر ریاضی فرزند واقعاً موجود در مجموعه را بر می‌گرداند. int فقط-خواندنی.

--------------------

> ```
> Example:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  int count = mathBlock.getCount();
> ```

**برگشت:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMathElement get_Item(int index)
```

دریافت یا تعیین IMathElement در ایندکس مشخص‌شده.

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
| index | int | ایندکس مبتنی بر صفر آیتم |
**برگشت:**
[IMathElement](../../com.aspose.slides/imathelement) - عنصر ریاضی.

### set_Item(int index, IMathElement value) {#set-Item-int-com.aspose.slides.IMathElement-}
```
public final void set_Item(int index, IMathElement value)
```

دریافت یا تعیین IMathElement در ایندکس مشخص‌شده.

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
| index | int | ایندکس مبتنی بر صفر آیتم |
| value | [IMathElement](../../com.aspose.slides/imathelement) | عنصر ریاضی. |

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

مقدار false را برمی‌گرداند زیرا مجموعه عناصر فرزند قابل اصلاح است.

**برگشت:**
boolean
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

دریافت عناصر فرزند

**برگشت:**
com.aspose.slides.IMathElement[]
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. IDOMObject فقط-خواندنی.

**برگشت:**
com.aspose.slides.IDOMObject
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public final void add(IMathElement item)
```

یک عنصر ریاضی را به انتهای مجموعه اضافه می‌کند.

--------------------

> ```
> مثال:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  mathBlock.add(new MathematicalText("+"));
>  mathBlock.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement برای افزودن به انتهای مجموعه. |

### clear() {#clear--}
```
public final void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.

--------------------

> ```
> مثال:
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
> مثال:
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
| item | [IMathElement](../../com.aspose.slides/imathelement) | شیء برای جستجو در مجموعه. |

**برگشت:**
boolean - true اگر مورد در مجموعه پیدا شود؛ در غیر اینصورت false.
### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public final void copyTo(IMathElement[] array, int arrayIndex)
```

به آرایه مشخص‌شده کپی می‌کند.

--------------------

> ```
> مثال:
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
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | آرایه برای کپی. |
| arrayIndex | int | ایندکس شروع کپی. |

### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public final boolean remove(IMathElement item)
```

اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

--------------------

> ```
> مثال:
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
| item | [IMathElement](../../com.aspose.slides/imathelement) | شیء برای حذف از مجموعه. |

**برگشت:**
boolean - true اگر مورد با موفقیت حذف شود؛ در غیر اینصورت false. این متد همچنین false برمی‌گرداند اگر مورد در مجموعه اصلی پیدا نشود.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMathElement> iterator()
```

یک enumerator که از طریق مجموعه تکرار می‌کند را برمی‌گرداند.

**برگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMathElement> - یک IGenericEnumerator که می‌تواند برای تکرار در مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.IEnumerator iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**برگشت:**
com.aspose.ms.System.Collections.IEnumerator - یک java.util.Iterator برای کل مجموعه.
### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public final int indexOf(IMathElement item)
```

اندیس یک عنصر ریاضی خاص را در مجموعه تعیین می‌کند.

--------------------

> ```
> مثال:
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
| item | [IMathElement](../../com.aspose.slides/imathelement) | عنصر برای جستجو در مجموعه. |

**برگشت:**
int - اندیس مورد اگر در مجموعه پیدا شود؛ در غیر اینصورت -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public final void insert(int index, IMathElement item)
```

یک MathElement را در ایندکس مشخص‌شده به مجموعه وارد می‌کند.

--------------------

> ```
> مثال:
>  
>  MathBlock mathBlock = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  mathBlock.add(plusElement);
>  mathBlock.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس مبتنی بر صفر که MathElement باید در آن وارد شود. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | MathElement برای وارد کردن. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصر موجود در ایندکس مشخص‌شده از مجموعه را حذف می‌کند.

--------------------

> ```
> مثال:
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
| index | int | ایندکس مبتنی بر صفر عنصر برای حذف. |

### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

یک عنصر ریاضی را به این بلاک ریاضی پیوست می‌کند.

--------------------

> ```
> مثال:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | عنصر برای پیوستن. |

**برگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - نمونه فعلی IMathBlock
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

یک متن ریاضی را به این بلاک ریاضی پیوست می‌کند.

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
| mathText | java.lang.String | متن ریاضی برای پیوستن. |

**برگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - یک IMathBlock جدید که این نمونه و پارامتر مشخص‌شده را شامل می‌شود
### joinBlock(IMathBlock other) {#joinBlock-com.aspose.slides.IMathBlock-}
```
public final IMathBlock joinBlock(IMathBlock other)
```

یک بلاک ریاضی دیگر را به این بلاک پیوست می‌کند.

--------------------

> ```
> مثال:
>  
>  IMathBlock block1 = new MathSuperscriptElement(new MathematicalText("c"), new MathematicalText("2")).join(new MathematicalText("="));
>  IMathBlock block2 = new MathSuperscriptElement(new MathematicalText("a"), new MathematicalText("2")).join(new MathematicalText("+"))
>  .join(new MathSuperscriptElement(new MathematicalText("b"), new MathematicalText("2")));
>  IMathBlock block3 = block1.joinBlock(block2);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | [IMathBlock](../../com.aspose.slides/imathblock) | بلاک پیوست شونده. |

**برگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - این بلاک ریاضی پس از پیوستن
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

عناصر فرزند را با کاراکتر جداکننده (بدون براکت) محدود می‌کند.

--------------------

> ```
> مثال:
>  
>  MathBlock mathBlock = new MathematicalText("x").join("y");
>  IMathDelimiter delimiterElement = mathBlock.delimit('|');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| separatorCharacter | char | کاراکتر جداکننده |

**برگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter)

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

عناصر فرزند این بلاک را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد.

--------------------

> ```
> مثال:
>  
>  IMathBlock block = new MathematicalText("x").join("+y");
>  IMathDelimiter delimiter = block.enclose('[', ']');
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| beginningCharacter | char | کاراکتر ابتدایی (معمولاً براکت چپ) |
| endingCharacter | char | کاراکتر انتهایی (معمولاً براکت راست) |

**برگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) که شامل کاراکترهای مشخص‌شده به‌عنوان قاب است
### enclose(char beginningCharacter, char endingCharacter, char separatorCharacter) {#enclose-char-char-char-}
```
public final IMathDelimiter enclose(char beginningCharacter, char endingCharacter, char separatorCharacter)
```

عناصر فرزند این بلاک را در کاراکترهای مشخص‌شده مانند پرانتز یا کاراکترهای دیگر به‌عنوان قاب می‌گیرد و با کاراکتر جداکننده محدود می‌کند.

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
| beginningCharacter | char | کاراکتر ابتدایی (معمولاً براکت چپ) |
| endingCharacter | char | کاراکتر انتهایی (معمولاً براکت راست) |
| separatorCharacter | char | کاراکتر جداکننده |

**برگشت:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - عنصر ریاضی از نوع [IMathDelimiter](../../com.aspose.slides/imathdelimiter) که شامل کاراکترهای مشخص‌شده به‌عنوان قاب و جداکننده است
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

عناصر فرزند را در یک آرایه عمودی قرار می‌دهد.

--------------------

> ```
> مثال:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```

**برگشت:**
[IMathArray](../../com.aspose.slides/imatharray) - نمونه جدید از نوع [IMathArray](../../com.aspose.slides/imatharray)
### writeAsMathMl(OutputStream stream) {#writeAsMathMl-java.io.OutputStream-}
```
public final void writeAsMathMl(OutputStream stream)
```

محتوای این [MathBlock](../../com.aspose.slides/mathblock) را به‌صورت MathML ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |