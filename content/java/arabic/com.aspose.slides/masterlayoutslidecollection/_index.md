---
title: MasterLayoutSlideCollection
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل مجموعة من جميع شرائح التخطيط للماستر المحدد.
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

يمثل مجموعة من جميع شرائح التخطيط للماستر المحدد. يمتد فئة LayoutSlideCollection مع طرق لإضافة/إدراج/إزالة/استنساخ/إعادة ترتيب شرائح التخطيط في سياق المجموعات الفردية لشرائح التخطيط الخاصة بالماستر.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | يدرج نسخة من شريحة تخطيط محددة إلى الموضع المحدد في المجموعة. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | يضيف شريحة تخطيط جديدة إلى نهاية المجموعة. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | يدرج شريحة تخطيط جديدة إلى الموضع المحدد في المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | نقل شريحة التخطيط من المجموعة إلى الموضع المحدد. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة لاستنساخها. |

--------------------

1) سيتم ربط التخطيط الجديد بشريحة الماستر الأصلية لهذه المجموعة من شرائح التخطيط. لذا هذا يُعادل النسخ/اللصق مع خيار "Use Destination Theme" في PowerPoint. 2) يُعادل هذه الطريقة الطريقة [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) التي يتم الوصول إليها عبر الخاصية ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مضافة.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

يدرج نسخة من شريحة تخطيط محددة إلى الموضع المحدد في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة لاستنساخها. |

--------------------

سيتم ربط التخطيط الجديد بشريحة الماستر الأصلية لهذه المجموعة من شرائح التخطيط. لذا هذا يُعادل النسخ/اللصق مع خيار "Use Destination Theme" في PowerPoint.

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة تم إدراجها.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

يضيف شريحة تخطيط جديدة إلى نهاية المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| layoutType | byte | نوع التخطيط لتصميم جديد. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. الأنواع الأخرى غير المدعومة حالياً: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | اسم لتصميم جديد. إذا كان الاسم الممرّر مستخدمًا مسبقًا سيتم إلقاء ArgumentException. إذا تم تمرير معامل null فسيتم توليد الاسم تلقائيًا وفقًا لنوع التخطيط الممرّر (على سبيل المثال "Title Slide" أو "1\_Title Slide"، "2\_.."، إلخ). |

--------------------

1) تم إضافة تخطيط للقيمة SlideLayoutType.Custom من layoutType لا يحتوي على عناصر نائبة ولا أشكال. 2) يُعادل هذه الطريقة الطريقة [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) التي يتم الوصول إليها عبر الخاصية ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مضافة.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

يدرج شريحة تخطيط جديدة إلى الموضع المحدد في المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| layoutType | byte | نوع التخطيط لتصميم جديد. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. الأنواع الأخرى غير المدعومة حالياً: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | اسم لتصميم جديد. إذا كان الاسم الممرّر مستخدمًا مسبقًا سيتم إلقاء ArgumentException. إذا تم تمرير معامل null فسيتم توليد الاسم تلقائيًا وفقًا لنوع التخطيط الممرّر (على سبيل المثال "Title Slide" أو "1\_Title Slide"، "2\_.."، إلخ). |

--------------------

تم إدراج تخطيط للقيمة SlideLayoutType.Custom من layoutType لا يحتوي على عناصر نائبة ولا أشكال.

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة تم إدراجها.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

يزيل العنصر في الفهرس المحدد من المجموعة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر المراد إزالته. |

--------------------

1) لتجنب رمي PptxEditException تحقق من خاصية HasDependingSlides للتخطيط أولاً. 2) يمكنك أيضًا استخدام الطريقة [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) لتبسيط الكود.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

نقل شريحة التخطيط من المجموعة إلى الموضع المحدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الهدف. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة التي سيتم نقلها. |