---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از تمام اسلایدهای طرح در ارائه.
type: docs
url: /fa/com.aspose.slides/globallayoutslidecollection/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

نمایشی از مجموعه تمام اسلایدهای طرح در ارائه را توصیف می‌کند. کلاس LayoutSlideCollection را گسترش می‌دهد با روش‌هایی برای افزودن/کلون‌سازی اسلایدهای طرح در زمینهٔ ادغام مجموعه‌های فردی اسلایدهای طرح master.

## Methods

| متد | توضیح |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | یک نسخه از اسلاید طرح مشخص‌شده را به ارائه اضافه می‌کند. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | یک نسخه از اسلاید طرح مشخص‌شده را به ارائه اضافه می‌کند. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | یک اسلاید طرح جدید را به ارائه اضافه می‌کند. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

یک نسخه از اسلاید طرح مشخص‌شده را به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای کلون‌سازی. |

--------------------

هنگام کلون‌سازی یک طرح بین ارائه‌های مختلف، master طرح نیز می‌تواند کلون شود تا قالب منبع حفظ شود. رجیستری داخلی برای ردیابی master‌های کلون‌شده به‌طور خودکار استفاده می‌شود تا از ایجاد چندین کلون از یک اسلاید master جلوگیری کند. کلون‌سازی دستی اسلایدهای master نه جلوگیری می‌شود و نه ثبت می‌شود.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

یک نسخه از اسلاید طرح مشخص‌شده را به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای کلون‌سازی. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلاید master برای یک طرح جدید. |

--------------------

1) طرح جدید با master تعریف شده در ارائه مقصد پیوند خواهد شد. بنابراین این مشابه کپی/چسباندن با گزینه "Use Destination Theme" در PowerPoint است. 2) مشابه این متد، متد [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) است که از طریق ویژگی ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) دسترسی می‌یابد.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

یک اسلاید طرح جدید را به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلاید master برای یک طرح جدید. |
| layoutType | byte | نوع طرح برای یک طرح جدید. انواع طرح پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. انواع دیگر طرح در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | نام برای یک طرح جدید. اگر نامی که ارسال شود قبلاً استفاده شده باشد، ArgumentException پرتاب می‌شود. اگر پارامتر null باشد، نام به‌صورت خودکار بر اساس نوع طرح ارسال‌شده تولید می‌شود (به عنوان مثال "Title Slide" یا "1_Title Slide"، "2_.." و غیره). |

--------------------

1) طرح اضافه‌شده برای مقدار SlideLayoutType.Custom از layoutType شامل هیچ placeholder و هیچ شکل‌گی نیست. 2) مشابه این متد، متد [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) است که از طریق ویژگی ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) دسترسی می‌یابد.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.