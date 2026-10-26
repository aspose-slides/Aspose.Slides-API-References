---
title: MasterLayoutSlideCollection
second_title: مرجع API Aspose.Slides برای Java
description: مجموعه‌ای از تمام اسلایدهای طرح‌بندی اسلاید اصلی تعریف‌شده را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/masterlayoutslidecollection/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

یک مجموعه از تمام اسلایدهای طرح‌بندی اسلاید اصلی تعریف‌شده را نشان می‌دهد. کلاس LayoutSlideCollection را گسترش می‌دهد و شامل روش‌های افزودن/درج/حذف/کلون/تغییر ترتیب اسلایدهای طرح‌بندی در زمینه مجموعه‌های فردی اسلایدهای طرح‌بندی استاد است.
## متدها

| متد | توضیح |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | یک کپی از اسلاید طرح‌بندی مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | یک کپی از اسلاید طرح‌بندی مشخص‌شده را در موقعیت تعیین‌شده‌ی مجموعه درج می‌کند. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | یک اسلاید طرح‌بندی جدید را به انتهای مجموعه اضافه می‌کند. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | یک اسلاید طرح‌بندی جدید را در موقعیت تعیین‌شده‌ی مجموعه درج می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصری را که در ایندکس مشخص‌شده‌ی مجموعه قرار دارد حذف می‌کند. |
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

1) طرح جدید با اسلاید اصلی والد برای این مجموعه اسلایدهای طرح‌بندی لینک خواهد شد. بنابراین این مشابه عمل کپی/چسباندن با گزینه "Use Destination Theme" در PowerPoint است. 2) معادل این متد، متد [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) است که با ویژگی ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) قابل دسترسی می‌باشد.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

یک کپی از اسلاید طرح‌بندی مشخص‌شده را در موقعیت تعیین‌شده‌ی مجموعه درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای کلون کردن. |

--------------------

طرح جدید با اسلاید اصلی والد برای این مجموعه اسلایدهای طرح‌بندی لینک خواهد شد. بنابراین این مشابه عمل کپی/چسباندن با گزینه "Use Destination Theme" در PowerPoint است.

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
| layoutType | byte | نوع طرح برای یک طرح جدید. نوع‌های طرح پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | نام برای یک طرح جدید. اگر نام داده‌شده قبلاً استفاده شده باشد، ArgumentException پرتاب می‌شود. اگر پارامتر null باشد، نام به‌صورت خودکار با توجه به نوع طرح داده‌شده تولید می‌شود (برای مثال "Title Slide" یا "1_Title Slide"، "2_.."، و غیره). |

--------------------

1) طرح افزوده‌شده برای مقدار SlideLayoutType.Custom از layoutType حاوی هیچ جای‌گذاری و هیچ شکلی نیست. 2) معادل این متد، متد [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) است که با ویژگی ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) قابل دسترسی می‌باشد.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

یک اسلاید طرح‌بندی جدید را در موقعیت تعیین‌شده‌ی مجموعه درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| layoutType | byte | نوع طرح برای یک طرح جدید. نوع‌های طرح پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | نام برای یک طرح جدید. اگر نام داده‌شده قبلاً استفاده شده باشد، ArgumentException پرتاب می‌شود. اگر پارامتر null باشد، نام به‌صورت خودکار با توجه به نوع طرح داده‌شده تولید می‌شود (برای مثال "Title Slide" یا "1_Title Slide"، "2_.."، و غیره). |

--------------------

طرح درج‌شده برای مقدار SlideLayoutType.Custom از layoutType حاوی هیچ جای‌گذاری و هیچ شکلی نیست.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید درج‌شده.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عنصری را که در ایندکس مشخص‌شده‌ی مجموعه قرار دارد حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنی عنصر برای حذف. |

--------------------

1) برای جلوگیری از پرتاب PptxEditException، پیش از آن ویژگی HasDependingSlides طرح را بررسی کنید. 2) می‌توانید برای ساده‌سازی کد از متد [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) نیز استفاده کنید.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

اسلاید طرح‌بندی را از مجموعه به موقعیت مشخص‌شده منتقل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس هدف. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای انتقال. |