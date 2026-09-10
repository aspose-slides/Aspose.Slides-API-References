---
title: Paragraph
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: نمایانگر یک پاراگراف متن.
type: docs
url: /fa/com.aspose.slides/paragraph/
---
**ارث‌بری:**
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

یک پاراگراف متن را نشان می‌دهد.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [Paragraph()](#Paragraph--) | یک نمونه جدید از کلاس Paragraph را با ویژگی‌های پیش‌فرض مقداردهی اولیه می‌کند. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | سازنده نسخه‌برداری که یک نمونه جدید از کلاس Paragraph را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getPortions()](#getPortions--) | مجموعه‌ای از بخش‌های متن را برمی‌گرداند. |
| [getParagraphFormat()](#getParagraphFormat--) | شیء قالب‌بندی برای این پاراگراف را برمی‌گرداند. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | دنباله‌ها را با قالب‌بندی یکسان ترکیب می‌کند. |
| [getText()](#getText--) | متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. |
| [getRect()](#getRect--) | مختصات مستطیلی که پاراگراف را دربر می‌گیرد، دریافت می‌کند. |
| [getLinesCount()](#getLinesCount--) | تعداد خطوط در یک پاراگراف را دریافت می‌کند. |
| [getImage()](#getImage--) | یک تصویر از پاراگراف را برمی‌گرداند. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | یک تصویر از پاراگراف را با مقیاس مشخص شده برمی‌گرداند. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | ویژگی‌های بخش را که در صورت درج بخش دیگری پس از آخرین بخش استفاده می‌شود، مشخص می‌کند. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | ویژگی‌های بخش را که در صورت درج بخش دیگری پس از آخرین بخش استفاده می‌شود، مشخص می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | اسلاید والد یک پاراگراف را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد یک پاراگراف را برمی‌گرداند. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

یک نمونه جدید از کلاس Paragraph را با ویژگی‌های پیش‌فرض مقداردهی اولیه می‌کند.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

سازنده نسخه‌برداری که یک نمونه جدید از کلاس Paragraph را مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

مجموعه‌ای از بخش‌های متن را برمی‌گرداند. فقط-خواندنی [IPortionCollection](../../com.aspose.slides/iportioncollection).

**بازگرداندن:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

شیء قالب‌بندی برای این پاراگراف را برمی‌گرداند. فقط-خواندنی [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

---

شیء قالب‌بندی فقط شامل پارامترهای قالب‌بندی تعریف‌شده برای پاراگراف فعلی است و داده‌های به ارث‌رفته اعمال نمی‌شوند.

برای دریافت مقادیر مؤثر شامل به ارث‌رسدها از روش [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) استفاده کنید.

**بازگرداندن:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

دنباله‌ها را با قالب‌بندی یکسان ترکیب می‌کند.

### getText() {#getText--}
```
public final String getText()
```

متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. خواندن/نوشتن String.

مقدار: متن.

**بازگرداندن:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. خواندن/نوشتن String.

مقدار: متن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

مختصات مستطیلی که پاراگراف را دربر می‌گیرد، دریافت می‌کند. مستطیل شامل تمام خطوط متن در پاراگراف، از جمله خطوط خالی، است.

**بازگرداندن:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

تعداد خطوط در یک پاراگراف را دریافت می‌کند.

---

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

**بازگرداندن:**
int - تعداد خطوط در یک پاراگراف
### getImage() {#getImage--}
```
public final IImage getImage()
```

یک تصویر از پاراگراف را برمی‌گرداند.

---

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

**بازگرداندن:**
[IImage](../../com.aspose.slides/iimage) - یک تصویر شامل پاراگراف رندر شده، یا null اگر پاراگراف در مجموعه والد یافت نشود، محدوده رندر معتبری نداشته باشد، یا هنگام رندر تصویر خطایی رخ دهد.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

یک تصویر از پاراگراف را با مقیاس مشخص شده برمی‌گرداند.

---

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
| scaleX | float | عامل مقیاس افقی اعمال‌شده به تصویر پاراگراف. |
| scaleY | float | عامل مقیاس عمودی اعمال‌شده به تصویر پاراگراف. |

**بازگرداندن:**
[IImage](../../com.aspose.slides/iimage) - یک تصویر شامل پاراگراف رندر شده، یا null اگر پاراگراف در مجموعه والد یافت نشود، محدوده رندر معتبری نداشته باشد، یا هنگام رندر تصویر خطایی رخ دهد.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

ویژگی‌های بخش را که در صورت درج بخش دیگری پس از آخرین بخش استفاده می‌شود، مشخص می‌کند.

**بازگرداندن:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

ویژگی‌های بخش را که در صورت درج بخش دیگری پس از آخرین بخش استفاده می‌شود، مشخص می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگرداندن:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک پاراگراف را برمی‌گرداند. فقط-خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگرداندن:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد یک پاراگراف را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگرداندن:**
[IPresentation](../../com.aspose.slides/ipresentation)