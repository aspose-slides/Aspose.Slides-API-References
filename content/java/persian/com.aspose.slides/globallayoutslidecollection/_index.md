---
title: GlobalLayoutSlideCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر مجموعه‌ای از تمام اسلایدهای طرح‌بندی در ارائه است.
type: docs
url: /fa/com.aspose.slides/globallayoutslidecollection/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

نمایانگر مجموعه‌ای از تمام اسلایدهای طرح‌بندی در ارائه است. کلاس LayoutSlideCollection را گسترش می‌دهد و شامل متدهایی برای افزودن/کلون کردن اسلایدهای طرح‌بندی در زمینه ترکیب مجموعه‌های فردی اسلایدهای طرح‌بندی مستر می‌باشد.
## متدها

| متد | توضیح |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | یک کپی از اسلاید طرح‌بندی مشخص‌شده را به ارائه اضافه می‌کند. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | یک کپی از اسلاید طرح‌بندی مشخص‌شده را به ارائه اضافه می‌کند. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | یک اسلاید طرح‌بندی جدید را به ارائه اضافه می‌کند. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


یک کپی از اسلاید طرح‌بندی مشخص‌شده را به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای کلون کردن. |

--------------------

هنگام کلون کردن یک طرح‌بندی بین ارائه‌های مختلف، master طرح‌بندی نیز می‌تواند برای حفظ قالب منبع کلون شود. رجیستری داخلی برای ردیابی masterهای کلون‌شده به‌صورت خودکار استفاده می‌شود تا از ایجاد کلون‌های متعدد از یک اسلاید master جلوگیری کند. کلون‌کردن دستی اسلایدهای master نه جلوگیری می‌شود و نه ثبت می‌گردد. |

**مقدار بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه شده.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


یک کپی از اسلاید طرح‌بندی مشخص‌شده را به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای کلون کردن. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلاید master برای یک طرح‌بندی جدید. |

--------------------

1) طرح‌بندی جدید با master تعریف‌شده در ارائه مقصد لینک خواهد شد. بنابراین این معادل عملیات copy/paste با گزینه "Use Destination Theme" در PowerPoint است. 2) معادل این متد، متد [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) است که از طریق ویژگی ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) دسترسی پیدا می‌کند. |

**مقدار بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه شده.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


یک اسلاید طرح‌بندی جدید را به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلاید master برای یک طرح‌بندی جدید. |
| layoutType | byte | نوع طرح‌بندی برای یک طرح‌بندی جدید. انواع طرح‌بندی پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. سایر انواع طرح‌بندی در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | نام برای یک طرح‌بندی جدید. اگر نام ارائه‌شده قبلاً استفاده شده باشد ArgumentException پرتاب می‌شود. اگر پارامتر null باشد، نام به‌صورت خودکار بر اساس نوع طرح‌بندی ارائه‌شده تولید می‌شود (به عنوان مثال "Title Slide" یا "1_Title Slide", "2_.." و غیره). |

--------------------

1) طرح‌بندی اضافه شده برای مقدار SlideLayoutType.Custom از layoutType شامل هیچ جای‌نگهدارنده و هیچ شکلی نیست. 2) معادل این متد، متد [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) است که از طریق ویژگی ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) دسترسی پیدا می‌کند. |

**مقدار بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه شده.