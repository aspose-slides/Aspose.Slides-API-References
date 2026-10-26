---
title: IMathElementCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة Java
description: يمثل مجموعة من العناصر الرياضية MathElement.
type: docs
url: /ar/com.aspose.slides/imathelementcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

يمثل مجموعة من العناصر الرياضية (MathElement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock();
> ```
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [getCount()](#getCount--) | يحصل على عدد العناصر الموجودة فعليًا في المجموعة. |
| [add(IMathElement item)](#add-com.aspose.slides.IMathElement-) | يضيف عنصرًا رياضيًا إلى نهاية المجموعة. |
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | يحدد فهرس عنصر رياضي معين في المجموعة. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | يدرج عنصرًا رياضيًا في المجموعة عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | يزيل أول حدوث لكائن معين من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | نسخ إلى المصفوفة المحددة. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. قراءة فقط [IMathElement](../../com.aspose.slides/imathelement).

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  IMathElement firstElem = collection.get_Item(0);
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر المراد الحصول عليه |

**الإرجاع:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```

يحصل على عدد العناصر الموجودة فعليًا في المجموعة. قراءة فقط int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**الإرجاع:**
int
### add(IMathElement item) {#add-com.aspose.slides.IMathElement-}
```
public abstract void add(IMathElement item)
```

يضيف عنصرًا رياضيًا إلى نهاية المجموعة.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.add(new MathematicalText("+"));
>  collection.add(new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMathElement لإضافته إلى نهاية المجموعة. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```

يحدد فهرس عنصر رياضي معين في المجموعة.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | العنصر لتحديد موقعه في المجموعة. |

**الإرجاع:**
int - فهرس العنصر إذا تم العثور عليه في المجموعة؛ وإلا، -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```

يدرج عنصرًا رياضيًا في المجموعة عند الفهرس المحدد.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  MathematicalText plusElement = new MathematicalText("+");
>  collection.add(plusElement);
>  collection.insert(0, new MathRadical(new MathematicalText("x"), new MathematicalText("3")));
> ```

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري الذي ينبغي إدراج IMathElement فيه. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | IMMathElement لإدراجه. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع العناصر من المجموعة.

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

يحدد ما إذا كانت المجموعة تحتوي على قيمة معينة.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | الكائن لتحديد موقعه في المجموعة. |

**الإرجاع:**
boolean - true إذا تم العثور على الكائن في المجموعة؛ وإلا false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```

يزيل أول حدوث لكائن معين من المجموعة.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| item | [IMathElement](../../com.aspose.slides/imathelement) | الكائن لإزالته من المجموعة. |

**الإرجاع:**
boolean - true إذا تم إزالة الكائن بنجاح من المجموعة؛ وإلا false. كما تُعيد هذه الطريقة false إذا لم يُعثر على الكائن في المجموعة الأصلية.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد من المجموعة.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر المراد إزالته. |

### copyTo(IMathElement[] array, int arrayIndex) {#copyTo-com.aspose.slides.IMathElement---int-}
```
public abstract void copyTo(IMathElement[] array, int arrayIndex)
```

نسخ إلى المصفوفة المحددة.

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | المصفوفة للنسخ إليها. |
| arrayIndex | int | الفهرس لبدء النسخ. |