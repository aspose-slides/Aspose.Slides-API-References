---
title: Shape
second_title: مرجع API Aspose.Slides برای جاوا
description: یک شکل را بر روی اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/shape/
---
**وراثت:**  
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject  
```
public class Shape implements IShape, IDOMObject
```

نمایشگر یک شکل روی اسلاید.

## متدها

| متد | شرح |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | تعیین می‌کند که آیا شکل TextHolder\_PPT است. |
| [getPlaceholder()](#getPlaceholder--) | بازگرداندن جای‌دار (placeholder) برای یک شکل. |
| [removePlaceholder()](#removePlaceholder--) | تعریف می‌کند که این شکل جای‌دار نیست. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | افزودن یک جای‌دار جدید در صورت عدم وجود و تنظیم ویژگی‌های جای‌دار به مقدار مشخص‌شده. |
| [getBasePlaceholder()](#getBasePlaceholder--) | بازگرداندن یک شکل پایه جای‌دار (شکلی از چیدمان و/یا اسلاید اصلی که شکل جاری از آن ارث‌بری می‌کند). |
| [getCustomData()](#getCustomData--) | بازگرداندن داده‌های سفارشی شکل. |
| [getRawFrame()](#getRawFrame--) | دریافت یا تنظیم ویژگی‌های فریم شکل خام. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | دریافت یا تنظیم ویژگی‌های فریم شکل خام. |
| [getFrame()](#getFrame--) | دریافت یا تنظیم ویژگی‌های فریم شکل. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | دریافت یا تنظیم ویژگی‌های فریم شکل. |
| [getLineFormat()](#getLineFormat--) | بازگرداندن شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای شکل است. |
| [getThreeDFormat()](#getThreeDFormat--) | بازگرداندن شیء ThreeDFormat که ویژگی‌های اثر ۳بعدی برای شکل را دارد. |
| [getEffectFormat()](#getEffectFormat--) | بازگرداندن شیء EffectFormat که شامل اثرات پیکسلی اعمال‌شده بر شکل است. |
| [getFillFormat()](#getFillFormat--) | بازگرداندن شیء FillFormat که شامل ویژگی‌های قالب‌بندی پر کردن برای شکل است. |
| [getImage()](#getImage--) | بازگرداندن تصویر کوچک (thumbnail) شکل. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | بازگرداندن تصویر کوچک (thumbnail) شکل. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | ذخیره محتوای Shape به عنوان فایل SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | ذخیره محتوای Shape به عنوان فایل SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | دریافت یا تنظیم پیوندهای ابرمتنی تعریف‌شده برای کلیک ماوس. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | دریافت یا تنظیم پیوندهای ابرمتنی تعریف‌شده برای کلیک ماوس. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | دریافت یا تنظیم پیوندهای ابرمتنی تعریف‌شده برای حرکت ماوس روی عنصر. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | دریافت یا تنظیم پیوندهای ابرمتنی تعریف‌شده برای حرکت ماوس روی عنصر. |
| [getHyperlinkManager()](#getHyperlinkManager--) | بازگرداندن مدیر پیوندهای ابرمتنی. |
| [getHidden()](#getHidden--) | تعیین می‌کند که آیا شکل مخفی است. |
| [setHidden(boolean value)](#setHidden-boolean-) | تعیین می‌کند که آیا شکل مخفی است. |
| [getZOrderPosition()](#getZOrderPosition--) | بازگرداندن موقعیت شکل در ترتیب z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | بازگرداندن تعداد نقاط اتصال روی شکل. |
| [getRotation()](#getRotation--) | دریافت یا تنظیم تعداد درجه‌های چرخش مشخص‌شده شکل حول محور z. |
| [setRotation(float value)](#setRotation-float-) | دریافت یا تنظیم تعداد درجه‌های چرخش مشخص‌شده شکل حول محور z. |
| [getX()](#getX--) | دریافت یا تنظیم مختصات x گوشهٔ بالایی-چپ شکل، بر حسب نقاط. |
| [setX(float value)](#setX-float-) | دریافت یا تنظیم مختصات x گوشهٔ بالایی-چپ شکل، بر حسب نقاط. |
| [getY()](#getY--) | دریافت یا تنظیم مختصات y گوشهٔ بالایی-چپ شکل، بر حسب نقاط. |
| [setY(float value)](#setY-float-) | دریافت یا تنظیم مختصات y گوشهٔ بالایی-چپ شکل، بر حسب نقاط. |
| [getWidth()](#getWidth--) | دریافت یا تنظیم عرض شکل، بر حسب نقاط. |
| [setWidth(float value)](#setWidth-float-) | دریافت یا تنظیم عرض شکل، بر حسب نقاط. |
| [getHeight()](#getHeight--) | دریافت یا تنظیم ارتفاع شکل، بر حسب نقاط. |
| [setHeight(float value)](#setHeight-float-) | دریافت یا تنظیم ارتفاع شکل، بر حسب نقاط. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | ویژگی مشخص می‌کند که شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | ویژگی مشخص می‌کند که شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. |
| [getUniqueId()](#getUniqueId--) | بازگرداندن شناسه داخلی scoped به ارائه‌نامه برای استفاده افزونه‌ها یا کدهای دیگر. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | بازگرداندن شناسه یکتا scoped به اسلاید که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اطمینان به شکل را از هرجای سند می‌دهد. |
| [getAlternativeText()](#getAlternativeText--) | دریافت یا تنظیم متن جایگزین مرتبط با شکل. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | دریافت یا تنظیم متن جایگزین مرتبط با شکل. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | دریافت یا تنظیم عنوان متن جایگزین مرتبط با شکل. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | دریافت یا تنظیم عنوان متن جایگزین مرتبط با شکل. |
| [getName()](#getName--) | دریافت یا تنظیم نام شکل. |
| [setName(String value)](#setName-java.lang.String-) | دریافت یا تنظیم نام شکل. |
| [isDecorative()](#isDecorative--) | دریافت یا تنظیم گزینه «علامت‌گذاری به‌عنوان تزئینی» (خواندنی/نوشتنی). |
| [setDecorative(boolean value)](#setDecorative-boolean-) | دریافت یا تنظیم گزینه «علامت‌گذاری به‌عنوان تزئینی» (خواندنی/نوشتنی). |
| [getShapeLock()](#getShapeLock--) | بازگرداندن قفل‌های شکل. |
| [isGrouped()](#isGrouped--) | تعیین می‌کند که آیا شکل گروه‌بندی‌شده است. |
| [getParentGroup()](#getParentGroup--) | بازگرداندن شیء Parent GroupShape اگر شکل گروه‌بندی‌شده باشد. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | دریافت حدود بصری شکل که از محتوای رندرش محاسبه می‌شود. |
| [getSlide()](#getSlide--) | بازگرداندن اسلاید والد برای یک شکل. |
| [getPresentation()](#getPresentation--) | بازگرداندن ارائه‌نامهٔ والد برای یک اسلاید. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

تعیین می‌کند که آیا شکل TextHolder\_PPT است. فقط خواندنی  boolean .

**بازگشت:**  
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

بازگرداندن جای‌دار برای یک شکل. اگر شکل جای‌دار نداشته باشد، null باز می‌گرداند. فقط خواندنی [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // ایجاد یک شی از کلاس Presentation
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // دسترسی به اولین اسلاید
>      ISlide sld = pres.getSlides().get_Item(0);
>      // مرور اشکال برای یافتن جایدار
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // تغییر متن در هر جایدار
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // ذخیره ارائه در دیسک
>      pres.save("output_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set Prompt Text in Placeholder.
>  
>  Presentation pres = new Presentation("Presentation2.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      for (IShape shape : slide.getSlide().getShapes()) // مرور اسلاید
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint نمایش می‌دهد "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // افزودن زیرعنوان
>              {
>                  text = "Add Subtitle";
>              }
>              ((IAutoShape)shape).getTextFrame().setText(text);
>              System.out.println("Placeholder with text: " + text);
>          }
>      }
>      pres.save("Placeholders_PromptText.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

تعریف می‌کند که این شکل جای‌دار نیست.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

افزودن یک جای‌دار جدید در صورت عدم وجود و تنظیم ویژگی‌های جای‌دار به مقدار مشخص‌شده.

**پارامترها:**  
| پارامتر | نوع | توصیف |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | جای‌دار برای کپی محتوا از آن. |

**بازگشت:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder) - جدید #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

بازگرداندن یک شکل پایه جای‌دار (شکلی از چیدمان و/یا اسلاید اصلی که شکل جاری از آن ارث‌بری می‌کند).

--------------------

> ```
> // دریافت تمام افکت‌های انیمیشنی (master/layout/slide) شکل جایدار
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IShape shape = slide.getShapes().get_Item(0);
>      IEffect[] shapeEffects = slide.getTimeline().getMainSequence().getEffectsByShape(shape);
>      IShape layoutShape = shape.getBasePlaceholder();
>      IEffect[] layoutShapeEffects = slide.getLayoutSlide().getTimeline().getMainSequence().getEffectsByShape(layoutShape);
>      IShape masterShape = layoutShape.getBasePlaceholder();
>      IEffect[] masterShapeEffects = slide.getLayoutSlide().getMasterSlide().getTimeline().getMainSequence().getEffectsByShape(masterShape);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

اگر شکل جاری ارث‌بری نشده باشد، مقدار null باز می‌گردد.

**بازگشت:**  
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

بازگرداندن داده‌های سفارشی شکل. فقط خواندنی [ICustomData](../../com.aspose.slides/icustomdata).

**بازگشت:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

دریافت یا تنظیم ویژگی‌های فریم شکل خام. خواندنی/نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //یا
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //چنین کدی می‌تواند به وضعیت‌های مبهم منجر شود. بنابراین محدودیت‌هایی برای استفاده از مقادیر تعریف نشده در IShape.getFrame() اضافه شده است. مقادیر x، y، width، height، flipH، flipV و rotationAngle باید تعریف شوند (نه Float.NaN یا NullableBool.NotDefined). کد نمونه بالا اکنون استثنای ArgumentException را پرتاب می‌کند.
>  //این برای موارد استفاده زیر اعمال می‌شود:
>  IShape shape = ...;
>  shape.setFrame(...); // نمی‌تواند تعریف نشده باشد
>  IShapeCollection shapes = ...;
>  // پارامترهای x، y، width، height نمی‌توانند Float.NaN باشند:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //اما ویژگی‌های فریم IShape.RawFrame می‌توانند تعریف نشده باشند. این وقتی معنادار است که شکل به یک placeholder لینک شده باشد. در این حالت مقادیر فریم تعریف نشده از شکل placeholder والد بازنویسی می‌شوند. اگر برای آن شکل placeholder والد وجود نداشته باشد، شکل از مقادیر پیش‌فرض استفاده می‌کند هنگام ارزیابی فریم مؤثر بر پایه IShape.RawFrame. مقادیر پیش‌فرض 0 و NullableBool.False برای x، y، width، height، flipH، flipV و rotationAngle هستند. برای مثال:
>  IShape shape = ...; // شکل به placeholder لینک شده است
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // اکنون شکل مقدارهای x، y، height، flipH، flipV را از placeholder به ارث می‌برد و width=100 و rotationAngle=0 را بازنویسی می‌کند.{code}
> ```


**بازگشت:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

دریافت یا تنظیم ویژگی‌های فریم شکل خام. خواندنی/نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //یا
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //چنین کدی می‌تواند به وضعیت‌های مبهم منجر شود. بنابراین محدودیت‌هایی برای استفاده از مقادیر تعریف نشده در IShape.getFrame() اضافه شده است. مقادیر x، y، width، height، flipH، flipV و rotationAngle باید تعریف شوند (نه Float.NaN یا NullableBool.NotDefined). کد نمونه بالا اکنون استثنای ArgumentException را پرتاب می‌کند.
>  //این برای موارد استفاده زیر اعمال می‌شود:
>  IShape shape = ...;
>  shape.setFrame(...); // نمی‌تواند تعریف نشده باشد
>  IShapeCollection shapes = ...;
>  // پارامترهای x، y، width، height نمی‌توانند Float.NaN باشند:
>  {
>      shapes.addAudioFrameCD(...);
>      shapes.addAudioFrameEmbedded(...);
>      shapes.addAudioFrameLinked(...);
>      shapes.addAutoShape(...);
>      shapes.addChart(...);
>      shapes.addConnector(...);
>      shapes.addOleObjectFrame(...);
>      shapes.addPictureFrame(...);
>      shapes.addSmartArt(...);
>      shapes.addTable(...);
>      shapes.addVideoFrame(...);
>      shapes.insertAudioFrameEmbedded(...);
>      shapes.insertAudioFrameLinked(...);
>      shapes.insertAutoShape(...);
>      shapes.insertChart(...);
>      shapes.insertConnector(...);
>      shapes.insertOleObjectFrame(...);
>      shapes.insertPictureFrame(...);
>      shapes.insertTable(...);
>      shapes.insertVideoFrame(...);
>  }
>  //اما ویژگی‌های فریم IShape.RawFrame می‌توانند تعریف نشده باشند. این وقتی معنادار است که شکل به یک placeholder لینک شده باشد. در این صورت مقادیر فریم تعریف نشده از شکل placeholder والد بازنویسی می‌شوند. اگر برای آن شکل placeholder والد وجود نداشته باشد، شکل از مقادیر پیش‌فرض استفاده می‌کند وقتی فریم مؤثر را بر پایه IShape.RawFrame ارزیابی می‌کند. مقادیر پیش‌فرض 0 و NullableBool.False برای x، y، width، height، flipH، flipV و rotationAngle هستند. برای مثال:
>  IShape shape = ...; // شکل به placeholder لینک شده است
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // اکنون شکل مقادیر x، y، height، flipH، flipV را از placeholder به ارث می‌برد و width=100 و rotationAngle=0 را بازنویسی می‌کند.{code}
> ```


**پارامترها:**  
| پارامتر | نوع | توصیف |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

دریافت یا تنظیم ویژگی‌های فریم شکل. خواندنی/نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

مقدار هر ویژگی از نمونهٔ IShapeFrame بازگردانده‌شده تعریف‌شده است (نگهداری نشده یا NotDefined نیست). مقدار هر ویژگی از نمونهٔ IShapeFrame تخصیص داده‌شده باید تعریف‌شده باشد (نه NaN یا NotDefined). می‌توانید مقادیر undefined را برای ویژگی‌های RawFrame تنظیم کنید.

**بازگشت:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

دریافت یا تنظیم ویژگی‌های فریم شکل. خواندنی/نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

مقدار هر ویژگی از نمونهٔ IShapeFrame بازگردانده‌شده تعریف‌شده است (نگهداری نشده یا NotDefined نیست). مقدار هر ویژگی از نمونهٔ IShapeFrame تخصیص داده‌شده باید تعریف‌شده باشد (نه NaN یا NotDefined). می‌توانید مقادیر undefined را برای ویژگی‌های RawFrame تنظیم کنید.

**پارامترها:**  
| پارامتر | نوع | توصیف |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

بازگرداندن شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. نکته: برای برخی انواع شکل‌ها که ویژگی خط ندارند، می‌تواند null برگرداند. فقط خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازگشت:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

بازگرداندن شیء ThreeDFormat که ویژگی‌های اثر ۳بعدی برای یک شکل را دارد. نکته: برای برخی انواع شکل‌ها که ویژگی ۳بعدی ندارند، می‌تواند null برگرداند. فقط خواندنی [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**بازگشت:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

بازگرداندن شیء EffectFormat که شامل اثرات پیکسلی اعمال‌شده بر یک شکل است. نکته: برای برخی انواع شکل‌ها که ویژگی اثر ندارند، می‌تواند null برگرداند. فقط خواندنی [IEffectFormat](../../com.aspose.slides/ieffectformat).

**بازگشت:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

بازگرداندن شیء FillFormat که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است. نکته: برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند، می‌تواند null برگرداند. فقط خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

--------------------

> ```
> The following example shows how to change the accent color for a theme of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      shape.getFillFormat().setFillType(FillType.Solid);
>      shape.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example demonstrates how to obtain palette colors from the main theme color and then used in shapes.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      // رنگ Accent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // رنگ Accent 4، روشن‌تر 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // رنگ Accent 4، روشن‌تر 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // رنگ Accent 4، روشن‌تر 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // رنگ Accent 4، تیره‌تر 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // رنگ Accent 4، تیره‌تر 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

بازگرداندن تصویر کوچک (thumbnail) شکل. نوع ShapeThumbnailBounds.Shape به‌صورت پیش‌فرض استفاده می‌شود.

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - تصویر کوچک شکل.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

بازگرداندن تصویر کوچک (thumbnail) شکل.

**پارامترها:**  
| پارامتر | نوع | توصیف |
| --- | --- | --- |
| bounds | int | نوع حدود تصویر کوچک شکل. |
| scaleX | float | مقیاس X |
| scaleY | float | مقیاس Y |

**بازگشت:**  
[IImage](../../com.aspose.slides/iimage) - تصویر کوچک شکل یا null در صورتی که ShapeThumbnailBounds.Appearance استفاده شود و شکل عناصری قابل مشاهده نداشته باشد.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

ذخیره محتوای Shape به عنوان فایل SVG.

**پارامترها:**  
| پارامتر | نوع | توصیف |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

ذخیره محتوای Shape به عنوان فایل SVG.

**پارامترها:**  
| پارامتر | نوع | توصیف |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | گزینه‌های تولید SVG |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

دریافت یا تنظیم پیوندهای ابرمتنی تعریف‌شده برای کلیک ماوس. خواندنی/نوشتنی [IHyperlink](../../com.aspose.slides/ihyperlink).

**بازگشت:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

دریافت یا تنظیم پیوندهای ابرمتنی تعریف‌شده برای کلیک ماوس. خواندنی/نوشتنی [IHyperlink](../../com.aspose.slides/ihyperlink).

**پارامترها:**  
| پارامتر | نوع | توصیف |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

دریافت یا تنظیم پیوندهای ابرمتنی تعریف‌شده برای حرکت ماوس روی عنصر. خواندنی/نوشتنی [IHyperlink](../../com.aspose.slides/ihyperlink).

**بازگشت:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

دریافت یا تنظیم پیوندهای ابرمتنی تعریف‌شده برای حرکت ماوس روی عنصر. خواندنی/نوشتنی [IHyperlink](../../com.aspose.slides/ihyperlink).

**پارامترها:**  
| پارامتر | نوع | توصیف |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

بازگرداندن مدیر پیوندهای ابرمتنی. فقط خواندنی [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**بازگشت:**  
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

تعیین می‌کند که آیا شکل مخفی است. خواندنی/نوشتنی  boolean .

**بازگشت:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

تعیین می‌کند که آیا شکل مخفی است. خواندنی/نوشتنی  boolean .

**پارامترها:**  
| پارامتر | نوع | توصیف |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

بازگرداندن موقعیت یک شکل در ترتیب z. Shapes[0] شکل را در عقب‌ترین موقعیت z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلوی ترین موقعیت z برمی‌گرداند. فقط خواندنی  int .

**بازگشت:**  
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

بازگرداندن تعداد نقاط اتصال روی شکل. فقط خواندنی  int .

**بازگشت:**  
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

دریافت یا تنظیم تعداد درجه‌های چرخش مشخص‌شده شکل حول محور z. مقدار مثبت نشان‌دهنده چرخش ساعتگرد؛ مقدار منفی نشان‌دهنده چرخش ساعت‌عکس است. خواندنی/نوشتنی float.

--------------------

مقدار بازگردانده همیشه تعریف‌شده است (Float.NaN نیست). مقدار تخصیص داده‌شده باید تعریف‌شده باشد (نه Float.NaN). می‌توانید مقادیر undefined را برای ویژگی‌های RawFrame تنظیم کنید.

**بازگشت:**  
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
بازگرداندن یا تنظیم تعداد درجه‌های چرخشی که شکل مشخص شده حول محور z می‌چرخد. مقدار مثبت نشان‌دهندهٔ چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهندهٔ چرخش پادساعت‌گرد است. قابل خواندن/نوشتن float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است (Float.NaN نیست). مقدار اختصاص داده‌شده باید تعریف‌شده باشد (نه Float.NaN). می‌توانید مقادیر تعریف‌نشده را برای ویژگی‌های یک نمونه RawFrame تنظیم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

دریافت یا تنظیم مختصات x گوشهٔ بالا-چپ شکل، بر حسب نقاط. قابل خواندن/نوشتن float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص داده‌شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame اختصاص دهید.

**بازگشت:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

دریافت یا تنظیم مختصات x گوشهٔ بالا-چپ شکل، بر حسب نقاط. قابل خواندن/نوشتن float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص داده‌شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame اختصاص دهید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

دریافت یا تنظیم مختصات y گوشهٔ بالا-چپ شکل، بر حسب نقاط. قابل خواندن/نوشتن float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص داده‌شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame اختصاص دهید.

**بازگشت:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

دریافت یا تنظیم مختصات y گوشهٔ بالا-چپ شکل، بر حسب نقاط. قابل خواندن/نوشتن float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص داده‌شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame اختصاص دهید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

دریافت یا تنظیم عرض شکل، بر حسب نقاط. قابل خواندن/نوشتن float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص داده‌شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame اختصاص دهید.

**بازگشت:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

دریافت یا تنظیم عرض شکل، بر حسب نقاط. قابل خواندن/نوشتن float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص داده‌شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame اختصاص دهید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

دریافت یا تنظیم ارتفاع شکل، بر حسب نقاط. قابل خواندن/نوشتن float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص داده‌شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame اختصاص دهید.

**بازگشت:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

دریافت یا تنظیم ارتفاع شکل، بر حسب نقاط. قابل خواندن/نوشتن float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص داده‌شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame اختصاص دهید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

ویژگی مشخص می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر می‌شود.. قابل خواندن/نوشتن [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**بازگشت:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

ویژگی مشخص می‌کند شکل در حالت نمایش سیاه-سفید چگونه رندر می‌شود.. قابل خواندن/نوشتن [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

یک شناسه داخلی در سطح ارائه که برای افزودنی‌ها یا کدهای دیگر به کار می‌رود، بازگردانده می‌شود. از آنجا که این مقدار می‌تواند توسط کاربر یا برنامه‌نویس مجدداً اختصاص داده شود، نباید به‌عنوان کلید منحصربه‌فرد دائم در نظر گرفته شود. فقط خواندنی long. همچنین ببینید \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**بازگشت:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

یک شناسهٔ یکتا در سطح اسلاید که برای طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اعتماد به شکل را از هر نقطه‌ای در سند می‌دهد، بازگردانده می‌شود. فقط خواندنی long. همچنین ببینید \#getUniqueId.getUniqueId.

**بازگشت:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

بازگرداندن یا تنظیم متن جایگزین مرتبط با یک شکل. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

بازگرداندن یا تنظیم متن جایگزین مرتبط با یک شکل. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

بازگرداندن یا تنظیم عنوان متن جایگزین مرتبط با یک شکل. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

بازگرداندن یا تنظیم عنوان متن جایگزین مرتبط با یک شکل. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

بازگرداندن یا تنظیم نام یک شکل. نباید مقدار null باشد. در صورت نیاز از رشتهٔ خالی استفاده کنید. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

بازگرداندن یا تنظیم نام یک شکل. نباید مقدار null باشد. در صورت نیاز از رشتهٔ خالی استفاده کنید. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

دریافت یا تنظیم گزینه «Mark as decorative». قابل خواندن/نوشتن boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

دریافت یا تنظیم گزینه «Mark as decorative». قابل خواندن/نوشتن boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

قفل‌های شکل را بازمی‌گرداند. فقط خواندنی [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**بازگشت:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

تعیین می‌کند که شکل گروه‌بندی شده است یا نه. فقط خواندنی boolean.

--------------------

ویژگی \#getParentGroup.getParentGroup شیء GroupShape والد را برمی‌گرداند اگر شکل گروه‌بندی شده باشد.

**بازگشت:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

شیء GroupShape والد را باز می‌گرداند اگر شکل گروه‌بندی شده باشد. در غیر این صورت null باز می‌گرداند. فقط خواندنی [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

ویژگی \#isGrouped.isGrouped تعیین می‌کند که آیا شکل گروه‌بندی شده است.

**بازگشت:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را باز می‌گرداند. فقط خواندنی IDOMObject.

**بازگشت:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```

مرزهای بصری شکل را که از محتوای رندر شده‌اش محاسبه می‌شود، باز می‌گرداند.

**بازگشت:**
java.awt.geom.Rectangle2D.Float - یک java.awt.geom.Rectangle2D.Float که مرزهای بصری شکل را در مختصات اسلاید نشان می‌دهد.

--------------------

مستطیل بازگردانده‌شده نشان‌دهندهٔ محدوده‌های محوری تمام محتوایی است که توسط شکل در طول رندر در فضای مختصات اسلاید تولید می‌شود. این محدوده‌ها ممکن است با محدوده‌های مدل شکل که در \#getX.getX/\#setX(float).setX(float)، \#getY.getY/\#setY(float).setY(float)، \#getWidth.getWidth/\#setWidth(float).setWidth(float)، \#getHeight.getHeight/\#setHeight(float).setHeight(float) تعریف شده‌اند، متفاوت باشند و ممکن است شامل مختصات منفی باشند اگر محتوای رندر شده فراتر از مبدأ اسلاید گسترش یابد. محدوده‌های بصری عوامل مرتبط با رندر مانند تبدیلات (مثلاً چرخش)، عرض و اتصال خطوط، چینش متن و سرریز، هندسهٔ SmartArt، و سایر اثرات چیدمانی که ظاهر نهایی رندر شدهٔ شکل را تحت تأثیر قرار می‌دهند را در نظر می‌گیرند. محدوده‌های بازگردانده‌شده به مستطیل اسلاید قطع نمی‌شوند.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک شکل را باز می‌گرداند. فقط خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**بازگشت:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد اسلاید را باز می‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**
[IPresentation](../../com.aspose.slides/ipresentation)