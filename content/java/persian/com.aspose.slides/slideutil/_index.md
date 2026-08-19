---
title: SlideUtil
second_title: Aspose.Slides برای مرجع API جاوا
description: متدهایی را ارائه می‌دهد که به جستجو در اشکال و متن در یک ارائه کمک می‌کند.
type: docs
url: /fa/com.aspose.slides/slideutil/
---
**ارث‌بری:**
java.lang.Object
```
public class SlideUtil
```

متدهایی را ارائه می‌دهد که به جستجو در اشکال و متن در یک ارائه کمک می‌کند.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [SlideUtil()](#SlideUtil--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [findShape(IPresentation pres, String altText)](#findShape-com.aspose.slides.IPresentation-java.lang.String-) | یافتن شکل بر اساس متن جایگزین در یک ارائه PPTX. |
| [findShape(IBaseSlide slide, String altText)](#findShape-com.aspose.slides.IBaseSlide-java.lang.String-) | یافتن شکل بر اساس متن جایگزین در یک اسلاید در یک ارائه PPTX. |
| [findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)](#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-) | جستجو برای تمام اشکال در اسلاید مشخص شده که با نوع نگهدارنده داده شده مطابقت دارند. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-) | تغییر مکان تمام اشکال در اسلاید. |
| [alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---) | تغییر مکان اشکال انتخاب شده در اسلاید. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-) | تغییر مکان تمام اشکال درون شکل گروهی. |
| [alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)](#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---) | تغییر مکان اشکال انتخاب شده درون شکل گروهی. |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-) | متن را در ارائه پیدا کرده و با قالب داده شده جایگزین می‌کند |
| [findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)](#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-) | متن را در ارائه پیدا کرده و با قالب داده شده جایگزین می‌کند |
| [getAllTextBoxes(IBaseSlide slide)](#getAllTextBoxes-com.aspose.slides.IBaseSlide-) | تمام فریم‌های متنی را در یک اسلاید در یک ارائه PPTX بر می‌گرداند. |
| [getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)](#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-) | تمام فریم‌های متنی را در اسلاید مشخص شده که شامل متن داده شده هستند بر می‌گرداند. |
| [getAllTextFrames(IPresentation pres, boolean withMasters)](#getAllTextFrames-com.aspose.slides.IPresentation-boolean-) | تمام فریم‌های متنی را در یک ارائه PPTX بر می‌گرداند. |
| [toSaveFormat(int format)](#toSaveFormat-int-) | یک قالب فایل منبع را به [SaveFormat](../../com.aspose.slides/saveformat) متناظر تبدیل می‌کند. |
### SlideUtil() {#SlideUtil--}
```
public SlideUtil()
```

### findShape(IPresentation pres, String altText) {#findShape-com.aspose.slides.IPresentation-java.lang.String-}
```
public static IShape findShape(IPresentation pres, String altText)
```

یافتن شکل بر اساس متن جایگزین در یک ارائه PPTX.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه اسکن‌شده. |
| altText | java.lang.String | متن جایگزین یک شکل. |

**بازگرداندن:**
[IShape](../../com.aspose.slides/ishape) - Shape یا null.
### findShape(IBaseSlide slide, String altText) {#findShape-com.aspose.slides.IBaseSlide-java.lang.String-}
```
public static IShape findShape(IBaseSlide slide, String altText)
```

یافتن شکل بر اساس متن جایگزین در یک اسلاید در یک ارائه PPTX.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | اسلاید اسکن‌شده. |
| altText | java.lang.String | متن جایگزین یک شکل. |

**بازگرداندن:**
[IShape](../../com.aspose.slides/ishape) - Shape یا null.
### findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType) {#findShapesByPlaceholderType-com.aspose.slides.IBaseSlide-byte-}
```
public static IShape[] findShapesByPlaceholderType(IBaseSlide slide, byte placeholderType)
```

جستجو برای تمام اشکال در اسلاید مشخص شده که با نوع نگهدارنده داده شده مطابقت دارند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | اسلایدی که برای جستجوی اشکال استفاده می‌شود. |
| placeholderType | byte | نوع نگهدارنده‌ای که برای فیلتر کردن اشکال استفاده می‌شود. |

**بازگرداندن:**
com.aspose.slides.IShape[] - آرایه‌ای از اشیاء [IShape](../../com.aspose.slides/ishape) که با نوع نگهدارنده مشخص شده مطابقت دارند.
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide)
```

مکان تمام اشکال را در اسلاید تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر تراز می‌کند.

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
| alignmentType | int | نوع تراز شدن که اعمال خواهد شد را تعیین می‌کند. |
| alignToSlide | boolean | اگر true باشد، اشکال نسبت به لبه‌های اسلاید تراز می‌شوند. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | اسلاید والد. |
### alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IBaseSlide-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IBaseSlide slide, int[] shapeIndexes)
```

تغییر مکان اشکال انتخاب‌شده در اسلاید. اشکال را به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر تراز می‌کند.

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
| alignmentType | int | نوع تراز شدن که اعمال خواهد شد را تعیین می‌کند. |
| alignToSlide | boolean | اگر true باشد، اشکال نسبت به لبه‌های اسلاید تراز می‌شوند. |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | اسلاید والد. |
| shapeIndexes | int[] | اندیس‌های اشکال برای تراز شدن. |
### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape)
```

مکان تمام اشکال درون شکل گروهی را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر تراز می‌کند.

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
| alignmentType | int | نوع تراز شدن که اعمال خواهد شد را تعیین می‌کند. |
| alignToSlide | boolean | اگر true باشد، اشکال نسبت به لبه‌های اسلاید تراز می‌شوند. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | شکل گروهی والد. |
### alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes) {#alignShapes-int-boolean-com.aspose.slides.IGroupShape-int---}
```
public static void alignShapes(int alignmentType, boolean alignToSlide, IGroupShape groupShape, int[] shapeIndexes)
```

تغییر مکان اشکال انتخاب شده درون شکل گروهی. اشکال را به حاشیه‌ها یا لبه اسلاید تراز می‌کند یا نسبت به یکدیگر تراز می‌کند.

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
| alignmentType | int | نوع تراز شدن که اعمال خواهد شد را تعیین می‌کند. |
| alignToSlide | boolean | اگر true باشد، اشکال نسبت به لبه‌های اسلاید تراز می‌شوند. |
| groupShape | [IGroupShape](../../com.aspose.slides/igroupshape) | شکل گروهی والد. |
| shapeIndexes | int[] | اندیس‌های اشکال برای تراز شدن. |
### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace)
```

متن را در ارائه پیدا کرده و با قالب داده شده جایگزین می‌کند

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
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه اسکن‌شده. |
| withMasters | boolean | تعیین می‌کند که آیا اسلایدهای اصلی اسکن شوند یا نه. |
| find | java.lang.String | مقدار رشته برای جستجو. |
| replace | java.lang.String | مقدار رشته برای جایگزینی. کاراکتر رشته یافت‌شده |
### findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format) {#findAndReplaceText-com.aspose.slides.IPresentation-boolean-java.lang.String-java.lang.String-com.aspose.slides.PortionFormat-}
```
public static void findAndReplaceText(IPresentation presentation, boolean withMasters, String find, String replace, PortionFormat format)
```

متن را در ارائه پیدا کرده و با قالب داده شده جایگزین می‌کند

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
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه اسکن‌شده. |
| withMasters | boolean | تعیین می‌کند که آیا اسلایدهای اصلی اسکن شوند یا نه. |
| find | java.lang.String | مقدار رشته برای جستجو. |
| replace | java.lang.String | مقدار رشته برای جایگزینی. |
| format | [PortionFormat](../../com.aspose.slides/portionformat) | قالب برای جایگزینی بخش متن. اگر null باشد، قالب کاراکتر اول رشته یافت‌شده استفاده می‌شود. |
### getAllTextBoxes(IBaseSlide slide) {#getAllTextBoxes-com.aspose.slides.IBaseSlide-}
```
public static ITextFrame[] getAllTextBoxes(IBaseSlide slide)
```

تمام فریم‌های متنی را در یک اسلاید در یک ارائه PPTX بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | اسلاید اسکن‌شده. |

**بازگرداندن:**
com.aspose.slides.ITextFrame[] - آرایه‌ای از اشیاء [TextFrame](../../com.aspose.slides/textframe).
### getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText) {#getTextBoxesContainsText-com.aspose.slides.IBaseSlide-java.lang.String-boolean-}
```
public static ITextFrame[] getTextBoxesContainsText(IBaseSlide slide, String text, boolean checkPlaceholderText)
```

تمام فریم‌های متنی را در اسلاید مشخص شده که شامل متن داده شده هستند بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | اسلایدی که برای جستجو استفاده می‌شود. |
| text | java.lang.String | متنی که در فریم‌های متنی جستجو می‌شود. |
| checkPlaceholderText | boolean | نشان می‌دهد آیا فریم‌های متنی خالی که متن نگهدارنده آنها شامل متن جستجو است نیز شامل شوند یا نه. |

**بازگرداندن:**
com.aspose.slides.ITextFrame[] - آرایه‌ای از اشیاء [ITextFrame](../../com.aspose.slides/itextframe) که متن مشخص‌شده را شامل می‌شوند.
### getAllTextFrames(IPresentation pres, boolean withMasters) {#getAllTextFrames-com.aspose.slides.IPresentation-boolean-}
```
public static ITextFrame[] getAllTextFrames(IPresentation pres, boolean withMasters)
```

تمام فریم‌های متنی را در یک ارائه PPTX بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pres | [IPresentation](../../com.aspose.slides/ipresentation) | ارائه اسکن‌شده. |
| withMasters | boolean | تعیین می‌کند که آیا اسلایدهای اصلی اسکن شوند یا نه. |

**بازگرداندن:**
com.aspose.slides.ITextFrame[] - آرایه‌ای از اشیاء [TextFrame](../../com.aspose.slides/textframe).
### toSaveFormat(int format) {#toSaveFormat-int-}
```
public static int toSaveFormat(int format)
```

یک قالب فایل منبع را به [SaveFormat](../../com.aspose.slides/saveformat) متناظر تبدیل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format | int | قالب فایل منبع. |

**بازگرداندن:**
int - مقدار [SaveFormat](../../com.aspose.slides/saveformat) متناظر.