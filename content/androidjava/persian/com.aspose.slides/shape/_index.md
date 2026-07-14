---
title: Shape
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک شکل را در یک اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/shape/
---
**ارث‌بری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject  
```
public class Shape implements IShape, IDOMObject
```

نمایانگر یک شکل در یک اسلاید است.

## متدها

| متد | توضیح |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | مشخّص می‌کند که آیا شکل TextHolder_PPT است یا نه. |
| [getPlaceholder()](#getPlaceholder--) | Placeholder برای یک شکل را برمی‌گرداند. |
| [removePlaceholder()](#removePlaceholder--) | مشخّص می‌کند که این شکل محل نگهدارنده نیست. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | اگر هیچ placeholder‌ای وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [getBasePlaceholder()](#getBasePlaceholder--) | یک شکل placeholder پایه را برمی‌گرداند (شکلی که از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده است). |
| [getCustomData()](#getCustomData--) | داده‌های سفارشی شکل را برمی‌گرداند. |
| [getRawFrame()](#getRawFrame--) | ویژگی‌های چارچوب خام شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | ویژگی‌های چارچوب خام شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [getFrame()](#getFrame--) | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [getLineFormat()](#getLineFormat--) | شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند. |
| [getThreeDFormat()](#getThreeDFormat--) | شیء ThreeDFormat که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است را برمی‌گرداند. |
| [getEffectFormat()](#getEffectFormat--) | شیء EffectFormat که شامل افکت‌های پیکسل اعمال‌شده بر یک شکل است را برمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | شیء FillFormat که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است را برمی‌گرداند. |
| [getImage()](#getImage--) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | تصویر بندانگشتی شکل را برمی‌گرداند. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | محتوی Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | محتوی Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [getHyperlinkClick()](#getHyperlinkClick--) | هایپرلینک تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | هایپرلینک تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | هایپرلینک تعریف‌شده برای حرکتی ماوس (mouse over) را برمی‌گرداند یا تنظیم می‌کند. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | هایپرلینک تعریف‌شده برای حرکتی ماوس (mouse over) را برمی‌گرداند یا تنظیم می‌کند. |
| [getHyperlinkManager()](#getHyperlinkManager--) | مدیر هایپرلینک را برمی‌گرداند. |
| [getHidden()](#getHidden--) | تشخیص می‌دهد که آیا شکل مخفی است یا نه. |
| [setHidden(boolean value)](#setHidden-boolean-) | تشخیص می‌دهد که آیا شکل مخفی است یا نه. |
| [getZOrderPosition()](#getZOrderPosition--) | موقعیت یک شکل در ترتیب z را برمی‌گرداند. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | تعداد نقاط اتصال روی شکل را برمی‌گرداند. |
| [getRotation()](#getRotation--) | تعداد درجات چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. |
| [setRotation(float value)](#setRotation-float-) | تعداد درجات چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. |
| [getX()](#getX--) | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setX(float value)](#setX-float-) | مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getY()](#getY--) | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setY(float value)](#setY-float-) | مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getWidth()](#getWidth--) | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setWidth(float value)](#setWidth-float-) | عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getHeight()](#getHeight--) | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setHeight(float value)](#setHeight-float-) | ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. |
| [getUniqueId()](#getUniqueId--) | یک شناسه داخلی scoped به ارائه را که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است، برمی‌گرداند. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | یک شناسه یکتا scoped به اسلاید که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اعتماد به شکل را از هر جای سند می‌دهد، برمی‌گرداند. |
| [getAlternativeText()](#getAlternativeText--) | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [getName()](#getName--) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [setName(String value)](#setName-java.lang.String-) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [isDecorative()](#isDecorative--) | گزینه 'Mark as decorative' را به صورت boolean خواندنی/نوشتنی برمی‌گرداند یا تنظیم می‌کند. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | گزینه 'Mark as decorative' را به صورت boolean خواندنی/نوشتنی برمی‌گرداند یا تنظیم می‌کند. |
| [getShapeLock()](#getShapeLock--) | قفل‌های شکل را برمی‌گرداند. |
| [isGrouped()](#isGrouped--) | تشخیص می‌دهد که آیا شکل گروه‌بندی شده است یا نه. |
| [getParentGroup()](#getParentGroup--) | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | حدود بصری شکل را که از محتوی رندر‌شده محاسبه می‌شود، می‌گیرد. |
| [getSlide()](#getSlide--) | اسلاید والد یک شکل را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد یک اسلاید را برمی‌گرداند. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

مشخّص می‌کند که آیا شکل TextHolder_PPT است یا نه. **فقط-خواندنی**  boolean .

**باز می‌گرداند:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

Placeholder برای یک شکل را برمی‌گرداند. اگر شکل هیچ placeholder‌ای نداشته باشد، مقدار null برمی‌گردد. **فقط-خواندنی** [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // یک شی از کلاس Presentation ایجاد می‌کند
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // اولین اسلاید را دسترسی می‌یابد
>      ISlide sld = pres.getSlides().get_Item(0);
>      // از اشکال عبور می‌کند تا placeholder را پیدا کند
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // متن هر placeholder را تغییر می‌دهد
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // ارائه را بر روی دیسک ذخیره می‌کند
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
>      for (IShape shape : slide.getSlide().getShapes()) // از اسلاید عبور می‌کند
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint نمایش می‌دهد "برای افزودن عنوان کلیک کنید"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // زیرعنوان را اضافه می‌کند
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

**باز می‌گرداند:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

مشخّص می‌کند که این شکل محل نگهدارنده نیست.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

اگر هیچ placeholder‌ای وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder برای کپی محتوا از آن. |

**باز می‌گرداند:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

یک شکل placeholder پایه را برمی‌گرداند (شکلی که از طرح‌بندی و/یا اسلاید اصلی که شکل فعلی از آن به ارث برده است).

--------------------

> ```
> // دریافت تمام افکت‌های انیمیشنی (master/layout/slide) شکل placeholder
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

اگر شکل فعلی از ارث نبرده باشد، مقدار null برمی‌گردد.

**باز می‌گرداند:**
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

داده‌های سفارشی شکل را برمی‌گرداند. **فقط-خواندنی** [ICustomData](../../com.aspose.slides/icustomdata).

**باز می‌گرداند:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

ویژگی‌های چارچوب خام شکل را برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //or
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //Such code can lead to unclear situations. So restrictions had been added for using undefined values for IShape.getFrame(). Values of x, y, width, height, flipH, flipV and rotationAngle must be defined (not Float.NaN or NullableBool.NotDefined). Example code above now throws ArgumentException exception.
>  //This applies to these use cases:
>  IShape shape = ...;
>  shape.setFrame(...); // cannot be undefined
>  IShapeCollection shapes = ...;
>  // x, y, width, height parameters cannot be Float.NaN:
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
>  //But IShape.RawFrame frame properties can be undefined. This make sence when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // now shape inherits x, y, height, flipH, flipV values form placeholder and overrides width=100 and rotationAngle=0.{code}
> ```

**باز می‌گرداند:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

ویژگی‌های چارچوب خام شکل را برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> کدی که سعی می‌کند فریم نامعین را به IShape.getFrame() اختصاص دهد در حالت کلی منطقی نیست (به‌خصوص زمانی که GroupShape والد چندین بار در داخل سایر GroupShape‌ها تو در تو باشد). برای مثال:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //یا
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //چنین کدی می‌تواند منجر به وضعیت‌های نامشخص شود. بنابراین محدودیت‌هایی برای استفاده از مقادیر نامعین در IShape.getFrame() اضافه شده است. مقادیر x، y، width، height، flipH، flipV و rotationAngle باید تعریف شوند (نه Float.NaN یا NullableBool.NotDefined). کد مثال بالا اکنون استثنای ArgumentException را پرتاب می‌کند.
>  //این برای موارد استفاده زیر اعمال می‌شود:
>  IShape shape = ...;
>  shape.setFrame(...); // نمی‌تواند نامعین باشد
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
>  //اما ویژگی‌های فریم IShape.RawFrame می‌توانند نامعین باشند. این منطقی است وقتی شکل به placeholder لینک شده باشد. سپس مقادیر فریم نامعین از placeholder والد بازنویسی می‌شوند. اگر placeholder والد برای آن شکل وجود نداشته باشد، شکل از مقادیر پیش‌فرض 0 و NullableBool.False برای x، y، width، height، flipH، flipV و rotationAngle استفاده می‌کند. برای مثال:
>  IShape shape = ...; // شکل به placeholder لینک شده است
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // اکنون شکل مقادیر x، y، height، flipH، flipV را از placeholder به ارث می‌برد و width=100 و rotationAngle=0 را بازنویسی می‌کند.{code}
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

مقدار هر ویژگی از نمونهٔ IShapeFrame برگردانده‌شده همیشه تعریف‌شده است (نه Float.NaN). مقدار اختصاص‌یافته نیز باید تعریف‌شده باشد (نه Float.NaN). می‌توانید مقادیر undefined را برای ویژگی‌های RawFrame تنظیم کنید.

**باز می‌گرداند:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

مقدار هر ویژگی از نمونهٔ IShapeFrame برگردانده‌شده همیشه تعریف‌شده است (نه Float.NaN). مقدار اختصاص‌یافته نیز باید تعریف‌شده باشد (نه Float.NaN). می‌توانید مقادیر undefined را برای ویژگی‌های RawFrame تنظیم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی خط ندارند ممکن است مقدار null برگردد. **فقط-خواندنی** [ILineFormat](../../com.aspose.slides/ilineformat).

**باز می‌گرداند:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

شیء ThreeDFormat که شامل ویژگی‌های اثر سه‌بعدی برای یک شکل است را برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی 3d ندارند ممکن است مقدار null برگردد. **فقط-خواندنی** [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**باز می‌گرداند:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

شیء EffectFormat که شامل افکت‌های پیکسل اعمال‌شده بر یک شکل است را برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی اثر ندارند ممکن است مقدار null برگردد. **فقط-خواندنی** [IEffectFormat](../../com.aspose.slides/ieffectformat).

**باز می‌گرداند:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

شیء FillFormat که شامل ویژگی‌های قالب‌بندی پر کردن برای یک شکل است را برمی‌گرداند. توجه: برای برخی انواع شکل‌ها که ویژگی پر کردن ندارند ممکن است مقدار null برگردد. **فقط-خواندنی** [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Accent 4
>      IShape shape1 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 50, 50);
>      shape1.getFillFormat().setFillType(FillType.Solid);
>      shape1.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      // Accent 4, روشن‌تر 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, روشن‌تر 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, روشن‌تر 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, تیره‌تر 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, تیره‌تر 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**باز می‌گرداند:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public final IImage getImage()
```

تصویر بندانگشتی شکل را برمی‌گرداند. ShapeThumbnailBounds.Shape نوع مرز تصویر بندانگشتی به‌صورت پیش‌فرض استفاده می‌شود.

**باز می‌گرداند:**
[IImage](../../com.aspose.slides/iimage) - تصویر بندانگشتی شکل.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

تصویر بندانگشتی شکل را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bounds | int | نوع مرز تصویر بندانگشتی شکل. |
| scaleX | float | مقیاس X |
| scaleY | float | مقیاس Y |

**باز می‌گرداند:**
[IImage](../../com.aspose.slides/iimage) - تصویر بندانگشتی شکل یا null در صورتی که ShapeThumbnailBounds.Appearance استفاده شده و شکل عناصری قابل مشاهده نداشته باشد.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

محتوی Shape را به‌صورت فایل SVG ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

محتوی Shape را به‌صورت فایل SVG ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | گزینه‌های تولید SVG |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

هایپرلینک تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** [IHyperlink](../../com.aspose.slides/ihyperlink).

**باز می‌گرداند:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

هایپرلینک تعریف‌شده برای کلیک ماوس را برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** [IHyperlink](../../com.aspose.slides/ihyperlink).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

هایپرلینک تعریف‌شده برای حرکتی ماوس (mouse over) را برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** [IHyperlink](../../com.aspose.slides/ihyperlink).

**باز می‌گرداند:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

هایپرلینک تعریف‌شده برای حرکتی ماوس (mouse over) را برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** [IHyperlink](../../com.aspose.slides/ihyperlink).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

مدیر هایپرلینک را برمی‌گرداند. **فقط-خواندنی** [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**باز می‌گرداند:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public [‌   ]     public final boolean getHidden()
```

تشخیص می‌دهد که آیا شکل مخفی است یا نه. **خواندنی/نوشتنی**  boolean .

**باز می‌گرداند:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

تشخیص می‌دهد که آیا شکل مخفی است یا نه. **خواندنی/نوشتنی**  boolean .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل را در عقب‌ترین موقعیت z برمی‌گرداند و Shapes[Shapes.Count - 1] شکل را در جلوترین موقعیت z برمی‌گرداند. **فقط-خواندنی**  int .

**باز می‌گرداند:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

تعداد نقاط اتصال روی شکل را برمی‌گرداند. **فقط-خواندنی**  int .

**باز می‌گرداند:**
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

تعداد درجات چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعتگرد؛ مقدار منفی نشانگر چرخش پادساعتگرد است. **خواندنی/نوشتنی** float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است (نه Float.NaN). مقدار اختصاص‌یافته باید تعریف‌شده باشد (نه Float.NaN). می‌توانید مقادیر undefined را برای ویژگی‌های RawFrame تنظیم کنید.

**باز می‌گرداند:**
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

تعداد درجات چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشانگر چرخش ساعتگرد؛ مقدار منفی نشانگر چرخش پادساعتگرد است. **خواندنی/نوشتنی** float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است (نه Float.NaN). مقدار اختصاص‌یافته باید تعریف‌شده باشد (نه Float.NaN). می‌توانید مقادیر undefined را برای ویژگی‌های RawFrame تنظیم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص‌یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونهٔ RawFrame می‌تواند تنظیم شود.

**باز می‌گرداند:**
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

مختصات x گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص‌یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونهٔ RawFrame می‌تواند تنظیم شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص‌یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونهٔ RawFrame می‌تواند تنظیم شود.

**باز می‌گرداند:**
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

مختصات y گوشهٔ بالا-چپ شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص‌یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونهٔ RawFrame می‌تواند تنظیم شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص‌یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونهٔ RawFrame می‌تواند تنظیم شود.

**باز می‌گرداند:**
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

عرض شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص‌یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونهٔ RawFrame می‌تواند تنظیم شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص‌یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونهٔ RawFrame می‌تواند تنظیم شود.

**باز می‌گرداند:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

ارتفاع شکل را که بر حسب نقطه اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** float.

--------------------

مقدار بازگشتی همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص‌یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونهٔ RawFrame می‌تواند تنظیم شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. **خواندنی/نوشتنی** [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**باز می‌گرداند:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر می‌شود. **خواندنی/نوشتنی** [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

یک شناسه داخلی scoped به ارائه را که برای استفاده توسط افزونه‌ها یا کدهای دیگر در نظر گرفته شده است، برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس بازنویسی شود، نباید به عنوان کلید یکتا دائمی تلقی شود. **فقط-خواندنی** long. همچنین به \#getOfficeInteropShapeId.getOfficeInteropShapeId مراجعه کنید.

**باز می‌گرداند:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

یک شناسه یکتا scoped به اسلاید که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop امکان ارجاع قابل اعتماد به شکل را از هر جای سند می‌دهد، برمی‌گرداند. **فقط-خواندنی** long. همچنین به \#getUniqueId.getUniqueId مراجعه کنید.

**باز می‌گرداند:**
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** String.

**باز می‌گرداند:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** String.

**باز می‌گرداند:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. **خواندنی/نوشتنی** String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. باید مقدار null نداشته باشد. در صورت نیاز می‌توانید مقدار رشتهٔ خالی را استفاده کنید. **خواندنی/نوشتنی** String.

**باز می‌گرداند:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. باید مقدار null نداشته باشد. در صورت نیاز می‌توانید مقدار رشتهٔ خالی را استفاده کنید. **خواندنی/نوشتنی** String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

گزینه 'Mark as decorative' را به صورت boolean خواندنی/نوشتنی برمی‌گرداند یا تنظیم می‌کند.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**باز می‌گرداند:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

گزینه 'Mark as decorative' را به صورت boolean خواندنی/نوشتنی برمی‌گرداند یا تنظیم می‌کند.

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

قفل‌های شکل را برمی‌گرداند. **فقط-خواندنی** [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**باز می‌گرداند:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

تشخیص می‌دهد که آیا شکل گروه‌بندی شده است یا نه. **فقط-خواندنی** boolean.

--------------------

خاصیت \#getParentGroup.getParentGroup شیء GroupShape والد را برمی‌گرداند اگر شکل گروه‌بندی شده باشد.

**باز می‌گرداند:**
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. در غیر این صورت null برمی‌گردد. **فقط-خواندنی** [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

خاصیت \#isGrouped.isGrouped تشخیص می‌دهد که آیا شکل گروه‌بندی شده است.

**باز می‌گرداند:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. **فقط-خواندنی** IDOMObject.

**باز می‌گرداند:**
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

حدود بصری شکل را که از محتوی رندر‌شده محاسبه می‌شود، می‌گیرد.

**باز می‌گرداند:**
android.graphics.RectF - یک android.graphics.RectF که حدود بصری شکل را در مختصات اسلاید نشان می‌دهد.

--------------------

مستطیل بازگردانده‌شده نمایانگر حدود محوری تمام محتواهایی است که شکل در هنگام رندر در فضای مختصات اسلاید تولید می‌کند. این حدود ممکن است با حدود مدل شکل \#getX.getX/\#setX(float).setX(float)، \#getY.getY/\#setY(float).setY(float)، \#getWidth.getWidth/\#setWidth(float).setWidth(float)، \#getHeight.getHeight/\#setHeight(float).setHeight(float) متفاوت باشد و ممکن است مختصات منفی داشته باشد اگر محتوی رندر شده فراتر از مبدأ اسلاید گسترش یابد. حدود بصری جنبه‌های مرتبط با رندر مانند تبدیلات (مثلاً چرخش)، عرض و اتصال خطوط، چیدمان متن و سرریز، هندسه SmartArt و سایر اثرات چیدمانی که بر ظاهر نهایی رندر شکل تأثیر می‌گذارند را در نظر می‌گیرد. حدود بازگردانده‌شده به مستطیل اسلاید کلی محدود نمی‌شود.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد یک شکل را برمی‌گرداند. **فقط-خواندنی** [IBaseSlide](../../com.aspose.slides/ibaseslide).

**باز می‌گرداند:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه والد یک اسلاید را برمی‌گرداند. **فقط-خواندنی** [IPresentation](../../com.aspose.slides/ipresentation).

**باز می‌گرداند:**
[IPresentation](../../com.aspose.slides/ipresentation)