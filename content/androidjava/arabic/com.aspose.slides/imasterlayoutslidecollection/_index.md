---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides لأندرويد عبر مرجع API Java
description: يمثل مجموعة من جميع شرائح التخطيط للماستر المحدد.
type: docs
url: /ar/com.aspose.slides/imasterlayoutslidecollection/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

يمثل مجموعة من جميع شرائح التخطيط للماستر المحدد. يمتد واجهة ILayoutSlideCollection مع طرق لإضافة/إدراج/إزالة/استنساخ شرائح التخطيط في سياق مجموعات شرائح التخطيط الخاصة بالماستر.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | يُدرج نسخة من شريحة تخطيط محددة إلى الموضع المحدد في المجموعة. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | يضيف شريحة تخطيط جديدة إلى نهاية المجموعة. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | يُدرج شريحة تخطيط جديدة إلى الموضع المحدد في المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | ينقل شريحة التخطيط من المجموعة إلى الموضع المحدد. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة المراد استنساخها. |

--------------------

1) سيتم ربط التخطيط الجديد بشريحة الماستر الأصلية لمجموعة شرائح التخطيط هذه. لذا هذا يعادل النسخ/اللصق مع خيار "استخدام سمة الوجهة" في PowerPoint. 2) نظير هذه الطريقة هو الطريقة [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) التي يتم الوصول إليها عبر الخاصية [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - الشريحة المضافة.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

يُدرج نسخة من شريحة تخطيط محددة إلى الموضع المحدد في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة المراد استنساخها. |

--------------------

سيتم ربط التخطيط الجديد بشريحة الماستر الأصلية لمجموعة شرائح التخطيط هذه. لذا هذا يعادل النسخ/اللصق مع خيار "استخدام سمة الوجهة" في PowerPoint.

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - الشريحة المُدرجة.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

يضيف شريحة تخطيط جديدة إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| layoutType | byte | نوع التخطيط لشريحة جديدة. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. الأنواع الأخرى غير مدعومة حالياً: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | اسم التخطيط الجديد. إذا كان الاسم المُمرَّر مستخدمًا بالفعل سيتم رمي الاستثناء ArgumentException. إذا تم تمرير قيمة null فإن الاسم سُيتولد تلقائيًا بحسب نوع التخطيط المُمرَّر (مثال: "Title Slide" أو "1_Title Slide"، "2_.."، إلخ). |

--------------------

1) تم إضافة تخطيط للقيمة SlideLayoutType.Custom من نوع layoutType ولا يحتوي على عناصر نائبة ولا أشكال. 2) نظير هذه الطريقة هو الطريقة [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) التي يتم الوصول إليها عبر الخاصية [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - الشريحة المضافة.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

يُدرج شريحة تخطيط جديدة إلى الموضع المحدد في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| layoutType | byte | نوع التخطيط لشريحة جديدة. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. الأنواع الأخرى غير مدعومة حالياً: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | اسم التخطيط الجديد. إذا كان الاسم المُمرَّر مستخدمًا بالفعل سيتم رمي الاستثناء ArgumentException. إذا تم تمرير قيمة null فإن الاسم سُيتولد تلقائيًا بحسب نوع التخطيط المُمرَّر (مثال: "Title Slide" أو "1_Title Slide"، "2_.."، إلخ). |

--------------------

تم إدراج تخطيط للقيمة SlideLayoutType.Custom من نوع layoutType ولا يحتوي على عناصر نائبة ولا أشكال.

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - الشريحة المُدرجة.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر المراد إزالته. |

--------------------

1) لتجنب حدوث الاستثناء PptxEditException يُفضَّل فحص خاصية HasDependingSlides للتخطيط مسبقًا. 2) يمكنك أيضًا استخدام الطريقة [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) لتبسيط الشيفرة.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

ينقل شريحة التخطيط من المجموعة إلى الموضع المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الهدف. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة المراد نقلها. |