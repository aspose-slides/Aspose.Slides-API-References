---
title: AutoShape
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک AutoShape را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/autoshape/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IAutoShape](../../com.aspose.slides/iautoshape)
```
public final class AutoShape extends GeometryShape implements IAutoShape
```

یک AutoShape را نشان می‌دهد.
## روش‌ها

| متد | توضیح |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | قفل‌های شکل را بر می‌گرداند. |
| [getAutoShapeLock()](#getAutoShapeLock--) | قفل‌های autoshape را بر می‌گرداند. |
| [getTextFrame()](#getTextFrame--) | شیء TextFrame را برای AutoShape بر می‌گرداند. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | تعیین می‌کند که آیا این autoshape باید با پرکنندهٔ پس‌زمینهٔ اسلاید پر شود به جای آن که توسط سبک یا فرمت پرکننده مشخص شود. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | تعیین می‌کند که آیا این autoshape باید با پرکنندهٔ پس‌زمینهٔ اسلاید پر شود به جای آن که توسط سبک یا فرمت پرکننده مشخص شود. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | یک TextFrame جدید به شکل اضافه می‌کند. |
| [isTextBox()](#isTextBox--) | مشخص می‌کند که آیا شکل یک text box است. |
### getShapeLock() {#getShapeLock--}
```
public final IAutoShapeLock getShapeLock()
```

قفل‌های شکل را بر می‌گرداند. فقط-خواندنی [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**بر می‌گرداند:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getAutoShapeLock() {#getAutoShapeLock--}
```
public final IAutoShapeLock getAutoShapeLock()
```

قفل‌های autoshape را بر می‌گرداند. فقط-خواندنی [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**بر می‌گرداند:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

شیء TextFrame را برای AutoShape بر می‌گرداند. فقط-خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بر می‌گرداند:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public final boolean getUseBackgroundFill()
```

تعیین می‌کند که آیا این autoshape باید با پرکنندهٔ پس‌زمینهٔ اسلاید پر شود به جای آن که توسط سبک یا فرمت پرکننده مشخص شود. خواندنی/قابل نوشتن boolean.

**بر می‌گرداند:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public final void setUseBackgroundFill(boolean value)
```

تعیین می‌کند که آیا این autoshape باید با پرکنندهٔ پس‌زمینهٔ اسلاید پر شود به جای آن که توسط سبک یا فرمت پرکننده مشخص شود. خواندنی/قابل نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public final ITextFrame addTextFrame(String text)
```

یک TextFrame جدید به شکل اضافه می‌کند. اگر شکل قبلاً TextFrame داشته باشد، متن آن را به سادگی تغییر می‌دهد.

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
>  // نمونه‌سازی Presentation
>  Presentation pres = new Presentation();
>  try {
>      // اسلاید اول ارائه را دریافت می‌کند
>      ISlide sld = pres.getSlides().get_Item(0);
>      // یک AutoShape با نوع مستطیل اضافه می‌کند
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      // TextFrame را به مستطیل اضافه می‌کند
>      ashp.addTextFrame(" ");
>      // به فریم متن دسترسی می‌یابد
>      ITextFrame txtFrame = ashp.getTextFrame();
>      // شیء Paragraph را برای فریم متن ایجاد می‌کند
>      IParagraph para = txtFrame.getParagraphs().get_Item(0);
>      // شیء Portion را برای پاراگراف ایجاد می‌کند
>      IPortion portion = para.getPortions().get_Item(0);
>      // متن را تنظیم می‌کند
>      portion.setText("Aspose TextBox");
>      // ارائه را بر روی دیسک ذخیره می‌کند
>      pres.save("TextBox_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add column in Text Box.
>  
>  Presentation pres = new Presentation();
>  try {
>      // اسلاید اول ارائه را دریافت می‌کند
>      ISlide slide = pres.getSlides().get_Item(0);
>      // یک AutoShape با نوع مستطیل اضافه می‌کند
>      IAutoShape aShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      // TextFrame را به مستطیل اضافه می‌کند
>      aShape.addTextFrame("All these columns are limited to be within a single text container -- " +
>      "you can add or delete text and the new or remaining text automatically adjusts " +
>      "itself to flow within the container. You cannot have text flow from one container " +
>      "to other though -- we told you PowerPoint's column options for text are limited!");
>      // قالب متن TextFrame را دریافت می‌کند
>      ITextFrameFormat format = aShape.getTextFrame().getTextFrameFormat();
>      // تعداد ستون‌ها در TextFrame را مشخص می‌کند
>      format.setColumnCount(3);
>      // فاصله بین ستون‌ها را مشخص می‌کند
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

**بر می‌گرداند:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isTextBox() {#isTextBox--}
```
public final boolean isTextBox()
```

مشخص می‌کند که آیا شکل یک text box است.

--------------------

اگر شکل به عنوان یک text box مشخص نشود، به این معنی نیست که نمی‌تواند متن داشته باشد. یک text box صرفاً یک شکل تخصصی با ویژگی‌های خاص است.

**بر می‌گرداند:**
boolean