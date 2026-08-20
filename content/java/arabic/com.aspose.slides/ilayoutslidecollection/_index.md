---
title: ILayoutSlideCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل فئة أساسية لمجموعة من شرائح التخطيط.
type: docs
url: /ar/com.aspose.slides/ilayoutslidecollection/
---
**جميع الواجهات المُنفّذة:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

يمثل فئة أساسية لمجموعة من شرائح التخطيط.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد شريحة التخطيط بحسب الفهرس. |
| [getByType(byte type)](#getByType-byte-) | يعيد أول شريحة تخطيط من النوع المحدد. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | يزيل تخطيطًا من المجموعة. |
| [removeUnused()](#removeUnused--) | يزيل شرائح التخطيط غير المستخدمة (شرائح التخطيط التي تكون خاصية HasDependingSlides فيها false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```

يعيد شريحة التخطيط بحسب الفهرس. قراءة فقط [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرتجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```

يعيد أول شريحة تخطيط من النوع المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| type | byte | نوع شريحة التخطيط للبحث عنها. |

**القيمة المرتجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) بالنوع المحدد أو null إذا لم يتم العثور على أي تخطيطات.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```

يزيل تخطيطًا من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | شريحة التخطيط التي ستُزال من المجموعة.

--------------------

1) لتجنب حدوث استثناء PptxEditException، تحقق من خاصية HasDependingSlides للشريحة قبل ذلك. 2) يمكنك أيضًا استخدام طريقة [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) لتبسيط الشيفرة. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```

يزيل شرائح التخطيط غير المستخدمة (شرائح التخطيط التي تكون خاصية HasDependingSlides فيها false).