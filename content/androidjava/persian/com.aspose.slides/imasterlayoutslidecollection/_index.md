---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از تمام اسلایدهای طرح‌بندی تعریف‌شده برای اسلاید اصلی است.
type: docs
url: /fa/com.aspose.slides/imasterlayoutslidecollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

نمایانگر مجموعه‌ای از تمام اسلایدهای طرح‌بندی تعریف‌شده برای اسلاید اصلی است. رابط ILayoutSlideCollection را با متدهایی برای افزودن/درج/حذف/کلون کردن اسلایدهای طرح‌بندی در زمینه مجموعه‌های جداگانه اسلایدهای طرح‌بندی اسلاید اصلی گسترش می‌دهد.

## متدها

| متد | توضیح |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | یک کپی از اسلاید طرح‌بندی مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | کپی‌ای از اسلاید طرح‌بندی مشخص‌شده را در موقعیت مشخص شده در مجموعه درج می‌کند. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | یک اسلاید طرح‌بندی جدید را به انتهای مجموعه اضافه می‌کند. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | یک اسلاید طرح‌بندی جدید را در موقعیت مشخص شده در مجموعه درج می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصری را که در شاخص مشخص شده در مجموعه قرار دارد حذف می‌کند. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | اسلاید طرح‌بندی را از مجموعه به موقعیت مشخص‌شده منتقل می‌کند. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

یک کپی از اسلاید طرح‌بندی مشخص‌شده را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای کلون کردن. |

--------------------

1) طرح‌بندی جدید با اسلاید اصلی والد برای این مجموعه اسلایدهای طرح‌بندی پیوند خواهد شد. بنابراین این معادل عملیات کپی/چسباندن با گزینه "Use Destination Theme" در PowerPoint است. 2) معادل این متد، متد [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) است که از طریق ویژگی [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) قابل دسترسی می‌باشد.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

کپی‌ای از اسلاید طرح‌بندی مشخص‌شده را در موقعیت مشخص شده در مجموعه درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص اسلاید جدید. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای کلون کردن. |

--------------------

طرح‌بندی جدید با اسلاید اصلی والد برای این مجموعه اسلایدهای طرح‌بندی پیوند خواهد شد. بنابراین این معادل عملیات کپی/چسباندن با گزینه "Use Destination Theme" در PowerPoint است.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید درج‌شده.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

یک اسلاید طرح‌بندی جدید را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| layoutType | byte | نوع طرح‌بندی برای یک طرح‌بندی جدید. انواع طرح‌بندی پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. سایر انواع طرح‌بندی در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | نام برای یک طرح‌بندی جدید. اگر نام ارائه‌شده قبلاً استفاده شده باشد ArgumentException پرتاب می‌شود. اگر پارامتر null باشد، نام به‌صورت خودکار بر اساس نوع طرح‌بندی ارائه‌شده تولید می‌شود (برای مثال "Title Slide" یا "1_Title Slide", "2_.." و غیره). |

--------------------

1) طرح‌بندی اضافه‌شده برای مقدار SlideLayoutType.Custom از layoutType هیچ جایگزین‌کننده‌ای و هیچ شکلی ندارد. 2) معادل این متد، متد [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) است که از طریق ویژگی [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) قابل دسترسی می‌باشد.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

یک اسلاید طرح‌بندی جدید را در موقعیت مشخص شده در مجموعه درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص اسلاید جدید. |
| layoutType | byte | نوع طرح‌بندی برای یک طرح‌بندی جدید. انواع طرح‌بندی پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. سایر انواع طرح‌بندی در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | نام برای یک طرح‌بندی جدید. اگر نام ارائه‌شده قبلاً استفاده شده باشد ArgumentException پرتاب می‌شود. اگر پارامتر null باشد، نام به‌صورت خودکار بر اساس نوع طرح‌بندی ارائه‌شده تولید می‌شود (برای مثال "Title Slide" یا "1_Title Slide", "2_.." و غیره). |

--------------------

طرح‌بندی درج‌شده برای مقدار SlideLayoutType.Custom از layoutType هیچ جایگزین‌کننده‌ای و هیچ شکلی ندارد.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید درج‌شده.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصری را که در شاخص مشخص شده در مجموعه قرار دارد حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر-پایه عنصری که باید حذف شود. |

--------------------

1) برای جلوگیری از پرتاب PptxEditException پیش از آن، ویژگی HasDependingSlides طرح‌بندی را بررسی کنید. 2) همچنین می‌توانید از متد [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) برای ساده‌سازی کد استفاده کنید.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

اسلاید طرح‌بندی را از مجموعه به موقعیت مشخص‌شده منتقل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص هدف. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای انتقال. |