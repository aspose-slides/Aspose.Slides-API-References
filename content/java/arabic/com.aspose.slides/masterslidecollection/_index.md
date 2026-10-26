---
title: MasterSlideCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة من الشرائح الرئيسية.
type: docs
url: /ar/com.aspose.slides/masterslidecollection/
---
**الوراثة:**
java.lang.Object, com.aspose.slides.DomObject

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
```
public final class MasterSlideCollection extends DomObject<Presentation> implements IMasterSlideCollection
```

يمثل مجموعة من الشرائح الرئيسية.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يحصل على عدد العناصر الفعلية الموجودة في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | يزيل أول ظهور لكائن معين من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد في المجموعة. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | يزيل الشرائح الرئيسية غير المستخدمة. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | يضيف نسخة من شريحة رئيسية محددة إلى نهاية المجموعة. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | يدرج نسخة من شريحة رئيسية محددة إلى موضع محدد في المجموعة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تدل على ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر المزامنة. |
| [iterator()](#iterator--) | يعيد عدادًا يتنقل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مكرّر Java للمجموعة بأكملها. |
### size() {#size--}
```
public final int size()
```

يحصل على عدد العناصر الفعلية الموجودة في المجموعة. للقراءة فقط int.

**الإرجاع:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IMasterSlide get_Item(int index)
```

يحصل على العنصر في الفهرس المحدد. للقراءة فقط [MasterSlide](../../com.aspose.slides/masterslide).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### remove(IMasterSlide value) {#remove-com.aspose.slides.IMasterSlide-}
```
public final void remove(IMasterSlide value)
```

يزيل أول ظهور لكائن معين من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | الشريحة الرئيسية لإزالتها من المجموعة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيتم إزالته.

--------------------

لتجنب رمي استثناء PptxEditException، تحقق من خاصية HasDependingSlides للماستر مسبقًا. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

يزيل الشرائح الرئيسية غير المستخدمة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| ignorePreserveField | boolean | يحدد ما إذا كان يجب على هذه الطريقة إزالة الماستر غير المستخدم حتى لو تم تعيين الخاصية [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) إلى true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

يضيف نسخة من شريحة رئيسية محددة إلى نهاية المجموعة. سيتم نسخ الشرائح المرتبطة بالتخطيط أيضًا.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | الشريحة المراد استنساخها. |

**الإرجاع:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - الشريحة المضافة.
### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

يدرج نسخة من شريحة رئيسية محددة إلى موضع محدد في المجموعة. سيتم نسخ الشرائح المرتبطة بالتخطيط أيضًا.

--------------------

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // Instantiate Presentation class to load the source presentation file
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // Instantiate Presentation class for destination presentation (where slide is to be cloned)
>      Presentation destPres = new Presentation();
>      try {
>          // Instantiate ISlide from the collection of slides in source presentation along with
>          // Master slide
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // Get Master Slides of destination presentation
>          IMasterSlideCollection masters = destPres.getMasters();
>          // Clone the desired master slide from the source presentation to the collection of masters in the
>          // Destination presentation
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // Collection of slides in the destination presentation
>          ISlideCollection slds = destPres.getSlides();
>          // Clone source slide to destination slides collection.
>          slds.addClone(SourceSlide, iSlide, true);
>          // Save the destination presentation to disk
>          destPres.save("CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | الشريحة المراد استنساخها. |

**الإرجاع:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - شريحة الماستر المدخلة.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس البادئ في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تدل على ما إذا كان الوصول إلى المجموعة متزامنًا (آمن للخيوط). للقراءة فقط boolean.

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

يعيد جذر المزامنة. للقراءة فقط Object.

**الإرجاع:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iterator()
```

يعيد عدادًا يتنقل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

يعيد مكرّر Java للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - An java.util.Iterator for the entire collection.