---
title: IMathBlockCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: مجموعه‌ای از بلوک‌های ریاضی IMathBlock
type: docs
url: /fa/com.aspose.slides/imathblockcollection/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

مجموعه‌ای از بلوک‌های ریاضی (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```
## متدها

| Method | Description |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | IMathBlock را به انتهای مجموعه اضافه می‌کند. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | IMathBlock را در مجموعه در شاخص مشخص شده وارد می‌کند. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | یک مورد را در شاخص مشخص شده از مجموعه حذف می‌کند. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | تعیین می‌کند آیا مجموعه شامل مقدار خاصی است یا خیر. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | شاخص یک IMathBlock خاص در مجموعه را تعیین می‌کند. |
| [getCount()](#getCount--) | تعداد عناصر واقعاً موجود در مجموعه را دریافت می‌کند. |
| [get_Item(int index)](#get-Item-int-) | مورد را در شاخص مشخص شده دریافت می‌کند. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | مورد را در شاخص مشخص شده دریافت می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |

### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

IMathBlock را به انتهای مجموعه اضافه می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | یک بلوک ریاضی که به انتهای مجموعه اضافه خواهد شد |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

IMathBlock را در مجموعه در شاخص مشخص شده وارد می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنی که یک مورد باید در آن وارد شود. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock برای وارد کردن. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | شیئی که باید از مجموعه حذف شود. |

**بازگشت:**
boolean - true اگر مورد با موفقیت از مجموعه حذف شد؛ در غیر این صورت false. این متد همچنین false برمی‌گرداند اگر مورد در مجموعه اصلی یافت نشود.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

یک مورد را در شاخص مشخص شده از مجموعه حذف می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنی که یک مورد باید در آن حذف شود. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

تعیین می‌کند آیا مجموعه شامل مقدار خاصی است یا خیر.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | شیئی که باید در مجموعه پیدا شود. |

**بازگشت:**
boolean - true اگر مورد در مجموعه یافت شود؛ در غیر این صورت false.

### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

شاخص یک IMathBlock خاص در مجموعه را تعیین می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | موردی که باید در مجموعه پیدا شود. |

**بازگشت:**
int - شاخص مورد اگر در مجموعه یافت شود؛ در غیر این صورت -1.

### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد عناصری که واقعاً در مجموعه وجود دارد را دریافت می‌کند. فقط‌خواندنی int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**بازگشت:**
int

### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

مورد را در شاخص مشخص شده دریافت می‌کند. فقط‌خواندنی [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنی که یک مورد باید در آن دریافت شود. |

**بازگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - بلوک متن ریاضی.

### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

مورد را در شاخص مشخص شده دریافت می‌کند. فقط‌خواندنی [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنی که یک مورد باید در آن تنظیم شود. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | بلوک متن ریاضی.

### clear() {#clear--}
```
public abstract void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```