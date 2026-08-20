---
title: IMasterSlideCollection
second_title: Aspose.Slides لمرجع API لجافا
description: يمثِّل مجموعة من الشرائح الرئيسة.
type: docs
url: /ar/com.aspose.slides/imasterslidecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

Represents a collection of master slides.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يجلب العنصر في الفهرس المحدد. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | يزيل الظهور الأول لكائن محدد من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | يزيل الشرائح الرئيسية غير المستخدمة. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | يضيف نسخة من شريحة رئيسية محددة إلى نهاية المجموعة. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | يدرج نسخة من شريحة رئيسية محددة إلى موضع محدد في المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```


يجلب العنصر في الفهرس المحدد. للقراءة فقط [IMasterSlide](../../com.aspose.slides/imasterslide).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```


يزيل الظهور الأول لكائن محدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | الشريحة الرئيسية التي سيتم إزالتها من المجموعة. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


يزيل العنصر في الفهرس المحدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس صفر-الأساس للعنصر الذي سيتم إزالته. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```


يزيل الشرائح الرئيسية غير المستخدمة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| ignorePreserveField | boolean | يحدِّد ما إذا كان يجب على هذه الطريقة إزالة الشرائح الرئيسية غير المستخدمة حتى إذا كان خاصية [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) مضبوطة على true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```


يضيف نسخة من شريحة رئيسية محددة إلى نهاية المجموعة. سيتم نسخ الشرائح المرتبطة بالتخطيط أيضًا.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | الشريحة التي سيتم استنساخها. |

**القيمة المرجعة:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - الشريحة المضافة.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```


يدرج نسخة من شريحة رئيسية محددة إلى موضع محدد في المجموعة. سيتم نسخ الشرائح المرتبطة بالتخطيط أيضًا.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | الشريحة التي سيتم استنساخها. |

**القيمة المرجعة:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - الشريحة الرئيسية المدخلة.