---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides برای Java مرجع API
description: یک مجموعه از تمام اسلایدهای طرح‌بندی در ارائه را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/igloballayoutslidecollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

یک مجموعه از تمام اسلایدهای طرح‌بندی در ارائه را نمایش می‌دهد. رابط ILayoutSlideCollection را با متدهایی برای افزودن/کلون کردن اسلایدهای طرح‌بندی در زمینهٔ ادغام مجموعه‌های جداگانهٔ اسلایدهای طرح‌بندی مستر گسترش می‌دهد.
## متدها

| متد | توضیحات |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | یک نسخه از اسلاید طرح‌بندی مشخص را به ارائه اضافه می‌کند. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | یک نسخه از اسلاید طرح‌بندی مشخص را به ارائه اضافه می‌کند. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | یک اسلاید طرح‌بندی جدید به ارائه اضافه می‌کند. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

یک نسخه از اسلاید طرح‌بندی مشخص را به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای کلون کردن. |

--------------------

هنگام کلون کردن یک طرح‌بندی بین ارائه‌های مختلف، می‌توان مستر طرح‌بندی را نیز کلون کرد تا قالب‌بندی منبع حفظ شود. رجیستری داخلی برای پیگیری مسترهای کلون‌شده به‌صورت خودکار استفاده می‌شود تا از ایجاد کلون‌های متعدد برای یک اسلاید مستر جلوگیری کند. کلون دستی اسلایدهای مستر هم مسدود نمی‌شود و هم ثبت نمی‌شود.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

یک نسخه از اسلاید طرح‌بندی مشخص را به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای کلون کردن. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلاید مستر برای یک طرح‌بندی جدید. |

--------------------

طرح‌بندی جدید با مستر تعریف‌شده در ارائه مقصد لینک خواهد شد. بنابراین این معادل عملیات copy/paste با گزینه «Use Destination Theme» در PowerPoint است.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

یک اسلاید طرح‌بندی جدید به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | اسلاید مستر برای یک طرح‌بندی جدید. |
| layoutType | byte | نوع طرح‌بندی برای یک طرح‌بندی جدید. انواع طرح‌بندی پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. سایر انواع طرح‌بندی در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | نام برای یک طرح‌بندی جدید. اگر نام وارد شده قبلاً استفاده شده باشد، ArgumentException پرتاب می‌شود. اگر پارامتر null باشد، نام به‌صورت خودکار بر اساس نوع طرح‌بندی ارائه‌شده تولید می‌شود (مثلاً «Title Slide» یا «1_Title Slide»، «2_..» و غیره). |

--------------------

1) طرح‌بندی اضافه‌شده برای مقدار SlideLayoutType.Custom از layoutType حاوی هیچ جای‌نگهدار و هیچ شکل‌ای نیست. 2) معادل این متد، متد [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) است که با ویژگی ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) دسترسی پیدا می‌شود.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.