---
title: ILayoutSlideCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل فئة أساسية لمجموعة من شرائح التخطيط.
type: docs
url: /ar/com.aspose.slides/ilayoutslidecollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

يمثل فئة أساسية لمجموعة من شرائح التخطيط.
## الأساليب

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يرجع شريحة التخطيط حسب الفهرس. |
| [getByType(byte type)](#getByType-byte-) | يرجع أول شريحة تخطيط من النوع المحدد. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | يزيل تخطيطًا من المجموعة. |
| [removeUnused()](#removeUnused--) | يزيل شرائح التخطيط غير المستخدمة (شرائح التخطيط التي تكون خاصية HasDependingSlides فيها false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

يرجع شريحة التخطيط حسب الفهرس. للقراءة فقط [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**القيمة المرتجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

يرجع أول شريحة تخطيط من النوع المحدد.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | byte | نوع شريحة التخطيط للبحث عنها. |

**القيمة المرتجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) مع النوع المحدد أو null إذا لم يتم العثور على تخطيطات.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

يزيل تخطيطًا من المجموعة.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | شريحة التخطيط لإزالتها من المجموعة.

--------------------

1) لتجنب حدوث استثناء PptxEditException تحقق من خاصية HasDependingSlides للتخطيط مسبقًا. 2) يمكنك أيضًا استخدام طريقة [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) لتبسيط الشيفرة. |

### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

يزيل شرائح التخطيط غير المستخدمة (شرائح التخطيط التي تكون خاصية HasDependingSlides فيها false).