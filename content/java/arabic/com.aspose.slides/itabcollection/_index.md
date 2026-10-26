---
title: ITabCollection
second_title: Aspose.Slides لمرجع API جافا
description: يمثل مجموعة من الفواصل.
type: docs
url: /ar/com.aspose.slides/itabcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

يمثل مجموعة من الفواصل.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [add(double position, int align)](#add-double-int-) | يضيف فاصلًا إلى المجموعة. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | يضيف فاصلًا إلى المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. قراءة فقط [ITab](../../com.aspose.slides/itab).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

يضيف فاصلًا إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| position | double | موضع الفاصل. |
| align | int | محاذاة الفاصل. |

**القيمة المرجعة:**
[ITab](../../com.aspose.slides/itab)
- الفاصل المضاف.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

يضيف فاصلًا إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | كائن الفاصل الذي سيُضاف في نهاية المجموعة. |

**القيمة المرجعة:**
int - الفهرس الذي أضيف فيه الفاصل.
### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع العناصر من المجموعة.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيُزال. |