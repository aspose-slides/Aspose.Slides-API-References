---
title: IMasterSlideCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل مجموعة من الشرائح الرئيسية.
type: docs
url: /ar/com.aspose.slides/imasterslidecollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IMasterSlideCollection extends IGenericCollection<IMasterSlide>
```

يمثل مجموعة من الشرائح الرئيسية.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | يزيل أول حدوث لكائن محدد من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | يزيل الشرائح الرئيسية غير المستخدمة. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | يضيف نسخة من شريحة رئيسية محددة إلى نهاية المجموعة. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | يدخل نسخة من شريحة رئيسية محددة إلى موقع محدد في المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IMasterSlide get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [IMasterSlide](../../com.aspose.slides/imasterslide).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public abstract void remove(IMasterSlide value)
```

يزيل أول حدوث لكائن محدد من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | الشريحة الرئيسية لإزالتها من المجموعة. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد من المجموعة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيتم إزالته. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public abstract void removeUnused(boolean ignorePreserveField)
```

يزيل الشرائح الرئيسية غير المستخدمة.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| ignorePreserveField | boolean | يحدد ما إذا كان يجب على هذه الطريقة إزالة الشريحة الرئيسية غير المستخدمة حتى إذا كانت خاصية [IMasterSlide.getPreserve](../../com.aspose.slides/imasterslide\#getPreserve)/[IMasterSlide.setPreserve(boolean)](../../com.aspose.slides/imasterslide\#setPreserve-boolean-) مضبوطة على true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide addClone(IMasterSlide sourceMaster)
```

يضيف نسخة من شريحة رئيسية محددة إلى نهاية المجموعة. سيتم نسخ الشرائح المرتبطة بالمخطط أيضًا.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | الشريحة المراد استنساخها. |

**القيمة المرجعة:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - الشريحة المضافة.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public abstract IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

يدخل نسخة من شريحة رئيسية محددة إلى موقع محدد في المجموعة. سيتم نسخ الشرائح المرتبطة بالمخطط أيضًا.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | الشريحة المراد استنساخها. |

**القيمة المرجعة:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - الشريحة الرئيسية المدرجة.