---
title: SlideUtil
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: روش‌هایی ارائه می‌دهد که به جستجوی اشکال و متن در یک ارائه کمک می‌کنند.
type: docs
url: /fa/com.aspose.slides/slideutil/
---
**ارث‌بری:**
java.lang.Object
```
public class SlideUtil
```

روش‌هایی که به جستجوی اشکال و متن در یک ارائه کمک می‌کنند.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | یافتن شکل با متن جایگزین در یک ارائه PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | یافتن شکل با متن جایگزین روی یک اسلاید در یک ارائه PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | جستجوی تمام اشکال در اسلاید مشخص شده که با نوع جایگزین داده شده مطابقت دارند. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | تغییر مکان تمام اشکال روی اسلاید. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | تغییر مکان اشکال انتخاب شده روی اسلاید. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | تغییر مکان تمام اشکال در داخل شکل گروهی. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | تغییر مکان اشکال انتخاب شده در داخل شکل گروهی. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | یافتن و جایگزینی متن در ارائه با قالب داده شده |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | یافتن و جایگزینی متن در ارائه با قالب داده شده |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | تمام قاب‌های متن را در یک اسلاید از ارائه PPTX برمی‌گرداند. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | تمام قاب‌های متنی را در اسلاید مشخص شده که متن داده شده را شامل می‌شوند برمی‌گرداند. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | تمام قاب‌های متن در یک ارائه PPTX را برمی‌گرداند. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | یک قالب فایل منبع را به [SaveFormat](../../com.aspose.slides/saveformat) متناظر تبدیل می‌کند. |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```


### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```


یافتن شکل با متن جایگزین در یک ارائه PPTX.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه اسکن شده. |
| altText | java.lang.String | متن جایگزین یک شکل. |

**بازگشت:**
[IShape](../../com.aspose.slides/ishape) - Shape یا null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```


یافتن شکل با متن جایگزین روی یک اسلاید در یک ارائه PPTX.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | اسلاید اسکن شده. |
| altText | java.lang.String | متن جایگزین یک شکل. |

**بازگشت:**
[IShape](../../com.aspose.slides/ishape) - Shape یا null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```


جستجوی تمام اشکال در اسلاید مشخص شده که با نوع جایگزین داده شده مطابقت دارند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | اسلاید برای جستجوی اشکال. |
| placeholderType | byte | نوع جایگزینی که برای فیلتر کردن اشکال استفاده می‌شود. |

**بازگشت:**
com.aspose.slides.IShape[] - آرایه‌ای از [IShape](../../com.aspose.slides/ishape) که با نوع جایگزین مشخص شده مطابقت دارند.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```


تغییر مکان تمام اشکال روی اسلاید. اشکال را نسبت به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر تراز می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, true, pres.getSlides().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alignmentType | int | تعیین می‌کند کدام نوع تراز اعمال شود. |
| alignToSlide | boolean | اگر true باشد، اشکال نسبت به لبه‌های اسلاید تراز می‌شوند. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | اسلاید والد. |

### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```


تغییر مکان اشکال انتخاب شده روی اسلاید. اشکال را نسبت به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر تراز می‌کند.

--------------------

> ```
> Example:
>   
>   Presentation pres = new Presentation("pres.pptx");
>   try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape1 = slide.getShapes().get_Item(0);
>      IShape shape2 = slide.getShapes().get_Item(1);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignBottom, false, pres.getSlides().get_Item(0), new int[]
>      {
>          slide.getShapes().indexOf(shape1),
>          slide.getShapes().indexOf(shape2)
>      });
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alignmentType | int | تعیین می‌کند کدام نوع تراز اعمال شود. |
| alignToSlide | boolean | اگر true باشد، اشکال نسبت به لبه‌های اسلاید تراز می‌شوند. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | اسلاید والد. |
| shapeIndexes | int[] | ایندکس‌های اشکالی که باید تراز شوند. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```


