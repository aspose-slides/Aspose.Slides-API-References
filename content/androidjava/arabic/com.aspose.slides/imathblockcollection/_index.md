---
title: IMathBlockCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API للـ Java
description: مجموعة من كتل الرياضيات IMMathBlock
type: docs
url: /ar/com.aspose.slides/imathblockcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathBlockCollection extends System.Collections.Generic.IGenericEnumerable<IMathBlock>
```

مجموعة من كتل الرياضيات (IMathBlock)

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
> ```

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [add(IMathBlock item)](#add-com.aspose.slides.IMathBlock-) | يضيف IMathBlock إلى نهاية المجموعة. |
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | يدرج IMathBlock في المجموعة في الفهرس المحدد. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | يزيل الظهور الأول لكائن محدد من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل عنصرًا في الفهرس المحدد من المجموعة. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | يحدد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | يحدد فهرس IMMathBlock محدد في المجموعة. |
| [getCount()](#getCount--) | يحصل على عدد العناصر الفعلية الموجودة في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | يحصل على العنصر في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

يضيف IMathBlock إلى نهاية المجموعة.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | كتلة رياضية سيتم إضافتها إلى نهاية المجموعة |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

يدرج IMathBlock في المجموعة في الفهرس المحدد.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يتم فيه إدراج العنصر. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | الـ IMathBlock المراد إدراجه. |

### remove(IMathBlock item) {#remove-com.aspose.slides.IMathBlock-}
```
public abstract boolean remove(IMathBlock item)
```

يزيل الظهور الأول لكائن محدد من المجموعة.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.remove(block);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | الكائن الذي سيتم إزالته من المجموعة. |

**Returns:**
boolean - true إذا تم إزالة العنصر بنجاح من المجموعة؛ وإلا، false. تُعيد هذه الطريقة false أيضًا إذا لم يُعثر على العنصر في المجموعة الأصلية.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل عنصرًا في الفهرس المحدد من المجموعة.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيتم إزالته. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

يحدد ما إذا كانت المجموعة تحتوي على قيمة محددة.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | الكائن الذي يتم البحث عنه في المجموعة. |

**Returns:**
boolean - true إذا تم العثور على العنصر في المجموعة؛ وإلا، false.

### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

يحدد فهرس IMMathBlock محدد في المجموعة.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | العنصر الذي سيُبحث عنه في المجموعة. |

**Returns:**
int - فهرس العنصر إذا تم العثور عليه في المجموعة؛ وإلا، -1.

### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد العناصر الفعلية الموجودة في المجموعة. Read-only int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**Returns:**
int

### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. Read-only [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيُسترجع. |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة نص رياضية.

### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

يحصل على العنصر في الفهرس المحدد. Read-only [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيتم تعيينه. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | كتلة نص رياضية. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع العناصر من المجموعة.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  blockCollection.clear();
> ```