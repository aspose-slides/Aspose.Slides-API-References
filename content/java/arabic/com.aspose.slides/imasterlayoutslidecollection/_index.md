---
title: IMasterLayoutSlideCollection
second_title: مرجع API لـ Aspose.Slides لل Java
description: يمثل مجموعة من جميع شرائح التخطيط للماستر المحدد.
type: docs
url: /ar/com.aspose.slides/imasterlayoutslidecollection/
---
**جميع الواجهات المُنفذة:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

يمثل مجموعة من جميع شرائح التخطيط للماستر المحدد. يمتد من واجهة ILayoutSlideCollection مع طرق لإضافة/إدراج/حذف/استنساخ شرائح التخطيط ضمن مجموعات شرائح التخطيط الخاصة بالماستر.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | يدخل نسخة من شريحة تخطيط محددة إلى الموضع المحدد في المجموعة. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | يضيف شريحة تخطيط جديدة إلى نهاية المجموعة. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | يدخل شريحة تخطيط جديدة إلى الموضع المحدد في المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل العنصر في الفهرس المحدد من المجموعة. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | ينقل شريحة التخطيط من المجموعة إلى الموضع المحدد. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


يضيف نسخة من شريحة تخطيط محددة إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة المراد استنساخها. |

--------------------

1) سيتم ربط التخطيط الجديد بالماستر الرئيسي لمجموعة شرائح التخطيط هذه. لذا هو مشابه لعملية النسخ/اللصق مع خيار "Use Destination Theme" في PowerPoint. 2) نظير هذه الطريقة هو الطريقة [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) التي يمكن الوصول إليها عبر الخاصية [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مضافة.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```


يدخل نسخة من شريحة تخطيط محددة إلى الموضع المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة المراد استنساخها. |

--------------------

تم ربط التخطيط الجديد بالماستر الرئيسي لمجموعة شرائح التخطيط هذه. لذا هو مشابه لعملية النسخ/اللصق مع خيار "Use Destination Theme" في PowerPoint.

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مُدرجة.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```


يضيف شريحة تخطيط جديدة إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| layoutType | byte | نوع التخطيط لشريحة تخطيط جديدة. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. الأنواع الأخرى غير مدعومة الآن: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | اسم التخطيط الجديد. إذا كان الاسم المُمرّر مستخدمًا بالفعل سيتم رمي استثناء ArgumentException. إذا تم تمرير قيمة null فسيتم توليد الاسم تلقائيًا بناءً على نوع التخطيط المُمرّر (على سبيل المثال "Title Slide" أو "1\_Title Slide" أو "2\_.."، إلخ). |

--------------------

1) تم إضافة تخطيط للقيمة SlideLayoutType.Custom من layoutType ولا يحتوي على نواقل نائبة ولا أشكال. 2) نظير هذه الطريقة هو الطريقة [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) التي يمكن الوصول إليها عبر الخاصية [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مضافة.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```


يدخل شريحة تخطيط جديدة إلى الموضع المحدد في المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس الشريحة الجديدة. |
| layoutType | byte | نوع التخطيط لشريحة تخطيط جديدة. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. الأنواع الأخرى غير مدعومة الآن: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | اسم التخطيط الجديد. إذا كان الاسم المُمرّر مستخدمًا بالفعل سيتم رمي استثناء ArgumentException. إذا تم تمرير قيمة null فسيتم توليد الاسم تلقائيًا بناءً على نوع التخطيط المُمرّر (على سبيل المثال "Title Slide" أو "1\_Title Slide" أو "2\_.."، إلخ). |

--------------------

تم إدراج تخطيط للقيمة SlideLayoutType.Custom من layoutType ولا يحتوي على نواقل نائبة ولا أشكال.

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مُدرجة.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


يزيل العنصر في الفهرس المحدد من المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الصفري للعنصر المراد إزالته. |

--------------------

1) لتجنب رمي استثناء PptxEditException، يجب فحص خاصية HasDependingSlides للتخطيط مسبقًا. 2) يمكنك أيضًا استخدام الطريقة [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) لتبسيط الكود.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```


ينقل شريحة التخطيط من المجموعة إلى الموضع المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس الهدف. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة المراد نقلها. |