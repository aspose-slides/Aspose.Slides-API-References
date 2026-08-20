---
title: IGlobalLayoutSlideCollection
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل مجموعة من جميع شرائح التخطيط في العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/igloballayoutslidecollection/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

يمثل مجموعة من جميع شرائح التخطيط في العرض التقديمي. يمتد ILayoutSlideCollection الواجهة مع طرق لإضافة/استنساخ شرائح التخطيط في سياق توحيد المجموعات الفردية لشرائح تخطيط الماستر.

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | يضيف نسخة من شريحة تخطيط محددة إلى العرض التقديمي. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | يضيف نسخة من شريحة تخطيط محددة إلى العرض التقديمي. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | يضيف شريحة تخطيط جديدة إلى العرض التقديمي. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

يضيف نسخة من شريحة تخطيط محددة إلى العرض التقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة للاستنساخ.

--------------------

عند استنساخ تخطيط بين عروض تقديمية مختلفة يمكن استنساخ ماستر التخطيط أيضًا للحفاظ على تنسيق المصدر. يُستخدم السجل الداخلي لتتبع الماسترات المستنساخة تلقائيًا لمنع إنشاء نسخ متعددة من نفس شريحة الماستر. الاستنساخ اليدوي لشرائح الماستر لن يتم منعه ولا يُسجل.

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مضافة.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

يضيف نسخة من شريحة تخطيط محددة إلى العرض التقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة للاستنساخ. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | شريحة الماستر لتخطيط جديد.

--------------------

سيتم ربط التخطيط الجديد بالماستر المحدد في العرض التقديمي الوجهة. لذا هذا هو تماثل النسخ/اللصق مع خيار "Use Destination Theme" في PowerPoint.

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مضافة.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

يضيف شريحة تخطيط جديدة إلى العرض التقديمي.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | شريحة الماستر لتخطيط جديد. |
| layoutType | byte | نوع التخطيط لتخطيط جديد. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. أنواع التخطيط الأخرى غير مدعومة الآن: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | اسم للتخطيط الجديد. إذا كان الاسم الممرّر مستخدمًا بالفعل سيتم إلقاء ArgumentException. إذا تم تمرير معامل null فسيتم إنشاء الاسم تلقائيًا وفقًا لنوع التخطيط الممرّر (مثال "Title Slide" أو "1_Title Slide"، "2_.."، إلخ). |

--------------------

1) تم إضافة تخطيط للقيمة SlideLayoutType.Custom من layoutType لا يحتوي على نائبات ومجسمات. 2) تماثل هذه الطريقة هو الطريقة [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) التي يتم الوصول إليها بخصيصة ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مضافة.