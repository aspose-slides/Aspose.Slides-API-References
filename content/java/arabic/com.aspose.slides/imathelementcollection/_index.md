---
title: IMathElementCollection
second_title: Aspose.Slides لمرجع API لجافا
description: يمثل مجموعة من العناصر الرياضية MathElement.
type: docs
url: /ar/com.aspose.slides/imathelementcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMathElementCollection extends System.Collections.Generic.IGenericEnumerable<IMathElement>
```

تمثل مجموعة من العناصر الرياضية (MathElement).

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
| [indexOf(IMathElement item)](#indexOf-com.aspose.slides.IMathElement-) | يحدد الفهرس لعنصر رياضي معين في المجموعة. |
| [insert(int index, IMathElement item)](#insert-int-com.aspose.slides.IMathElement-) | يدخل عنصرًا رياضيًا في المجموعة عند الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [contains(IMathElement item)](#contains-com.aspose.slides.IMathElement-) | يحدد ما إذا كانت المجموعة تحتوي على قيمة محددة. |
| [remove(IMathElement item)](#remove-com.aspose.slides.IMathElement-) | يزيل أول ظهور لكائن محدد من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر عند الفهرس المحدد في المجموعة. |
| [copyTo(IMathElement[] array, int arrayIndex)](#copyTo-com.aspose.slides.IMathElement---int-) | نسخ إلى المصفوفة المحددة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMathElement get_Item(int index)
```


يحصل على العنصر في الفهرس المحدد. للقراءة فقط [IMathElement](../../com.aspose.slides/imathelement).

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
| index | int | الفهرس الصفري للعنصر المطلوب الحصول عليه |

**القيمة المرجعة:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCount() {#getCount--}
```
public abstract int getCount()
```


يحصل على عدد العناصر الموجودة فعليًا في المجموعة. للقراءة فقط int.

--------------------

> ```
> Example:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  int count = collection.getCount();
> ```

**القيمة المرجعة:**
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
| item | [IMathElement](../../com.aspose.slides/imathelement) | عنصر IMathElement الذي سيُضاف إلى نهاية المجموعة. |

### indexOf(IMathElement item) {#indexOf-com.aspose.slides.IMathElement-}
```
public abstract int indexOf(IMathElement item)
```


يحدد الفهرس لعنصر رياضي معين في المجموعة.

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
| item | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الذي سيُحدد موقعه في المجموعة. |

**القيمة المرجعة:**
int - الفهرس للعنصر إذا وُجد في المجموعة؛ وإلا -1.
### insert(int index, IMathElement item) {#insert-int-com.aspose.slides.IMathElement-}
```
public abstract void insert(int index, IMathElement item)
```


يدخل عنصرًا رياضيًا في المجموعة عند الفهرس المحدد.

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
| index | int | الفهرس الصفري الذي سيُدرج فيه IMathElement. |
| item | [IMathElement](../../com.aspose.slides/imathelement) | عنصر IMathElement الذي سيُدخل. |

### clear() {#clear--}
```
public abstract void clear()
```


يزيل جميع العناصر من المجموعة.

--------------------

> ```
> مثال:
>  
>  IMathElementCollection collection = new MathBlock(new MathematicalText("x"));
>  collection.clear();
> ```

### contains(IMathElement item) {#contains-com.aspose.slides.IMathElement-}
```
public abstract boolean contains(IMathElement item)
```


يحدد ما إذا كانت المجموعة تحتوي على قيمة محددة.

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
| item | [IMathElement](../../com.aspose.slides/imathelement) | الكائن الذي سيُحدد موقعه في المجموعة. |

**القيمة المرجعة:**
boolean - true إذا تم العثور على العنصر في المجموعة؛ وإلا false.
### remove(IMathElement item) {#remove-com.aspose.slides.IMathElement-}
```
public abstract boolean remove(IMathElement item)
```


يزيل أول ظهور لكائن محدد من المجموعة.

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
| item | [IMathElement](../../com.aspose.slides/imathelement) | الكائن الذي سيُزال من المجموعة. |

**القيمة المرجعة:**
boolean - true إذا تم إزالة العنصر بنجاح من المجموعة؛ وإلا false. تُعيد هذه الطريقة false أيضًا إذا لم يُعثر على العنصر في المجموعة الأصلية.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


يزيل العنصر عند الفهرس المحدد في المجموعة.

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
| index | int | الفهرس الصفري للعنصر الذي سيُزال. |

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
| array | [IMathElement\[\]](../../com.aspose.slides/imathelement) | المصفوفة التي يُنسخ إليها. |
| arrayIndex | int | الفهرس للبدء في النسخ. |