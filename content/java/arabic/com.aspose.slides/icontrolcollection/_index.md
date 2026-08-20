---
title: IControlCollection
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ Java
description: مجموعة من عناصر التحكم ActiveX.
type: docs
url: /ar/com.aspose.slides/icontrolcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

مجموعة من عناصر التحكم ActiveX.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | يزيل عنصر تحكم ActiveX من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل عنصر تحكم ActiveX مخزن في الموضع المحدد من المجموعة. |
| [clear()](#clear--) | يزيل جميع عناصر التحكم من المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يُرجِع عنصر تحكم في الموضع المحدد. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | ينشئ ويضيف عنصر تحكم جديد إلى المجموعة. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

يزيل عنصر تحكم ActiveX من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | عنصر تحكم للإزالة. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل عنصر تحكم ActiveX مخزن في الموضع المحدد من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر لإزالته. |

### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع عناصر التحكم من المجموعة.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

يُرجِع عنصر تحكم في الموضع المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس العنصر. |

**القيمة المرجعة:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

ينشئ ويضيف عنصر تحكم جديد إلى المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| controlType | int | نوع عنصر التحكم للإضافة. |
| x | float | إحداثي X للجانب الأيسر لإطار الشكل. |
| y | float | إحداثي Y للجانب العلوي لإطار الشكل. |
| width | float | عرض إطار الشكل. |
| height | float | ارتفاع إطار الشكل. |

**القيمة المرجعة:**
[IControl](../../com.aspose.slides/icontrol) - عنصر تحكم تم إنشاؤه [IControl](../../com.aspose.slides/icontrol).