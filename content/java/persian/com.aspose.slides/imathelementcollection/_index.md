---
title: IMathElementCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایش‌دهنده‌ی مجموعه‌ای از عناصر ریاضی MathElement.
type: docs
url: /fa/com.aspose.slides/imathelementcollection/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

نمایش‌دهندهٔ مجموعه‌ای از عناصر ریاضی (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در اندیس مشخص شده قرار دارد، برمی‌گرداند. |
| [getCount()](#getCount--) | تعداد عناصری که در واقع در مجموعه موجود هستند را برمی‌گرداند. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | یک عنصر ریاضی را به انتهای مجموعه اضافه می‌کند. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | اندیس یک عنصر ریاضی خاص در مجموعه را تعیین می‌کند. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | یک عنصر ریاضی را در اندیس مشخص شده در مجموعه وارد می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | اینکه آیا مجموعه شامل مقدار خاصی است را تعیین می‌کند. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصری را که در اندیس مشخص شده از مجموعه قرار دارد حذف می‌کند. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | کپی به آرایهٔ مشخص‌شده. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

عنصری را که در اندیس مشخص شده قرار دارد برمی‌گرداند. فقط-خواندنی [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
>  ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | اندیس صفر-پایهٔ موردی که باید دریافت شود |

**بازگشت:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد عناصری که در واقع در مجموعه موجود هستند را برمی‌گرداند. فقط-خواندنی int.

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
| پارامتر | نوع | شرح |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | عنصر IMathElementی که باید به انتهای مجموعه اضافه شود. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```

اندیس یک عنصر ریاضی خاص در مجموعه را تعیین می‌کند.

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
| پارامتر | نوع | شرح |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | عنصری که در مجموعه باید پیدا شود. |

**بازگشت:**
int - اندیس عنصر اگر در مجموعه پیدا شود؛ در غیر اینصورت -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

یک عنصر ریاضی را در اندیس مشخص شده در مجموعه وارد می‌کند.

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
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که IMathElement باید در آن وارد شود. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | عنصر IMathElementی که باید وارد شود. |

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
>  IMMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
>  bool contains = collection.contains(plusElement);
> ```

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | شیئی که باید در مجموعه پیدا شود. |

**بازگشت:**
boolean - درست اگر مورد در مجموعه پیدا شود؛ در غیر اینصورت نادرست.
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
| پارامتر | نوع | شرح |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | شیئی که باید از مجموعه حذف شود. |

**بازگشت:**
boolean - درست اگر مورد با موفقیت از مجموعه حذف شود؛ در غیر اینصورت نادرست. این متد همچنین نادرست را برمی‌گرداند اگر مورد در مجموعه اصلی پیدا نشود.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصری را که در اندیس مشخص شده از مجموعه قرار دارد حذف می‌کند.

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
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | اندیس صفر-پایهٔ عنصری که باید حذف شود. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

کپی به آرایهٔ مشخص‌شده.

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
| پارامتر | نوع | شرح |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | آرایه‌ای که باید به آن کپی شود. |
| arrayIndex | int | اندیسی که کپی از آن آغاز می‌شود. |