---
title: IMathBlockCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: مجموعه‌ای از بلوک‌های ریاضی IMathBlock
type: docs
url: /fa/com.aspose.slides/imathblockcollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
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

| متد | توضیح |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | IMMathBlock را به انتهای مجموعه اضافه می‌کند. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | IMMathBlock را در موقعیت مشخص شده در مجموعه وارد می‌کند. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | موردی را در اندیس مشخص شده در مجموعه حذف می‌کند. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | تعیین می‌کند آیا مجموعه شامل مقدار خاصی است یا خیر. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | اندیس یک IMMathBlock خاص را در مجموعه تعیین می‌کند. |
| [getCount()](#getCount--) | تعداد عناصر واقعاً موجود در مجموعه را دریافت می‌کند. |
| [get_Item(int index)](#get-Item-int-) | موردی را در اندیس مشخص شده دریافت می‌کند. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | موردی را در اندیس مشخص شده دریافت می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

IMMathBlock را به انتهای مجموعه اضافه می‌کند.

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

IMMathBlock را در موقعیت مشخص شده در مجموعه وارد می‌کند.

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
| index | int | اندیس صفر-پایه‌ای که مورد باید در آن وارد شود. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | IMMathBlock مورد نظر برای وارد کردن. |

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
boolean - در صورت حذف موفقیت‌آمیز مورد از مجموعه، مقدار true؛ در غیر این صورت، false. این متد همچنین در صورتی که مورد در مجموعه اصلی یافت نشود، false برمی‌گرداند.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

موردی را در اندیس مشخص شده در مجموعه حذف می‌کند.

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
| index | int | اندیس صفر-پایه‌ای موردی که باید حذف شود. |

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | شیء‌ای که در مجموعه باید پیدا شود. |

**بازگشت:**
boolean - در صورت یافتن مورد در مجموعه، مقدار true؛ در غیر این صورت, false.

### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

اندیس یک IMMathBlock خاص را در مجموعه تعیین می‌کند.

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
| item | [IMathBlock](../../com.aspose.slides/imathblock) | موردی که در مجموعه باید پیدا شود. |

**بازگشت:**
int - اندیس مورد اگر در مجموعه پیدا شود؛ در غیر این صورت، -1.

### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد عناصر واقعاً موجود در مجموعه را دریافت می‌کند. فقط-خواندنی int.

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

موردی را در اندیس مشخص شده دریافت می‌کند. فقط-خواندنی [IMathBlock](../../com.aspose.slides/imathblock).

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
| index | int | اندیس صفر-پایه‌ای موردی که باید دریافت شود. |

**بازگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - بلوک متن ریاضی.

### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

موردی را در اندیس مشخص شده دریافت می‌کند. فقط-خواندنی [IMathBlock](../../com.aspose.slides/imathblock).

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
| index | int | اندیس صفر-پایه‌ای موردی که باید تنظیم شود. |
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