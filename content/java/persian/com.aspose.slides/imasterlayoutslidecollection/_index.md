---
title: IMasterLayoutSlideCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش‌دهندهٔ مجموعه‌ای از تمام اسلایدهای طرح‌بندی اسلاید اصلی تعریف‌شده.
type: docs
url: /fa/com.aspose.slides/imasterlayoutslidecollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

نمایش‌دهندهٔ مجموعه‌ای از تمام اسلایدهای طرح‌بندی اسلایدهای تعریف‌شدهٔ اسلاید اصلی است. این کلاس رابط ILayoutSlideCollection را گسترش می‌دهد و شامل متدهایی برای افزودن/درج/حذف/کلون کردن اسلایدهای طرح‌بندی در زمینهٔ مجموعه‌های فردی اسلایدهای طرح‌بندی اسلاید اصلی می‌باشد.
## متدها

| متد | توضیح |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | یک کپی از اسلاید طرح‌بندی مشخص‌شده را به انتهای مجموعه اضافه می‌کند. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | یک کپی از اسلاید طرح‌بندی مشخص‌شده را در موقعیت مشخص‌شدهٔ مجموعه درج می‌کند. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | یک اسلاید طرح‌بندی جدید را به انتهای مجموعه اضافه می‌کند. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | یک اسلاید طرح‌بندی جدید را در موقعیت مشخص‌شدهٔ مجموعه درج می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر را در ایندکس مشخص‌شدهٔ مجموعه حذف می‌کند. |
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

1) طرح‌بندی جدید با اسلاید اصلی والد برای این مجموعهٔ اسلایدهای طرح‌بندی مرتبط خواهد شد. بنابراین این معادل عملیات copy/paste با گزینهٔ «Use Destination Theme» در PowerPoint است. 2) معادل این متد، متد [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) است که از طریق ویژگی [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) قابل دسترسی است.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

یک کپی از اسلاید طرح‌بندی مشخص‌شده را در موقعیت مشخص‌شدهٔ مجموعه درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای کلون کردن. |

--------------------

طرح‌بندی جدید با اسلاید اصلی والد برای این مجموعهٔ اسلایدهای طرح‌بندی مرتبط خواهد شد. بنابراین این معادل عملیات copy/paste با گزینهٔ «Use Destination Theme» در PowerPoint است.

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
| layoutName | java.lang.String | نام برای یک طرح‌بندی جدید. اگر نام ارائه‌شده قبلاً استفاده شده باشد، ArgumentException پرتاب خواهد شد. اگر پارامتر null پاس داده شود، نام به‌طور خودکار بر اساس نوع طرح‌بندی ارائه‌شده تولید می‌شود (به عنوان مثال «Title Slide» یا «1\_Title Slide»، «2\_..» و غیره). |

--------------------

1) طرح‌بندی اضافه‌شده برای مقدار SlideLayoutType.Custom از layoutType شامل هیچ مکان‌ثبت‌کننده و هیچ شکلی نمی‌شود. 2) معادل این متد، متد [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) است که از طریق ویژگی [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) قابل دسترسی است.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید اضافه‌شده.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

یک اسلاید طرح‌بندی جدید را در موقعیت مشخص‌شدهٔ مجموعه درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس اسلاید جدید. |
| layoutType | byte | نوع طرح‌بندی برای یک طرح‌بندی جدید. انواع طرح‌بندی پشتیبانی‌شده: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. سایر انواع طرح‌بندی در حال حاضر پشتیبانی نمی‌شوند: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | نام برای یک طرح‌بندی جدید. اگر نام ارائه‌شده قبلاً استفاده شده باشد، ArgumentException پرتاب خواهد شد. اگر پارامتر null پاس داده شود، نام به‌طور خودکار بر اساس نوع طرح‌بندی ارائه‌شده تولید می‌شود (به عنوان مثال «Title Slide» یا «1\_Title Slide»، «2\_..» و غیره). |

--------------------

طرح‌بندی درج‌شده برای مقدار SlideLayoutType.Custom از layoutType شامل هیچ مکان‌ثبت‌کننده و هیچ شکلی نیست.

**بازگشت:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - اسلاید درج‌شده.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصر را در ایندکس مشخص‌شدهٔ مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-مبنا برای عنصری که باید حذف شود. |

--------------------

1) برای جلوگیری از پرتاب PptxEditException، پیش از عملیات ویژگی HasDependingSlides طرح‌بندی را بررسی کنید. 2) می‌توانید از متد [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) نیز برای ساده‌سازی کد استفاده کنید.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

اسلاید طرح‌بندی را از مجموعه به موقعیت مشخص‌شده منتقل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس هدف. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | اسلاید برای جابه‌جایی. |