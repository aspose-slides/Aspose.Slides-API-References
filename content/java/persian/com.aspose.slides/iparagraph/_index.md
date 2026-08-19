---
title: IParagraph
second_title: مرجع API Aspose.Slides برای جاوا
description: یک پاراگراف از متن را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/iparagraph/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

یک پاراگراف از متن را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getPortions()](#getPortions--) | مجموعه‌ای از بخش‌های متن را برمی‌گرداند. |
| [getParagraphFormat()](#getParagraphFormat--) | شیء فرمت‌بندی را برای این پاراگراف برمی‌گرداند. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | دنباله‌های با فرمت یکسان را ملحق می‌کند. |
| [getText()](#getText--) | متن سادهٔ پاراگراف را می‌گیرد یا تنظیم می‌کند. |
| [setText(String value)](#setText-java.lang.String-) | متن سادهٔ پاراگراف را می‌گیرد یا تنظیم می‌کند. |
| [getRect()](#getRect--) | مختصات مستطیلی که پاراگراف را محاط می‌کند، را به‌دست می‌آورد. |
| [getLinesCount()](#getLinesCount--) | تعداد خطوط در یک پاراگراف را به‌دست می‌آورد. |
| [getImage()](#getImage--) | یک تصویر از پاراگراف را برمی‌گرداند. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | یک تصویر از پاراگراف را با مقیاس مشخص‌شده برمی‌گرداند. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | خاصیت‌های بخش را که در صورت افزودن بخش دیگری پس از آخرین بخش استفاده می‌شوند، مشخص می‌کند. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | خاصیت‌های بخش را که در صورت افزودن بخش دیگری پس از آخرین بخش استفاده می‌شوند، مشخص می‌کند. |
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

شیء فرمت‌بندی را برای این پاراگراف برمی‌گرداند. فقط-خواندنی [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**بازگشت:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

دنباله‌های با فرمت یکسان را ملحق می‌کند.

### getText() {#getText--}
```
public abstract String getText()
```

متن سادهٔ پاراگراف را می‌گیرد یا تنظیم می‌کند. خواندن/نوشتن String.

مقدار: متن.

**بازگشت:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

متن سادهٔ پاراگراف را می‌گیرد یا تنظیم می‌کند. خواندن/نوشتن String.

مقدار: متن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```

مختصات مستطیلی که پاراگراف را محاط می‌کند را به‌دست می‌آورد. این مستطیل شامل تمام خطوط متن در پاراگراف، از جمله خطوط خالی، می‌شود.

**بازگشت:**
java.awt.geom.Rectangle2D.Float - مستطیلی که پاراگراف را محاط می‌کند java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```

تعداد خطوط در یک پاراگراف را به‌دست می‌آورد.

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
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

یک تصویر از پاراگراف را برمی‌گرداند.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه یک پاراگراف را به عنوان تصویر رندر کنیم:
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

**بازگشت:**
[IImage](../../com.aspose.slides/iimage) - تصویری شامل پاراگراف رندر‌شده، یا null اگر پاراگراف در مجموعه والد یافت نشود، مرزهای رندر معتبری نداشته باشد، یا خطایی در حین رندر تصویر رخ دهد.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

یک تصویر از پاراگراف را با مقیاس مشخص‌شده برمی‌گرداند.

--------------------

> ```
> مثال زیر نشان می‌دهد چگونه هر پاراگراف جعبه متن را روی یک اسلاید به عنوان تصویر با مقیاس‌بندی سفارشی رندر کنیم:
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
| scaleX | float | عامل مقیاس افقی اعمال‌شده بر تصویر پاراگراف. |
| scaleY | float | عامل مقیاس عمودی اعمال‌شده بر تصویر پاراگراف. |

**بازگشت:**
[IImage](../../com.aspose.slides/iimage) - تصویری شامل پاراگراف رندر‌شده، یا null اگر پاراگراف در مجموعه والد یافت نشود، مرزهای رندر معتبری نداشته باشد، یا خطایی در حین رندر تصویر رخ دهد.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```

خاصیت‌های بخش را که در صورت افزودن بخش دیگری پس از آخرین بخش استفاده می‌شوند، مشخص می‌کند.

**بازگشت:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

خاصیت‌های بخش را که در صورت افزودن بخش دیگری پس از آخرین بخش استفاده می‌شوند، مشخص می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |