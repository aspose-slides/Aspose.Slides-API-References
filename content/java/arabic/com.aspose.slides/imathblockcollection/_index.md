---
title: IMathBlockCollection
second_title: مرجع API Aspose.Slides للـ Java
description: مجموعة من كتل الرياضيات IMMathBlock
type: docs
url: /ar/com.aspose.slides/imathblockcollection/
---
**جميع الواجهات المطبقة:**
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
| [insert(int index, IMathBlock item)](#insert-int-com.aspose.slides.IMathBlock-) | يدرج IMathBlock في المجموعة عند الفهرس المحدد. |
| [remove(IMathBlock item)](#remove-com.aspose.slides.IMathBlock-) | يزيل الظهور الأول لكائن محدد من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل عنصرًا عند الفهرس المحدد في المجموعة. |
| [contains(IMathBlock item)](#contains-com.aspose.slides.IMathBlock-) | تحدد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [indexOf(IMathBlock item)](#indexOf-com.aspose.slides.IMathBlock-) | تحدد الفهرس لـ IMathBlock محدد في المجموعة. |
| [getCount()](#getCount--) | تحصل على عدد العناصر الفعلية الموجودة في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | تحصل على العنصر عند الفهرس المحدد. |
| [set_Item(int index, IMathBlock value)](#set-Item-int-com.aspose.slides.IMathBlock-) | تحصل على العنصر عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
### add(IMathBlock item) {#add-com.aspose.slides.IMathBlock-}
```
public abstract void add(IMathBlock item)
```

يضيف IMMathBlock إلى نهاية المجموعة.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("x")));
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | كتلة رياضية ستُضاف إلى نهاية المجموعة |

### insert(int index, IMathBlock item) {#insert-int-com.aspose.slides.IMathBlock-}
```
public abstract void insert(int index, IMathBlock item)
```

يدرج IMathBlock في المجموعة عند الفهرس المحدد.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.insert(0, block);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي يجب إدراج العنصر عنده. |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | IMathBlock المراد إدراجه. |

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

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | الكائن الذي سيتم إزالته من المجموعة. |

**الإرجاع:**
boolean - true إذا تمت إزالة العنصر بنجاح من المجموعة؛ otherwise, false. هذه الطريقة تُعيد أيضًا false إذا لم يُعثر على العنصر في المجموعة الأصلية.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل عنصرًا عند الفهرس المحدد في المجموعة.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  blockCollection.removeAt(0);
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيتم إزالته. |

### contains(IMathBlock item) {#contains-com.aspose.slides.IMathBlock-}
```
public abstract boolean contains(IMathBlock item)
```

تحدد ما إذا كانت المجموعة تحتوي على قيمة محددة.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.addd(block);
>  bool contains = blockCollection.contains(block);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | الكائن لتحديد موقعه في المجموعة. |

**الإرجاع:**
boolean - true إذا تم العثور على العنصر في المجموعة؛ otherwise, false.
### indexOf(IMathBlock item) {#indexOf-com.aspose.slides.IMathBlock-}
```
public abstract int indexOf(IMathBlock item)
```

تحدد الفهرس لـ IMathBlock محدد في المجموعة.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  IMathBlock block = new MathBlock(new MathematicalText("y"));
>  blockCollection.add(block);
>  int index = blockCollection.indexOf(block);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [IMathBlock](../../com.aspose.slides/imathblock) | العنصر لتحديد موقعه في المجموعة. |

**الإرجاع:**
int - فهرس العنصر إذا وجد في المجموعة؛ otherwise, -1.
### getCount() {#getCount--}
```
public abstract int getCount()
```

تحصل على عدد العناصر الفعلية الموجودة في المجموعة. قراءة فقط int.

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  int blocksCount = blockCollection.getCount();
> ```

**القيمة المرجعة:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathBlock get_Item(int index)
```

تحصل على العنصر عند الفهرس المحدد. قراءة فقط [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيتم الحصول عليه. |

**الإرجاع:**
[IMathBlock](../../com.aspose.slides/imathblock) - كتلة من نص رياضي.
### set_Item(int index, IMathBlock value) {#set-Item-int-com.aspose.slides.IMathBlock-}
```
public abstract void set_Item(int index, IMathBlock value)
```

تحصل على العنصر عند الفهرس المحدد. قراءة فقط [IMathBlock](../../com.aspose.slides/imathblock).

--------------------

> ```
> Example:
>  
>  IMathBlockCollection blockCollection = new MathParagraph();
>  blockCollection.add(new MathBlock(new MathematicalText("block1")));
>  blockCollection.add(new MathBlock(new MathematicalText("block2")));
>  IMathBlock block = blockCollection.get_Item(1);
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيتم تعيينه. |
| value | [IMathBlock](../../com.aspose.slides/imathblock) | الكتلة من نص رياضي. |

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