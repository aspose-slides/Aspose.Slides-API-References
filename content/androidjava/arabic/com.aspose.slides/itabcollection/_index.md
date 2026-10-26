---
title: ITabCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من علامات التبويب.
type: docs
url: /ar/com.aspose.slides/itabcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

يمثل مجموعة من Tabs.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر عند الفهرس المحدد. |
| [add(double position, int align)](#add-double-int-) | يضيف Tab إلى المجموعة. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | يضيف Tab إلى المجموعة. |
| [clear()](#clear--) | يزيل جميع العناصر من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر عند الفهرس المحدد من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

يحصل على العنصر عند الفهرس المحدد. للقراءة فقط [ITab](../../com.aspose.slides/itab).

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

يضيف Tab إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| position | double | موضع Tab. |
| align | int | محاذاة Tab. |

**القيمة المرجعة:**
[ITab](../../com.aspose.slides/itab) - تمت إضافة tab.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

يضيف Tab إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | كائن Tab الذي سيُضاف في نهاية المجموعة. |

**القيمة المرجعة:**
int - الفهرس الذي تم فيه إضافة tab.
### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع العناصر من المجموعة.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل العنصر عند الفهرس المحدد من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيُزال. |