---
title: TextStyle
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: این کلاس شامل ویژگی‌های قالب‌بندی سبک متن است.
type: docs
url: /fa/com.aspose.slides/textstyle/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ITextStyle](../../com.aspose.slides/itextstyle), com.aspose.slides.IStyleColorOwner
```
public final class TextStyle extends PVIObject implements ITextStyle, IStyleColorOwner
```

این کلاس شامل ویژگی‌های قالب‌بندی سبک متن است.
## متدها

| متد | توضیح |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getLevel(int index)](#getLevel-int-) | اگر سطح سبک موجود باشد، آن را برمی‌گرداند، در غیر این صورت null برمی‌گرداند. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | ویژگی‌های پیش‌فرض پاراگراف. |
| [getEffective()](#getEffective--) | داده‌های قالب‌بندی متن سبک مؤثر را با اعمال وراثت دریافت می‌کند. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**بازگشت:**
long
### getLevel(int index) {#getLevel-int-}
```
public final IParagraphFormat getLevel(int index)
```

اگر سطح سبک موجود باشد، آن را برمی‌گرداند، در غیر این صورت null برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبتنی سطح. باید در بازه 0..8 باشد. |

**بازگشت:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - قالب‌بندی سطح [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public final IParagraphFormat getDefaultParagraphFormat()
```

ویژگی‌های پیش‌فرض پاراگراف. فقط خواندنی [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**بازگشت:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public final ITextStyleEffectiveData getEffective()
```

داده‌های قالب‌بندی متن سبک مؤثر را با اعمال وراثت دریافت می‌کند.

--------------------

> ```
> This example demonstrates getting some of effective text style properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextStyleEffectiveData effectiveTextStyle = shape.getTextFrame().getTextFrameFormat().getTextStyle().getEffective();
>      for (int i = 0; i <= 8; i++)
>      {
>          IParagraphFormatEffectiveData effectiveStyleLevel = effectiveTextStyle.getLevel(i);
>          System.out.println("= Effective paragraph formatting for style level #" + i + " =");
>          System.out.println("Depth: " + effectiveStyleLevel.getDepth());
>          System.out.println("Indent: " + effectiveStyleLevel.getIndent());
>          System.out.println("Alignment: " + effectiveStyleLevel.getAlignment());
>          System.out.println("Font alignment: " + effectiveStyleLevel.getFontAlignment());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - یک [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).