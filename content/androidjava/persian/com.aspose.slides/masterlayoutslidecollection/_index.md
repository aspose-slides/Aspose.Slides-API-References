---
title: MasterLayoutSlideCollection
second_title: مرجع API جاوا برای Aspose.Slides برای Android
description: نمایشگر مجموعه‌ای از تمام اسلایدهای طرح‌بندی اسلاید اصلی تعریف‌شده است.
type: docs
url: /fa/com.aspose.slides/masterlayoutslidecollection/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

نمایشگر مجموعه‌ای از تمام اسلایدهای طرح‌بندی اسلایدهای اصلی تعریف‌شده است. کلاس LayoutSlideCollection را گسترش می‌دهد و شامل متدهایی برای افزودن/درج/حذف/کلون/تغییر ترتیب اسلایدهای طرح‌بندی در زمینه‌ی مجموعه‌های فردی اسلایدهای طرح‌بندی اصلی می‌باشد.
## متدها

| متد | توضیح |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | یک کپی از اسلاید طرح‌بندی مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | یک کپی از اسلاید طرح‌بندی مشخص‌شده را در موقعیت مشخصی از مجموعه درج می‌کند. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | یک اسلاید طرح‌بندی جدید را به انتهای مجموعه اضافه می‌کند. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | یک اسلاید طرح‌بندی جدید را در موقعیت مشخصی از مجموعه درج می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر موجود در اندیس مشخص‌شده از مجموعه را حذف می‌کند. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | اسلاید طرح‌بندی را از مجموعه به موقعیت مشخص‌شده منتقل می‌کند. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

یک کپی از اسلاید طرح‌بندی مشخص‌شده را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای کلون کردن. |
--------------------

1) طرح‌بندی جدید با اسلاید اصلی والد برای این مجموعه اسلایدهای طرح‌بندی ارتباط خواهد یافت. بنابراین این مشابه کپی/پیست با گزینه «Use Destination Theme» در PowerPoint است. 2) مشابه این متد، متد [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) است که از طریق خصوصیت ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) قابل دسترسی است. |

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

یک کپی از اسلاید طرح‌بندی مشخص‌شده را در موقعیت مشخصی از مجموعه درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس اسلاید جدید. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای کلون کردن. |
--------------------

طرح‌بندی جدید با اسلاید اصلی والد برای این مجموعه اسلایدهای طرح‌بندی ارتباط خواهد یافت. بنابراین این مشابه کپی/پیست با گزینه «Use Destination Theme» در PowerPoint است. |

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید درج‌شده.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

یک اسلاید طرح‌بندی جدید را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| layoutType | byte | نوع طرح‌بندی برای یک طرح‌بندی جدید. انواع طرح‌بندی پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | نام برای یک طرح‌بندی جدید. اگر نام داده‌شده قبلاً استفاده شده باشد ArgumentException پرتاب می‌شود. اگر پارامتر null باشد، نام به‌صورت خودکار بر اساس نوع طرح‌بندی داده‌شده تولید می‌شود (به عنوان مثال «Title Slide» یا «1_Title Slide»، «2_..» و غیره). |
--------------------

1) طرح‌بندی اضافه‌شده برای مقدار SlideLayoutType.Custom از layoutType شامل هیچ جای‌گیرنده‌ای و هیچ شکلی نیست. 2) مشابه این متد، متد [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) است که از طریق خصوصیت ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) قابل دسترسی است. |

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

یک اسلاید طرح‌بندی جدید را در موقعیت مشخصی از مجموعه درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس اسلاید جدید. |
| layoutType | byte | نوع طرح‌بندی برای یک طرح‌بندی جدید. انواع طرح‌بندی پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | نام برای یک طرح‌بندی جدید. اگر نام داده‌شده قبلاً استفاده شده باشد ArgumentException پرتاب می‌شود. اگر پارامتر null باشد، نام به‌صورت خودکار بر اساس نوع طرح‌بندی داده‌شده تولید می‌شود (به عنوان مثال «Title Slide» یا «1_Title Slide»، «2_..» و غیره). |
--------------------

طرح‌بندی درج‌شده برای مقدار SlideLayoutType.Custom از layoutType شامل هیچ جای‌گیرنده‌ای و هیچ شکلی نیست. |

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید درج‌شده.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصر موجود در اندیس مشخص‌شده از مجموعه را حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه عنصر برای حذف. |
--------------------

1) برای جلوگیری از پرتاب PptxEditException، قبل از آن خصوصیت HasDependingSlides طرح‌بندی را بررسی کنید. 2) همچنین می‌توانید از متد [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) برای ساده‌سازی کد استفاده کنید. |
### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

اسلاید طرح‌بندی را از مجموعه به موقعیت مشخص‌شده منتقل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس هدف. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای انتقال. |