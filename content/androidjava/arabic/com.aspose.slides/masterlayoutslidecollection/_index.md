---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides للـ Android عبر مرجع API Java
description: يمثل مجموعة من جميع شرائح التخطيط للشريحة الرئيسة المحددة.
type: docs
url: /ar/com.aspose.slides/masterlayoutslidecollection/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

يمثل مجموعة من جميع شرائح التخطيط للماستر شريحة المحددة. يمتد فئة LayoutSlideCollection مع طرق لإضافة/إدراج/إزالة/استنساخ/إعادة ترتيب شرائح التخطيط في سياق مجموعات شرائح التخطيط الخاصة بالماستر.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | يدرج نسخة من شريحة تخطيط محددة إلى الموضع المحدد في المجموعة. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | يضيف شريحة تخطيط جديدة إلى نهاية المجموعة. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | يدرج شريحة تخطيط جديدة إلى الموضع المحدد في المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | ينقل شريحة التخطيط من المجموعة إلى الموضع المحدد. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة التي سيُستنسخ منها. |

--------------------

1) سيتم ربط التخطيط الجديد بالشريحة الرئيسة لهذا التجميع من شرائح التخطيط. وبالتالي هو مماثل لعملية النسخ/اللصق مع خيار "استخدام نسق الوجهة" في PowerPoint.  
2) طريقة مماثلة لهذه الطريقة هي الطريقة [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) التي تُستدعى عبر الخاصية ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).  

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - الشريحة المضافة.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

يدرج نسخة من شريحة تخطيط محددة إلى الموضع المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة التي سيُستنسخ منها. |

--------------------

سيتم ربط التخطيط الجديد بالشريحة الرئيسة لهذا التجميع من شرائح التخطيط. وبالتالي هو مماثل لعملية النسخ/اللصق مع خيار "استخدام نسق الوجهة" في PowerPoint.

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - الشريحة المدرجة.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

يضيف شريحة تخطيط جديدة إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| layoutType | byte | نوع التخطيط للمت Layout الجديد. الأنواع المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. الأنواع الأخرى غير مدعومة حالياً: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | اسم التخطيط الجديد. إذا كان الاسم المُمرَّر مستخدمًا مسبقًا سيتم إثارة استثناء ArgumentException. إذا تم تمرير قيمة null سيتم توليد اسم تلقائيًا وفقًا لنوع التخطيط (مثال: "Title Slide" أو "1_Title Slide"، "2_.."، إلخ). |

--------------------

1) تم إضافة تخطيط للقيمة SlideLayoutType.Custom من layoutType لا يحتوي على عناصر نائبة ولا أشكال.  
2) طريقة مماثلة لهذه الطريقة هي الطريقة [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) التي تُستدعى عبر الخاصية ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).  

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - الشريحة المضافة.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

يدرج شريحة تخطيط جديدة إلى الموضع المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| layoutType | byte | نوع التخطيط للمت Layout الجديد. الأنواع المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. الأنواع الأخرى غير مدعومة حالياً: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | اسم التخطيط الجديد. إذا كان الاسم المُمرَّر مستخدمًا مسبقًا سيتم إثارة استثناء ArgumentException. إذا تم تمرير قيمة null سيتم توليد اسم تلقائيًا وفقًا لنوع التخطيط (مثال: "Title Slide" أو "1_Title Slide"، "2_.."، إلخ). |

--------------------

تم إدراج تخطيط للقيمة SlideLayoutType.Custom من layoutType لا يحتوي على عناصر نائبة ولا أشكال.

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - الشريحة المدرجة.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر الذي سيُزال. |

--------------------

1) لتجنب إثارة استثناء PptxEditException تحقق من الخاصية HasDependingSlides للتخطيط أولاً.  
2) يمكنك أيضًا استخدام طريقة [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) لتبسيط الشيفرة.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

ينقل شريحة التخطيط من المجموعة إلى الموضع المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الهدف. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة التي سيُنقلها. |