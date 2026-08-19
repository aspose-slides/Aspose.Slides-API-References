---
title: AutoShape
second_title: Aspose.Slides برای مرجع API جاوا
description: یک AutoShape را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/autoshape/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

یک AutoShape را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | قفل‌های شکل را برمی‌گرداند. |
| [getAutoShapeLock()](#getAutoShapeLock--) | قفل‌های autoshape را برمی‌گرداند. |
| [getTextFrame()](#getTextFrame--) | شیء TextFrame را برای AutoShape برمی‌گرداند. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | تعیین می‌کند که آیا این autoshape باید به‌جای مقداردهی توسط سبک یا قالب پر شدن، با پر کردن پس‌زمینه اسلاید پر شود یا خیر. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | تعیین می‌کند که آیا این autoshape باید به‌جای مقداردهی توسط سبک یا قالب پر شدن، با پر کردن پس‌زمینه اسلاید پر شود یا خیر. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | یک TextFrame جدید به شکل اضافه می‌کند. |
| [isTextBox()](#isTextBox--) | مشخص می‌کند که آیا شکل یک جعبه متن است یا خیر. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```


قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**بازگشت:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```


قفل‌های autoshape را برمی‌گرداند. فقط-خواندنی [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**بازگشت:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


شیء TextFrame را برای AutoShape برمی‌گرداند. فقط-خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```


تعیین می‌کند که آیا این autoshape باید به‌جای مقداردهی توسط سبک یا قالب پر شدن، با پر کردن پس‌زمینه اسلاید پر شود یا خیر. بولی خواندنی/نوشتنی.

**بازگشت:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```


تعیین می‌کند که آیا این autoshape باید به‌جای مقداردهی توسط سبک یا قالب پر شدن، با پر کردن پس‌زمینه اسلاید پر شود یا خیر. بولی خواندنی/نوشتنی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```


یک TextFrame جدید به شکل اضافه می‌کند. اگر شکل قبلاً TextFrame داشته باشد، تنها متن آن را تغییر می‌دهد.

--------------------

> ```
> The following sample code shows how to add watermark text in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape watermarkShape = slide.getShapes().addAutoShape(ShapeType.Triangle, 0, 0, 150, 50);
>      ITextFrame watermarkTextFrame = watermarkShape.addTextFrame("Watermark");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to create Text Box on Slide.
>  
>  // یک نمونه از Presentation را ایجاد می‌کند
>  Presentation pres = new Presentation();
>  try {
>      // اولین اسلاید در ارائه را دریافت می‌کند
>      ISlide sld = pres.getSlides().get_Item(0);
>      // یک AutoShape با نوع Rectangle اضافه می‌کند
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // یک TextFrame به Rectangle اضافه می‌کند
>      ashp.addTextFrame(" ");
>      // به TextFrame دسترسی می‌یابد
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // شیء Paragraph برای TextFrame ایجاد می‌کند
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // شیء Portion برای پاراگراف ایجاد می‌کند
>      IPortion portion = para.getPortions().get_Item(0);
>      // متن را تنظیم می‌کند
>      portion.setText("Aspose TextBox");
>      // ارائه را در دیسک ذخیره می‌کند
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // اولین اسلاید در ارائه را دریافت می‌کند
>      ISlide slide = pres.getSlides().get_Item(0);
>      // یک AutoShape با نوع Rectangle اضافه می‌کند
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // یک TextFrame به Rectangle اضافه می‌کند
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // فرمت متن TextFrame را دریافت می‌کند
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // تعداد ستون‌ها در TextFrame را مشخص می‌کند
>      format.setColumnCount(3);
>      // فاصله بین ستون‌ها را تنظیم می‌کند
>      format.setColumnSpacing(10);
>      // ارائه را ذخیره می‌کند
>      pres.save("ColumnCount.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن پیش‌فرض برای یک TextFrame جدید. |

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```


مشخص می‌کند که آیا شکل یک جعبه متن است یا خیر.

--------------------

اگر شکل به عنوان جعبه متن مشخص نشده باشد، به این معنا نیست که نمی‌تواند متن داشته باشد. جعبه متن صرفاً یک شکل تخصصی با ویژگی‌های خاص است.

**بازگشت:**
boolean