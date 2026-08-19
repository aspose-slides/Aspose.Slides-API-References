---
title: IShape
second_title: Aspose.Slides برای مرجع API جاوا
description: یک shape را در اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ishape/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

نمایانگر یک shape در اسلاید است.
## متدها

| Method | Description |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | تعیین می‌کند که آیا shape TextHolder است. |
| [getPlaceholder()](#getPlaceholder--) | placeholder را برای یک shape باز می‌گرداند. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌کند. |
| [removePlaceholder()](#removePlaceholder--) | تعریف می‌کند که این shape placeholder نیست. |
| [getCustomData()](#getCustomData--) | داده‌های سفارشی shape را باز می‌گرداند. |
| [getRawFrame()](#getRawFrame--) | ویژگی‌های فریم raw shape را باز می‌گرداند یا تنظیم می‌کند. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | ویژگی‌های فریم raw shape را باز می‌گرداند یا تنظیم می‌کند. |
| [getFrame()](#getFrame--) | ویژگی‌های فریم shape را باز می‌گرداند یا تنظیم می‌کند. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | ویژگی‌های فریم shape را باز می‌گرداند یا تنظیم می‌کند. |
| [getLineFormat()](#getLineFormat--) | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک shape است، باز می‌گرداند. |
| [getThreeDFormat()](#getThreeDFormat--) | شیء ThreeDFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک shape است، باز می‌گرداند. |
| [getEffectFormat()](#getEffectFormat--) | شیء EffectFormat را که شامل اثرهای پیکسلی اعمال‌شده به یک shape است، باز می‌گرداند. |
| [getFillFormat()](#getFillFormat--) | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک shape است، باز می‌گرداند. |
| [getImage()](#getImage--) | تصویر کوچک shape را باز می‌گرداند. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | تصویر کوچک shape را باز می‌گرداند. |
| [getHidden()](#getHidden--) | تعیین می‌کند که آیا shape مخفی است. |
| [setHidden(boolean value)](#setHidden-boolean-) | تعیین می‌کند که آیا shape مخفی است. |
| [getZOrderPosition()](#getZOrderPosition--) | موقعیت یک shape در ترتیب z را باز می‌گرداند. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | تعداد نقاط اتصال روی shape را باز می‌گرداند. |
| [getRotation()](#getRotation--) | تعداد درجه‌های چرخش shape حول محور z را باز می‌گرداند یا تنظیم می‌کند. |
| [setRotation(float value)](#setRotation-float-) | تعداد درجه‌های چرخش shape حول محور z را باز می‌گرداند یا تنظیم می‌کند. |
| [getX()](#getX--) | مختصات x گوشه بالایی-چپ shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. |
| [setX(float value)](#setX-float-) | مختصات x گوشه بالایی-چپ shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. |
| [getY()](#getY--) | مختصات y گوشه بالایی-چپ shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. |
| [setY(float value)](#setY-float-) | مختصات y گوشه بالایی-چپ shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. |
| [getWidth()](#getWidth--) | عرض shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. |
| [setWidth(float value)](#setWidth-float-) | عرض shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. |
| [getHeight()](#getHeight--) | ارتفاع shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. |
| [setHeight(float value)](#setHeight-float-) | ارتفاع shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. |
| [getAlternativeText()](#getAlternativeText--) | متن جایگزین مرتبط با یک shape را باز می‌گرداند یا تنظیم می‌کند. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | متن جایگزین مرتبط با یک shape را باز می‌گرداند یا تنظیم می‌کند. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | عنوان متن جایگزین مرتبط با یک shape را باز می‌گرداند یا تنظیم می‌کند. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | عنوان متن جایگزین مرتبط با یک shape را باز می‌گرداند یا تنظیم می‌کند. |
| [getName()](#getName--) | نام یک shape را باز می‌گرداند یا تنظیم می‌کند. |
| [setName(String value)](#setName-java.lang.String-) | نام یک shape را باز می‌گرداند یا تنظیم می‌کند. |
| [isDecorative()](#isDecorative--) | گزینه «Mark as decorative» را به صورت بولی خواندنی-نوشتنی تنظیم یا دریافت می‌کند. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | گزینه «Mark as decorative» را به صورت بولی خواندنی-نوشتنی تنظیم یا دریافت می‌کند. |
| [getShapeLock()](#getShapeLock--) | قفل‌های shape را باز می‌گرداند. |
| [getUniqueId()](#getUniqueId--) | شناسه داخلی scoped برای ارائه که برای افزونه‌ها یا کدهای دیگر در دسترس است را باز می‌گرداند. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | شناسه یکتا scoped برای اسلاید که برای طول عمر shape ثابت است و اجازه می‌دهد PowerPoint یا کدهای interop به‌طور قابل اعتماد به shape ارجاع دهند، را باز می‌گرداند. |
| [isGrouped()](#isGrouped--) | تعیین می‌کند که آیا shape در یک گروه قرار دارد. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | ویژگی مشخص می‌کند که shape چگونه در حالت نمایش سیاه-سفید رندر خواهد شد. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | ویژگی مشخص می‌کند که shape چگونه در حالت نمایش سیاه-سفید رندر خواهد شد. |
| [getParentGroup()](#getParentGroup--) | در صورت گروه‌بندی بودن shape، شیء parent GroupShape را باز می‌گرداند. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند. |
| [getBasePlaceholder()](#getBasePlaceholder--) | یک shape placeholder پایه (shape ای از layout و/یا master slide که shape جاری از آن ارث‌بری شده) را باز می‌گرداند. |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

تعیین می‌کند که آیا shape TextHolder است. فقط-خواندنی بولی.

**باز می‌گرداند:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

placeholder را برای یک shape باز می‌گرداند. فقط-خواندنی [IPlaceholder](../../com.aspose.slides/iplaceholder).

**باز می‌گرداند:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

اگر placeholder وجود نداشته باشد، یک placeholder جدید اضافه می‌کند و ویژگی‌های placeholder را به مقدار مشخص شده تنظیم می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder ای که محتوا از آن کپی می‌شود. |

**باز می‌گرداند:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - [IPlaceholder](../../com.aspose.slides/iplaceholder) جدید.

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

تعریف می‌کند که این shape placeholder نیست.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

داده‌های سفارشی shape را باز می‌گرداند. فقط-خواندنی [ICustomData](../../com.aspose.slides/icustomdata).

**باز می‌گرداند:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

ویژگی‌های فریم raw shape را باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //یا
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //چنین کدی می‌تواند به وضعیت‌های نامشخص منجر شود. بنابراین محدودیت‌هایی برای استفاده از مقادیر ناشناخته در IShape.getFrame() اضافه شده‌اند. مقادیر x، y، width، height، flipH، flipV و rotationAngle باید تعریف شوند (نه Float.NaN یا NullableBool.NotDefined). کد مثال بالا اکنون استثنای ArgumentException را پرتاب می‌کند.
>  //این موارد برای موارد استفاده زیر اعمال می‌شود:
>  IShape shape = ...;
>  shape.setFrame(...); // نمی‌تواند ناشناخته باشد
>  IShapeCollection shapes = ...;
>  // پارامترهای x، y، width و height نمی‌توانند Float.NaN باشند:
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
>  اما ویژگی‌های فریم IShape.RawFrame می‌توانند ناشناخته باشند. این منطقی است وقتی shape به placeholder مرتبط باشد. در این صورت مقادیر فریم ناشناخته از shape placeholder والد بازنویسی می‌شود. اگر برای آن shape placeholder والد وجود نداشته باشد، آن shape از مقادیر پیش‌فرض استفاده می‌کند هنگامی که فریم مؤثر را بر اساس IShape.RawFrame محاسبه می‌کند. مقادیر پیش‌فرض 0 و NullableBool.False برای x، y، width، height، flipH، flipV و rotationAngle هستند. برای مثال:
>  IShape shape = ...; // shape به placeholder مرتبط است
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // اکنون shape مقادیر x، y، height، flipH و flipV را از placeholder به ارث می‌برد و مقدار width=100 و rotationAngle=0 را بازنویسی می‌کند.
```

**باز می‌گرداند:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

ویژگی‌های فریم raw shape را باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
> //یا
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
> //چنین کدی می‌تواند به وضعیت‌های نامشخص منجر شود. بنابراین محدودیت‌هایی برای استفاده از مقادیر نامشخص در IShape.getFrame() اضافه شده‌اند. مقادیر x، y، width، height، flipH، flipV و rotationAngle باید تعریف شوند (نه Float.NaN یا NullableBool.NotDefined). کد مثال بالا اکنون استثنای ArgumentException را پرتاب می‌کند.
> //این برای موارد استفاده زیر اعمال می‌شود:
>  IShape shape = ...;
>  shape.setFrame(...); // نمی‌تواند نامشخص باشد
>  IShapeCollection shapes = ...;
> // پارامترهای x، y، width و height نمی‌توانند Float.NaN باشند:
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
>  اما ویژگی‌های فریم IShape.RawFrame می‌توانند ناشناخته باشند. این منطقی است وقتی shape به placeholder مرتبط باشد. در این صورت مقادیر فریم ناشناخته از shape placeholder والد بازنویسی می‌شود. اگر برای آن shape placeholder والد وجود نداشته باشد، آن shape از مقادیر پیش‌فرض استفاده می‌کند هنگامی که فریم مؤثر را بر اساس IShape.RawFrame محاسبه می‌کند. مقادیر پیش‌فرض 0 و NullableBool.False برای x، y، width، height، flipH، flipV و rotationAngle هستند. برای مثال:
>  IShape shape = ...; // shape به placeholder مرتبط است
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // اکنون shape مقادیر x، y، height، flipH، flipV را از placeholder به ارث می‌برد و مقدار width=100 و rotationAngle=0 را بازنویسی می‌کند.
```

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

ویژگی‌های فریم shape را باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

مقدار هر ویژگی از نمونه IShapeFrame بازگردانده‌شده تعریف‌شده است (نه NaN و نه NotDefined). مقدار هر ویژگی از نمونه IShapeFrame اختصاص-یافته نیز باید تعریف‌شده باشد (نه NaN و نه NotDefined). می‌توانید مقادیر undefined را برای ویژگی‌های RawFrame تنظیم کنید.

**باز می‌گرداند:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

ویژگی‌های فریم shape را باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

مقدار هر ویژگی از نمونه IShapeFrame بازگردانده‌شده تعریف‌شده است (نه NaN و نه NotDefined). مقدار هر ویژگی از نمونه IShapeFrame اختصاص-یافته نیز باید تعریف‌شده باشد (نه NaN و نه NotDefined). می‌توانید مقادیر undefined را برای ویژگی‌های RawFrame تنظیم کنید.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک shape است، باز می‌گرداند. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**باز می‌گرداند:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

شیء ThreeDFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک shape است، باز می‌گرداند. فقط-خواندنی [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**باز می‌گرداند:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

شیء EffectFormat را که شامل اثرهای پیکسلی اعمال‌شده به یک shape است، باز می‌گرداند. فقط-خواندنی [IEffectFormat](../../com.aspose.slides/ieffectformat).

**باز می‌گرداند:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر کردن برای یک shape است، باز می‌گرداند. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**باز می‌گرداند:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

تصویر کوچک shape را باز می‌گرداند. به‌صورت پیش‌فرض از نوع ShapeThumbnailBounds.Shape استفاده می‌شود.

**باز می‌گرداند:**
[IImage](../../com.aspose.slides/iimage) - تصویر کوچک shape.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

تصویر کوچک shape را باز می‌گرداند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| bounds | int | نوع bounds تصویر کوچک shape. |
| scaleX | float | مقیاس X |
| scaleY | float | مقیاس Y |

**باز می‌گرداند:**
[IImage](../../com.aspose.slides/iimage) - تصویر کوچک shape یا null در صورتی که از ShapeThumbnailBounds.Appearance استفاده شود و shape دارای عناصر قابل مشاهده نباشد.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

تعیین می‌کند که آیا shape مخفی است. خواندنی-نوشتنی بولی.

**باز می‌گرداند:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

تعیین می‌کند که آیا shape مخفی است. خواندنی-نوشتنی بولی.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

موقعیت یک shape در ترتیب z را باز می‌گرداند. Shapes[0] shape را در عقب‌ترین موقعیت z باز می‌گرداند و Shapes[Shapes.Count - 1] shape را در جلوترین موقعیت باز می‌گرداند. فقط-خواندنی int.

**باز می‌گرداند:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

تعداد نقاط اتصال روی shape را باز می‌گرداند. فقط-خواندنی int.

**باز می‌گرداند:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

تعداد درجه‌های چرخش shape حول محور z را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. خواندنی-نوشتنی float.

--------------------

مقدار بازگردانده‌شده همیشه تعریف‌شده است (نه Float.NaN). مقدار اختصاص-یافته نیز باید تعریف‌شده باشد (نه Float.NaN). می‌توانید برای ویژگی‌های RawFrame مقادیر undefined تنظیم کنید.

**باز می‌گرداند:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

تعداد درجه‌های چرخش shape حول محور z را باز می‌گرداند یا تنظیم می‌کند. مقدار مثبت نشان‌دهنده چرخش ساعت‌گرد؛ مقدار منفی نشان‌دهنده چرخش پادساعت‌گرد است. خواندنی-نوشتنی float.

--------------------

مقدار بازگردانده‌شده همیشه تعریف‌شده است (نه Float.NaN). مقدار اختصاص-یافته نیز باید تعریف‌شده باشد (نه Float.NaN). می‌توانید برای ویژگی‌های RawFrame مقادیر undefined تنظیم کنید.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

مختصات x گوشه بالایی-چپ shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی float.

--------------------

مقدار بازگردانده‌شده همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص-یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونه RawFrame تنظیم شود.

**باز می‌گرداند:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

مختصات x گوشه بالایی-چپ shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی float.

--------------------

مقدار بازگردانده‌شده همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص-یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونه RawFrame تنظیم شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

مختصات y گوشه بالایی-چپ shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی float.

--------------------

مقدار بازگردانده‌شده همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص-یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونه RawFrame تنظیم شود.

**باز می‌گرداند:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

مختصات y گوشه بالایی-چپ shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی float.

--------------------

مقدار بازگردانده‌شده همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص-یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونه RawFrame تنظیم شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

عرض shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی float.

--------------------

مقدار بازگردانده‌شده همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص-یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونه RawFrame تنظیم شود.

**باز می‌گرداند:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

عرض shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی float.

--------------------

مقدار بازگردانده‌شده همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص-یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونه RawFrame تنظیم شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

ارتفاع shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی float.

--------------------

مقدار بازگردانده‌شده همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص-یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونه RawFrame تنظیم شود.

**باز می‌گرداند:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

ارتفاع shape را که بر حسب نقطه اندازه‌گیری می‌شود، باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی float.

--------------------

مقدار بازگردانده‌شده همیشه تعریف‌شده است و هرگز Float.NaN نیست. مقدار اختصاص-یافته نیز باید تعریف‌شده باشد؛ Float.NaN فقط برای ویژگی‌های یک نمونه RawFrame تنظیم شود.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

متن جایگزین مرتبط با یک shape را باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی String.

**باز می‌گرداند:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

متن جایگزین مرتبط با یک shape را باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی String.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

عنوان متن جایگزین مرتبط با یک shape را باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی String.

**باز می‌گرداند:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

عنوان متن جایگزین مرتبط با یک shape را باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی String.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

نام یک shape را باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی String.

**باز می‌گرداند:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

نام یک shape را باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی String.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

گزینه «Mark as decorative» را به صورت بولی خواندنی-نوشتنی تنظیم یا دریافت می‌کند.

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
public abstract void setDecorative(boolean value)
```

گزینه «Mark as decorative» را به صورت بولی خواندنی-نوشتنی تنظیم یا دریافت می‌کند.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

قفل‌های shape را باز می‌گرداند. فقط-خواندنی [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**باز می‌گرداند:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public long { get; }
```

یک شناسه داخلی scoped برای ارائه که برای افزونه‌ها یا کدهای دیگر در دسترس است را باز می‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس تغییر یابد، نباید به‌عنوان کلید یکتا دائم استفاده شود. فقط-خواندنی long. همچنین به \#getOfficeInteropShapeId.getOfficeInteropShapeId مراجعه کنید.

**باز می‌گرداند:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

شناسه یکتا scoped برای اسلاید را باز می‌گرداند که برای طول عمر shape ثابت است و اجازه می‌دهد PowerPoint یا کدهای interop به‌صورت قابل اعتماد به shape از هر نقطه‌ای در سند ارجاع دهند. فقط-خواندنی long. همچنین به \#getUniqueId.getUniqueId مراجعه کنید.

**باز می‌گرداند:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

تعیین می‌کند که آیا shape در یک گروه قرار دارد. فقط-خواندنی بولی.

--------------------

ویژگی \#getParentGroup.getParentGroup شیء parent GroupShape را اگر shape گروه‌بندی شده باشد، باز می‌گرداند.

**باز می‌گرداند:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

ویژگی مشخص می‌کند که shape چگونه در حالت نمایش سیاه-سفید رندر خواهد شد. خواندنی-نوشتنی [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**باز می‌گرداند:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

ویژگی مشخص می‌کند که shape چگونه در حالت نمایش سیاه-سفید رندر خواهد شد. خواندنی-نوشتنی [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

شیء parent GroupShape را اگر shape گروه‌بندی شده باشد، باز می‌گرداند. در غیر این صورت null بر می‌گرداند. فقط-خواندنی [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

ویژگی \#isGrouped.isGrouped تعیین می‌کند که آیا shape گروه‌بندی شده است.

**باز می‌گرداند:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

محتوای Shape را به‌صورت فایل SVG ذخیره می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | گزینه‌های تولید SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

یک shape placeholder پایه (shape ای از layout و/یا master slide که shape جاری از آن ارث‌بری شده) را باز می‌گرداند.

--------------------

> ```
> // دریافت تمام افکت‌های انیمیشن (master/layout/slide) شکل placeholder
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

اگر shape جاری ارث‌بری نشده باشد، مقدار null برگردانده می‌شود.

**باز می‌گرداند:**
[IShape](../../com.aspose.slides/ishape)