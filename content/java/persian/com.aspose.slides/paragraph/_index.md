---
title: Paragraph
second_title: مرجع API Aspose.Slides برای جاوا
description: یک پاراگراف متن را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/paragraph/
---
**ارث‌برداری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

یک پاراگراف متن را نشان می‌دهد.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [Paragraph()](#Paragraph--) | یک نمونه جدید از کلاس Paragraph را با ویژگی‌های پیش‌فرض مقداردهی اولیه می‌کند. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | سازنده‌ کپی که یک نمونه جدید از کلاس Paragraph را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getPortions()](#getPortions--) | مجموعه‌ای از بخش‌های متن را بر می‌گرداند. |
| [getParagraphFormat()](#getParagraphFormat--) | شیء قالب‌بندی این پاراگراف را بر می‌گرداند. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | بخش‌های متن با قالب‌بندی مشابه را به هم می‌پیوندد. |
| [getText()](#getText--) | متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. |
| [getRect()](#getRect--) | مختصات مستطیلی که پاراگراف را محصور می‌کند دریافت می‌کند. |
| [getLinesCount()](#getLinesCount--) | تعداد خطوط در یک پاراگراف را دریافت می‌کند. |
| [getImage()](#getImage--) | تصویری از پاراگراف را بر می‌گرداند. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | تصویری از پاراگراف با مقیاس مشخص شده را بر می‌گرداند. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | خواص بخش را که در صورت افزودن بخش دیگر پس از آخرین بخش استفاده می‌شود، مشخص می‌کند. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | خواص بخش را که در صورت افزودن بخش دیگر پس از آخرین بخش استفاده می‌شود، مشخص می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | اسلاید والد یک پاراگراف را بر می‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه‌گر والد یک پاراگراف را بر می‌گرداند. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

یک نمونه جدید از کلاس Paragraph را با ویژگی‌های پیش‌فرض مقداردهی اولیه می‌کند.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

سازنده‌ کپی که یک نمونه جدید از کلاس Paragraph را مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

مجموعه‌ای از بخش‌های متن را بر می‌گرداند. فقط-خواندنی [IPortionCollection](../../com.aspose.slides/iportioncollection).

**باز می‌گرداند:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

شیء قالب‌بندی این پاراگراف را بر می‌گرداند. فقط-خواندنی [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

شیء قالب‌بندی فقط شامل پارامترهای قالب‌بندی تعریف‌شده برای پاراگراف جاری است؛ داده‌های به‌ارث‌برده اعمال نمی‌شوند.

برای دریافت مقادیر مؤثر شامل ارث‌برده‌ها، از متد [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) استفاده کنید.

**باز می‌گرداند:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

بخش‌های متن با قالب‌بندی مشابه را به هم می‌پیوندد.

### getText() {#getText--}
```
public final String getText()
```

متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی String.

مقدار: متن.

**باز می‌گرداند:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی String.

مقدار: متن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

مختصات مستطیلی که پاراگراف را محصور می‌کند دریافت می‌کند. مستطیل شامل تمام خطوط متن در پاراگراف است، حتی خطوط خالی.

**باز می‌گرداند:**
java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

تعداد خطوط در یک پاراگراف را دریافت می‌کند.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**باز می‌گرداند:**
int - تعداد خطوط در یک پاراگراف
### getImage() {#getImage--}
```
public final IImage getImage()
```

تصویری از پاراگراف را بر می‌گرداند.

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**باز می‌گرداند:**
[IImage](../../com.aspose.slides/iimage) - تصویری شامل پاراگراف رندر شده، یا null اگر پاراگراف در مجموعه والد یافت نشود، مرزهای رندر معتبری نداشته باشد یا خطایی در رندر تصویر رخ دهد.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

تصویری از پاراگراف با مقیاس مشخص شده را بر می‌گرداند.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| scaleX | float | فاکتور مقیاس افقی اعمال‌شده به تصویر پاراگراف. |
| scaleY | float | فاکتور مقیاس عمودی اعمال‌شده به تصویر پاراگراف. |

**باز می‌گرداند:**
[IImage](../../com.aspose.slides/iimage) - تصویری شامل پاراگراف رندر شده، یا null اگر پاراگراف در مجموعه والد یافت نشود، مرزهای رندر معتبری نداشته باشد یا خطایی در رندر تصویر رخ دهد.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

خواص بخش را که در صورت افزودن بخش دیگر پس از آخرین بخش استفاده می‌شود، مشخص می‌کند.

**باز می‌گرداند:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

خواص بخش را که در صورت افزودن بخش دیگر پس از آخرین بخش استفاده می‌شود، مشخص می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را بر می‌گرداند. فقط-خواندنی IDOMObject.

**باز می‌گرداند:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک پاراگراف را بر می‌گرداند. فقط-خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**باز می‌گرداند:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه‌گر والد یک پاراگراف را بر می‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**باز می‌گرداند:**
[IPresentation](../../com.aspose.slides/ipresentation)