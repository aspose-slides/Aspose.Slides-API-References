---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من جميع شرائح التخطيط في العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/globallayoutslidecollection/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

يمثل مجموعة من جميع شرائح التخطيط في العرض التقديمي. يمتد من فئة LayoutSlideCollection مع طرق لإضافة/استنساخ شرائح التخطيط في سياق توحيد المجموعات الفردية لشرائح التخطيط الخاصة بالماستر.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | يضيف نسخة من شريحة تخطيط معينة إلى العرض التقديمي. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | يضيف نسخة من شريحة تخطيط معينة إلى العرض التقديمي. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | يضيف شريحة تخطيط جديدة إلى العرض التقديمي. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

يضيف نسخة من شريحة تخطيط معينة إلى العرض التقديمي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة للاستنساخ. |

--------------------

عند استنساخ تخطيط بين عروض تقديمية مختلفة يمكن استنساخ ماستر التخطيط أيضًا للحفاظ على تنسيق المصدر. يتم استخدام سجل داخلي لتتبع الماسترز المستنسخة تلقائيًا لمنع إنشاء مستنسخات متعددة لنفس شريحة الماستر. لن يتم منع أو تسجيل الاستنساخ اليدوي لشرائح الماستر.

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مضافة.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

يضيف نسخة من شريحة تخطيط معينة إلى العرض التقديمي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة للاستنساخ. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | شريحة الماستر لتخطيط جديد. |

--------------------

1) سيتم ربط التخطيط الجديد بالماستر المحدد في العرض التقديمي الوجهة. لذا فإن هذا يُعادل عملية النسخ/اللصق مع خيار "Use Destination Theme" في PowerPoint. 2) نظير هذه الطريقة هو الطريقة [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) التي يتم الوصول إليها عبر خاصية ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مضافة.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

يضيف شريحة تخطيط جديدة إلى العرض التقديمي.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | شريحة الماستر لتخطيط جديد. |
| layoutType | byte | نوع التخطيط لتخطيط جديد. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. الأنواع الأخرى غير المدعومة الآن: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | اسم لتخطيط جديد. إذا كان الاسم الممرّر مستخدمًا بالفعل سيتم إثارة الاستثناء ArgumentException. إذا تم تمرير معامل null فسيتم توليد الاسم تلقائيًا بناءً على نوع التخطيط الممرّر (على سبيل المثال "Title Slide" أو "1\_Title Slide"، "2\_.."، إلخ). |

--------------------

1) يحتوي التخطيط المضاف للقيمة SlideLayoutType.Custom من layoutType على لا نائبة ولا أشكال. 2) نظير هذه الطريقة هو الطريقة [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) التي يتم الوصول إليها عبر خاصية ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**القيمة المرجعة:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مضافة.