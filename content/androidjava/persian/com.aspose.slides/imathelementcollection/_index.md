---
title: IMathElementCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهنده یک مجموعه از عناصر ریاضی MathElement.
type: docs
url: /fa/com.aspose.slides/imathelementcollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

نمایش یک مجموعه از عناصر ریاضی (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در ایندکس مشخص شده است دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد عناصری که واقعاً در مجموعه موجود است را دریافت می‌کند. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | یک عنصر ریاضی را به انتهای مجموعه اضافه می‌کند. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | شاخص یک عنصر ریاضی خاص را در مجموعه تعیین می‌کند. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | یک عنصر ریاضی را در ایندکس مشخص شده در مجموعه وارد می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | اینکه آیا مجموعه شامل یک مقدار خاص است را تعیین می‌کند. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر در ایندکس مشخص شده از مجموعه را حذف می‌کند. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | به آرایه مشخص شده کپی می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

عنصری را که در ایندکس مشخص شده است دریافت می‌کند. فقط خواندنی [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```


**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | int | ایندکس پایه صفر برای آیتم مورد دریافت. |

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد عناصری که واقعاً در مجموعه موجود است را دریافت می‌کند. فقط خواندنی int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**بازگشت:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```

یک عنصر ریاضی را به انتهای مجموعه اضافه می‌کند.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement که باید به انتهای مجموعه اضافه شود. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```

شاخص یک عنصر ریاضی خاص را در مجموعه تعیین می‌کند.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  int index = collection.indexOf(plusElement);
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که باید در مجموعه موقعیت‌یابی شود. |

**بازگشت:**
int - شاخص مورد اگر در مجموعه یافت شود؛ در غیر اینصورت -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

یک عنصر ریاضی را در ایندکس مشخص شده در مجموعه وارد می‌کند.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | int | ایندکس پایه صفر که IMathElement باید در آن وارد شود. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement که باید وارد شود. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```

اینکه آیا مجموعه شامل مقدار خاصی است را تعیین می‌کند.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | شیء‌ای که باید در مجموعه یافت شود. |

**بازگشت:**
boolean - true اگر مورد در مجموعه یافت شود؛ در غیر اینصورت false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.remove(plusElement);
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | شیء‌ای که باید از مجموعه حذف شود. |

**بازگشت:**
boolean - true اگر مورد با موفقیت از مجموعه حذف شد؛ در غیر اینصورت false. این متد همچنین false برمی‌گرداند اگر مورد در مجموعه اصلی یافت نشود.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصر در ایندکس مشخص شده از مجموعه را حذف می‌کند.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  collection.removeAt(2);
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| index | int | ایندکس پایه صفر برای عنصری که باید حذف شود. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

به آرایه مشخص شده کپی می‌کند.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  IMathElement[] destinationArray = new IMathElement[collection.Count];
>  collection.copyTo(destinationArray, 0);
> ```

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | آرایه‌ای که باید به آن کپی شود. |
| arrayIndex | int | ایندکس برای شروع کپی. |