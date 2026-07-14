---
title: Paragraph
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک پاراگراف متن را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/paragraph/
---
**ارث‌بری:**
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
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | سازنده‌ی کپی که یک نمونه جدید از کلاس Paragraph را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getPortions()](#getPortions--) | مجموعه‌ای از بخش‌های متن را برمی‌گرداند. |
| [getParagraphFormat()](#getParagraphFormat--) | شیء قالب‌بندی برای این پاراگراف را برمی‌گرداند. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | بخش‌های متن با قالب‌بندی یکسان را به هم می‌پیوندد. |
| [getText()](#getText--) | متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. |
| [getRect()](#getRect--) | مختصات مستطیل محدوده پاراگراف را دریافت می‌کند. |
| [getLinesCount()](#getLinesCount--) | تعداد خطوط یک پاراگراف را دریافت می‌کند. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | ویژگی‌های بخش را که در صورت افزودن بخش دیگری پس از آخرین بخش استفاده می‌شوند، مشخص می‌کند. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | ویژگی‌های بخش را که در صورت افزودن بخش دیگری پس از آخرین بخش استفاده می‌شوند، مشخص می‌کند. |
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

سازنده‌ی کپی که یک نمونه جدید از کلاس Paragraph را مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |
### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

مجموعه‌ای از بخش‌های متن را برمی‌گرداند. فقط‌خواندنی [IPortionCollection](../../com.aspose.slides/iportioncollection).

**بازگشت:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

شیء قالب‌بندی برای این پاراگراف را برمی‌گرداند. فقط‌خواندنی [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

شیء قالب‌بندی فقط حاوی پارامترهای قالب‌بندی تعریف شده برای پاراگراف جاری است و داده‌های ارث‌برده اعمال نمی‌شوند.

برای به‌دست آوردن مقادیر مؤثر شامل مقادیر ارث‌برده، از متد [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) استفاده کنید.

**بازگشت:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

بخش‌های متن با قالب‌بندی یکسان را به هم می‌پیوندد.

### getText() {#getText--}
```
public final String getText()
```

متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. خواندن/نوشتن String.

مقدار: متن.

**بازگشت:**
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

مختصات مستطیل محدوده پاراگراف را دریافت می‌کند. این مستطیل شامل تمام خطوط متن در پاراگراف، شامل خطوط خالی، است.

**بازگشت:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```

تعداد خطوط یک پاراگراف را دریافت می‌کند.

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

**بازگشت:**
int - تعداد خطوط در یک پاراگراف
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

ویژگی‌های بخش را مشخص می‌کند که در صورت افزودن بخش دیگری پس از آخرین بخش استفاده می‌شوند.

**بازگشت:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

ویژگی‌های بخش را مشخص می‌کند که در صورت افزودن بخش دیگری پس از آخرین بخش استفاده می‌شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط‌خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک پاراگراف را برمی‌گرداند. فقط‌خواندنی [BaseSlide](../../com.aspose.slides/baseslide).

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد یک پاراگراف را برمی‌گرداند. فقط‌خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)