---
title: MasterSlideCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API للغة جافا
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
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يحصل على عدد العناصر الفعلية الموجودة في المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يحصل على العنصر في الفهرس المحدد. |
| [remove(IMasterSlide value)](#remove-com.aspose.slides.IMasterSlide-) | يزيل أول ظهور لكائن محدد من المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [removeUnused(boolean ignorePreserveField)](#removeUnused-boolean-) | يزيل الشرائح الرئيسية غير المستخدمة. |
| [addClone(IMasterSlide sourceMaster)](#addClone-com.aspose.slides.IMasterSlide-) | يضيف نسخة من شريحة رئيسية محددة إلى نهاية المجموعة. |
| [insertClone(int index, IMasterSlide sourceMaster)](#insertClone-int-com.aspose.slides.IMasterSlide-) | يدرج نسخة من شريحة رئيسية محددة في موضع محدد داخل المجموعة. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن الخيوط). |
| [getSyncRoot()](#getSyncRoot--) | يعيد جذر المزامنة. |
| [iterator()](#iterator--) | يعيد مُعددًا يتكرر عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | يعيد مُكرر جافا للمجموعة بأكملها. |

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

يزيل أول ظهور لكائن محدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) | الشريحة الرئيسية التي سيتم إزالتها من المجموعة. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس القائم على الصفر للعنصر الذي سيتم إزالته. |

--------------------

لتجنب حدوث استثناء PptxEditException، تحقق من خاصية HasDependingSlides للماستر قبل ذلك. |

### removeUnused(boolean ignorePreserveField) {#removeUnused-boolean-}
```
public final void removeUnused(boolean ignorePreserveField)
```

يزيل الشرائح الرئيسية غير المستخدمة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| ignorePreserveField | boolean | يحدد ما إذا كان يجب على هذه الطريقة إزالة الماستر غير المستخدم حتى إذا كانت خاصية [MasterSlide.getPreserve](../../com.aspose.slides/masterslide\#getPreserve)/[MasterSlide.setPreserve(boolean)](../../com.aspose.slides/masterslide\#setPreserve-boolean-) مضبوطة على true. |

### addClone(IMasterSlide sourceMaster) {#addClone-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide addClone(IMasterSlide sourceMaster)
```

يضيف نسخة من شريحة رئيسية محددة إلى نهاية المجموعة. سيتم نسخ شرائح التخطيط المرتبطة أيضًا.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | الشريحة التي سيتم استنساخها. |

**الإرجاع:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - شريحة مضافة.

### insertClone(int index, IMasterSlide sourceMaster) {#insertClone-int-com.aspose.slides.IMasterSlide-}
```
public final IMasterSlide insertClone(int index, IMasterSlide sourceMaster)
```

يدرج نسخة من شريحة رئيسية محددة في موضع محدد داخل المجموعة. سيتم نسخ شرائح التخطيط المرتبطة أيضًا.

---

> ```
> The following example shows how to clone master slide in another PowerPoint Presentation.
>  
>  // إنشاء فئة Presentation لتحميل ملف العرض المصدر
>  Presentation srcPres = new Presentation("CloneToAnotherPresentationWithMaster.pptx");
>  try {
>      // إنشاء فئة Presentation للعرض الوجهة (حيث سيتم استنساخ الشريحة)
>      Presentation destPres = new Presentation();
>      try {
>          // إنشاء ISlide من مجموعة الشرائح في العرض المصدر مع
>          // الشريحة الرئيسية
>          ISlide SourceSlide = srcPres.getSlides().get_Item(0);
>          IMasterSlide SourceMaster = SourceSlide.getLayoutSlide().getMasterSlide();
>          // الحصول على الشرائح الرئيسية للعرض الوجهة
>          IMasterSlideCollection masters = destPres.getMasters();
>          // استنسخ الشريحة الرئيسية المطلوبة من العرض المصدر إلى مجموعة الماسترات في الـ
>          // العرض الوجهة
>          IMasterSlide iSlide = masters.addClone(SourceMaster);
>          // مجموعة الشرائح في العرض الوجهة
>          ISlideCollection slds = destPres.getSlides();
>          // استنسخ الشريحة المصدر إلى مجموعة الشرائح في العرض الوجهة.
>          slds.addClone(SourceSlide, iSlide, true);
>          // حفظ العرض الوجهة إلى القرص
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
| sourceMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | الشريحة التي سيتم استنساخها. |

**الإرجاع:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - شريحة ماستر تم إدراجها.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

ينسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

يعيد قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامنًا (آمن الخيوط). للقراءة فقط boolean.

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

يعيد مُعددًا يتكرر عبر المجموعة.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - مُعدد IGenericEnumerator يمكن استخدامه للتكرار عبر المجموعة.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMasterSlide> iteratorJava()
```

يعيد مُكرر جافا للمجموعة بأكملها.

**الإرجاع:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMasterSlide> - java.util.Iterator للمجموعة بأكملها.