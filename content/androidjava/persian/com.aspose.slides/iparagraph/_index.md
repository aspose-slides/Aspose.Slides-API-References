---
title: IParagraph
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر یک پاراگراف از متن است.
type: docs
url: /fa/com.aspose.slides/iparagraph/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

یک پاراگراف از متن را نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getPortions()](#getPortions--) | مجموعه‌ای از بخش‌های متن را برمی‌گرداند. |
| [getParagraphFormat()](#getParagraphFormat--) | شیء قالب‌بندی برای این پاراگراف را برمی‌گرداند. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | دو تکه متن با قالب‌بندی یکسان را به هم می‌پیوندد. |
| [getText()](#getText--) | متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. |
| [getRect()](#getRect--) | مختصات مستطیلی که پاراگراف را محصور می‌کند دریافت می‌کند. |
| [getLinesCount()](#getLinesCount--) | تعداد خطوط در یک پاراگراف را دریافت می‌کند. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | ویژگی‌های بخش را مشخص می‌کند که در صورت افزودن بخش دیگری پس از آخرین بخش، استفاده شوند. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | ویژگی‌های بخش را مشخص می‌کند که در صورت افزودن بخش دیگری پس از آخرین بخش، استفاده شوند. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

مجموعه‌ای از بخش‌های متن را برمی‌گرداند. فقط-خواندنی [IPortionCollection](../../com.aspose.slides/iportioncollection).

**بازگشت:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

شیء قالب‌بندی برای این پاراگراف را برمی‌گرداند. فقط-خواندنی [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**بازگشت:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

دو تکه متن با قالب‌بندی یکسان را به هم می‌پیوندد.

### getText() {#getText--}
```
public abstract String getText()
```

متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. خواندن/نوشتن String.

مقدار: متن.

**بازگشت:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

متن ساده یک پاراگراف را دریافت یا تنظیم می‌کند. خواندن/نوشتن String.

مقدار: متن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract RectF getRect()
```

مختصات مستطیلی که پاراگراف را محصور می‌کند دریافت می‌کند. این مستطیل شامل تمام خطوط متن در پاراگراف است، حتی خطوط خالی.

**بازگشت:**
android.graphics.RectF - مستطیلی که پاراگراف را محصور می‌کند android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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

**بازگشت:**
int - تعداد خطوط در یک پاراگراف
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

ویژگی‌های بخش را مشخص می‌کند که در صورت افزودن بخش دیگری پس از آخرین بخش، استفاده شوند.

**بازگشت:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

ویژگی‌های بخش را مشخص می‌کند که در صورت افزودن بخش دیگری پس از آخرین بخش، استفاده شوند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |