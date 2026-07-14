---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایشی از مجموعه‌ای از تمام اسلایدهای طرح‌بندی در ارائه.
type: docs
url: /fa/com.aspose.slides/igloballayoutslidecollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

نمایشی از مجموعه‌ای از تمام اسلایدهای طرح‌بندی در ارائه است. این رابط ILayoutSlideCollection را که شامل متدهایی برای افزودن/کلون کردن اسلایدهای طرح‌بندی در زمینه اتحاد مجموعه‌های فردی اسلایدهای طرح‌بندی مستر (master) است، گسترش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | یک کپی از اسلاید طرح‌بندی مشخص شده را به ارائه اضافه می‌کند. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | یک کپی از اسلاید طرح‌بندی مشخص شده را به ارائه اضافه می‌کند. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | یک اسلاید طرح‌بندی جدید را به ارائه اضافه می‌کند. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

یک کپی از اسلاید طرح‌بندی مشخص شده را به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلایدی که باید کلون شود. |

--------------------

هنگامی که یک طرح‌بندی را بین ارائه‌های مختلف کلون می‌کنید، می‌توان مستر طرح‌بندی آن را نیز کلون کرد تا قالب‌بندی منبع حفظ شود. یک رجیستری داخلی برای ردیابی مسترهای کلون‌شده به‌صورت خودکار استفاده می‌شود تا از ایجاد چندین کلون از همان اسلاید مستر جلوگیری شود. کلون کردن دستی اسلایدهای مستر نه جلوگیری می‌شود نه ثبت می‌شود. 

**مقدار بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Added slide.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

یک کپی از اسلاید طرح‌بندی مشخص شده را به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلایدی که باید کلون شود. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | مستر اسلاید برای یک طرح‌بندی جدید. |

--------------------

طرح‌بندی جدید با مستر تعریف‌شده در ارائه مقصد لینک می‌شود. بنابراین این روش معادل عملیات copy/paste با گزینه «Use Destination Theme» در PowerPoint است. 

**مقدار بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Added slide.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

یک اسلاید طرح‌بندی جدید را به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | مستر اسلاید برای یک طرح‌بندی جدید. |
| layoutType | byte | نوع طرح‌بندی برای یک طرح‌بندی جدید. انواع طرح‌بندی پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. سایر انواع طرح‌بندی در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | نام برای یک طرح‌بندی جدید. اگر نامی که گذارده شده قبلاً استفاده شده باشد، ArgumentException صادر می‌شود. اگر مقدار null گذارده شود، نام به‌صورت خودکار بر اساس نوع طرح‌بندی (مثلاً "Title Slide" یا "1_Title Slide"، "2_.." و غیره) تولید می‌شود. |

--------------------

1) طرح‌بندی اضافه‌شده برای مقدار SlideLayoutType.Custom از layoutType شامل هیچ محل-متن و هیچ شکلی نیست. 2) معادل این متد، متد [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) است که با ویژگی ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) قابل دسترسی است. 

**مقدار بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Added slide.