تغییر مکان تمام اشکال در داخل شکل گروهی. اشکال را نسبت به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر تراز می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape) slide.getShapes().get_Item(0));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alignmentType | int | تعیین می‌کند کدام نوع تراز اعمال شود. |
| alignToSlide | boolean | اگر true باشد، اشکال نسبت به لبه‌های اسلاید تراز می‌شوند. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | شکل گروهی والد. |

### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```


تغییر مکان اشکال انتخاب شده در داخل شکل گروهی. اشکال را نسبت به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر تراز می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      SlideUtil.alignShapes(ShapesAlignmentType.AlignLeft, false, (GroupShape)slide.getShapes().get_Item(0), new int[] { 0, 2 });
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alignmentType | int | تعیین می‌کند کدام نوع تراز اعمال شود. |
| alignToSlide | boolean | اگر true باشد، اشکال نسبت به لبه‌های اسلاید تراز می‌شوند. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | شکل گروهی والد. |
| shapeIndexes | int[] | ایندکس‌های اشکالی که باید تراز شوند. |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```


یافتن و جایگزینی متن در ارائه با قالب داده شده

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه اسکن شده. |
| withMasters | boolean | تعیین می‌کند آیا اسلایدهای اصلی اسکن شوند یا نه. |
| find | java.lang.String | مقدار رشته‌ای برای جستجو. |
| replace | java.lang.String | مقدار رشته‌ای برای جایگزینی. کاراکتر رشته یافت شده |

### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```


یافتن و جایگزینی متن در ارائه با قالب داده شده

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      PortionFormat format = new PortionFormat();
>      format.setFontHeight(24f);
>      format.setFontItalic(NullableBool.True);
>      format.getFillFormat().setFillType(FillType.Solid);
>      format.getFillFormat().getSolidFillColor().setColor(Color.RED);
> 
>      SlideUtil.findAndReplaceText(pres, true, "[this block] ", "my text ", format);
>      pres.save("replaced.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه اسکن شده. |
| withMasters | boolean | تعیین می‌کند آیا اسلایدهای اصلی اسکن شوند یا نه. |
| find | java.lang.String | مقدار رشته‌ای برای جستجو. |
| replace | java.lang.String | مقدار رشته‌ای برای جایگزینی. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | قالب برای جایگزینی بخش متن. اگر null باشد، قالب اولین کاراکتر رشته یافت شده استفاده می‌شود. |

### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```


تمام قاب‌های متن را در یک اسلاید از ارائه PPTX برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | اسلاید اسکن شده. |

**بازگشت:**
com.aspose.slides.ITextFrame[] - آرایه‌ای از [TextFrame](../../com.aspose.slides/textframe).

### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```


تمام قاب‌های متنی را در اسلاید مشخص شده که متن داده شده را شامل می‌شوند برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | اسلاید برای جستجو. |
| text | java.lang.String | متنی که باید در قاب‌های متن جستجو شود. |
| checkPlaceholderText | boolean | تعیین می‌کند آیا قاب‌های متنی خالی که متن جایگزین آن‌ها شامل متن جستجو باشد نیز شامل شوند یا نه. |

**بازگشت:**
com.aspose.slides.ITextFrame[] - آرایه‌ای از [ITextFrame](../../com.aspose.slides/itextframe) که متن مشخص‌شده را شامل می‌شوند.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```


تمام قاب‌های متن را در یک ارائه PPTX برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه اسکن شده. |
| withMasters | boolean | تعیین می‌کند آیا اسلایدهای اصلی اسکن شوند یا نه. |

**بازگشت:**
com.aspose.slides.ITextFrame[] - آرایه‌ای از [TextFrame](../../com.aspose.slides/textframe).
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```


یک قالب فایل منبع را به [SaveFormat](../../com.aspose.slides/saveformat) متناظر تبدیل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | int | قالب فایل منبع. |

**بازگشت:**
int - مقدار [SaveFormat](../../com.aspose.slides/saveformat) متناظر.