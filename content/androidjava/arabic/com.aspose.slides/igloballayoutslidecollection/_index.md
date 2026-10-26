---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة جميع شرائح التخطيط في العرض التقديمي.
type: docs
url: /ar/com.aspose.slides/igloballayoutslidecollection/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

يمثل مجموعة جميع شرائح التخطيط في العرض التقديمي. يمدّ واجهة ILayoutSlideCollection بالطرق لإضافة/استنساخ شرائح التخطيط في سياق توحيد مجموعات الشرائح الماستر الفردية.

## الطرق

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

**العوامل:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة المراد استنساخها. |
|  |  |  |

--------------------

When cloning a layout between different presentations layout's master can be cloned too to keep source formatting. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. |

**الإرجاع:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مضافة.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

يضيف نسخة من شريحة تخطيط محددة إلى العرض التقديمي.

**العوامل:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | الشريحة المراد استنساخها. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | شريحة الماستر للتخطيط الجديد. |
|  |  |  |

--------------------

New layout will be linked with defined master in destination presentation. So this is analogue of copy/paste with "Use Destination Theme" option in PowerPoint. |

**الإرجاع:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مضافة.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

يضيف شريحة تخطيط جديدة إلى العرض التقديمي.

**العوامل:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | شريحة الماستر للتخطيط الجديد. |
| layoutType | byte | نوع التخطيط لشريحة تخطيط جديدة. أنواع التخطيط المدعومة: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. أنواع التخطيط الأخرى غير مدعومة حالياً: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | اسم للتخطيط الجديد. إذا كان الاسم الممرّر مستخدمًا مسبقًا سيتم إلقاء استثناء ArgumentException. إذا تم تمرير معلمة بقيمة null فسيتم توليد الاسم تلقائيًا بناءً على نوع التخطيط الممرّر (على سبيل المثال "Title Slide" أو "1_Title Slide"، "2_.."، إلخ). |
|  |  |  |

--------------------

1) تم إضافة تخطيط للقيمة SlideLayoutType.Custom من layoutType لا يحتوي على عناصر نائبة ولا أشكال. 2) نظير هذه الطريقة هو الطريقة [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) التي يتم الوصول إليها عبر خاصية ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**الإرجاع:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - شريحة مضافة.