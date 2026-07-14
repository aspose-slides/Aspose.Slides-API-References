---
title: IShape
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک شکل روی اسلاید است.
type: docs
url: /fa/com.aspose.slides/ishape/
---
**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

نمایانگر یک شکل روی اسلاید است.

## متدها

| متد | توضیح |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | تعیین می‌کند که آیا شکل TextHolder است. |
| [getPlaceholder()](#getPlaceholder--) | placeholder را برای یک شکل برمی‌گرداند. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | اگر placeholder ای وجود نداشته باشد، placeholder جدیدی اضافه می‌کند و ویژگی‌های placeholder را به مورد مشخص شده تنظیم می‌کند. |
| [removePlaceholder()](#removePlaceholder--) | تعریف می‌کند که این شکل placeholder نیست. |
| [getCustomData()](#getCustomData--) | داده‌های سفارشی شکل را برمی‌گرداند. |
| [getRawFrame()](#getRawFrame--) | ویژگی‌های چارچوب شکل خام را برمی‌گرداند یا تنظیم می‌کند. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | ویژگی‌های چارچوب شکل خام را برمی‌گرداند یا تنظیم می‌کند. |
| [getFrame()](#getFrame--) | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [getLineFormat()](#getLineFormat--) | شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند. |
| [getThreeDFormat()](#getThreeDFormat--) | شیء ThreeDFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند. |
| [getEffectFormat()](#getEffectFormat--) | شیء EffectFormat که شامل اثرات پیکسلی اعمال‌شده به یک شکل است را برمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | شیء FillFormat که شامل ویژگی‌های قالب‌بندی پرکننده برای یک شکل است را برمی‌گرداند. |
| [getImage()](#getImage--) | تصویر کوچک شکل را برمی‌گرداند. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | تصویر کوچک شکل را برمی‌گرداند. |
| [getHidden()](#getHidden--) | تعیین می‌کند که آیا شکل مخفی است. |
| [setHidden(boolean value)](#setHidden-boolean-) | تعیین می‌کند که آیا شکل مخفی است. |
| [getZOrderPosition()](#getZOrderPosition--) | موقعیت یک شکل در ترتیب z را برمی‌گرداند. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | تعداد نقاط اتصال روی شکل را برمی‌گرداند. |
| [getRotation()](#getRotation--) | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. |
| [setRotation(float value)](#setRotation-float-) | تعداد درجه‌های چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. |
| [getX()](#getX--) | مختصات x گوشه بالایی سمت چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setX(float value)](#setX-float-) | مختصات x گوشه بالایی سمت چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getY()](#getY--) | مختصات y گوشه بالایی سمت چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setY(float value)](#setY-float-) | مختصات y گوشه بالایی سمت چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getWidth()](#getWidth--) | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setWidth(float value)](#setWidth-float-) | عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getHeight()](#getHeight--) | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [setHeight(float value)](#setHeight-float-) | ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. |
| [getAlternativeText()](#getAlternativeText--) | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [getName()](#getName--) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [setName(String value)](#setName-java.lang.String-) | نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. |
| [isDecorative()](#isDecorative--) | گزینه 'Mark as decorative' که نوع boolean خواندنی/نوشتنی است را برمی‌گرداند یا تنظیم می‌کند. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | گزینه 'Mark as decorative' که نوع boolean خواندنی/نوشتنی است را برمی‌گرداند یا تنظیم می‌کند. |
| [getShapeLock()](#getShapeLock--) | قفل‌های شکل را برمی‌گرداند. |
| [getUniqueId()](#getUniqueId--) | شناسه داخلی محدوده ارائه‌ای را که برای استفاده توسط افزونه‌ها یا کدهای دیگر منظور شده است، برمی‌گرداند. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | شناسه یکتا محدوده اسلاید را که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد شکل را از هرجای سند به‌طور قابل اعتماد ارجاع دهند، برمی‌گرداند. |
| [isGrouped()](#isGrouped--) | تعیین می‌کند که آیا شکل گروه‌بندی شده است. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. |
| [getParentGroup()](#getParentGroup--) | اگر شکل گروه‌بندی شده باشد، شیء GroupShape والد را برمی‌گرداند. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | محتواي Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | محتواي Shape را به عنوان فایل SVG ذخیره می‌کند. |
| [getBasePlaceholder()](#getBasePlaceholder--) | یک شکل placeholder پایه (شکل از چیدمان و/یا اسلاید اصلی که شکل جاری از آن ارث‌برگرفته) را برمی‌گرداند. |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

تعیین می‌کند که آیا شکل TextHolder است. boolean فقط-خواندنی.

**باز می‌گرداند:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

placeholder را برای یک شکل برمی‌گرداند. فقط-خواندنی [IPlaceholder](../../com.aspose.slides/iplaceholder).

**باز می‌گرداند:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

اگر placeholder ای وجود نداشته باشد، placeholder جدیدی اضافه می‌کند و ویژگی‌های placeholder را به مورد مشخص شده تنظیم می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | placeholder برای کپی محتوای آن. |

**باز می‌گرداند:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - [IPlaceholder](../../com.aspose.slides/iplaceholder) جدید.

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

تعریف می‌کند که این شکل placeholder نیست.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

داده‌های سفارشی شکل را برمی‌گرداند. فقط-خواندنی [ICustomData](../../com.aspose.slides/icustomdata).

**باز می‌گرداند:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

ویژگی‌های چارچوب شکل خام را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------
> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //یا
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //چنین کدی می‌تواند به وضعیت‌های نامشخص منجر شود. بنابراین محدودیت‌هایی برای استفاده از مقادیر تعریف‌نشده در IShape.getFrame() اضافه شده است. مقادیر x، y، width، height، flipH، flipV و rotationAngle باید تعریف شوند (نه Float.NaN یا NullableBool.NotDefined). کد مثال بالا اکنون استثنای ArgumentException را پرتاب می‌کند.
>  //این موارد در موارد استفاده زیر اعمال می‌شود:
>  IShape shape = ...;
>  shape.setFrame(...); //نمی‌تواند تعریف‌نشده باشد
>  IShapeCollection shapes = ...;
>  //پارامترهای x، y، width، height نمی‌توانند Float.NaN باشند:
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; //شکل به placeholder متصل است
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); //اکنون شکل مقادیر x، y، height، flipH، flipV را از placeholder ارث می‌برد و width=100 و rotationAngle=0 را بازنویسی می‌کند.
> ```

**باز می‌گرداند:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

ویژگی‌های چارچوب شکل خام را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------
> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //یا
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //کد مشابه می‌تواند به وضعیت‌های نامشخص منجر شود. بنابراین محدودیت‌هایی برای استفاده از مقادیر تعریف‌نشده در IShape.getFrame() اضافه شده است. مقادیر x، y، width، height، flipH، flipV و rotationAngle باید تعریف شوند (نه Float.NaN یا NullableBool.NotDefined). کد نمونه بالا اکنون استثنای ArgumentException را پرتاب می‌کند.
>  //این موارد در این حالات استفاده اعمال می‌شود:
>  IShape shape = ...;
>  shape.setFrame(...); // نمی‌تواند تعریف‌نشده باشد
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // شکل به placeholder متصل است
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // اکنون شکل مقادیر x، y، height، flipH، flipV را از placeholder به ارث می‌برد و width=100 و rotationAngle=0 را بازنویسی می‌کند.
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

مقدار هر ویژگی از نمونه IShapeFrame بازگردانده‌شده تعریف‌شده است (NaN یا NotDefined نیست). مقدار هر ویژگی از نمونه IShapeFrame اختصاص داده‌شده باید تعریف‌شده باشد (نباید NaN یا NotDefined باشد). می‌توانید مقادیر تعریف‌نشده را برای ویژگی‌های نمونه RawFrame تنظیم کنید.

**باز می‌گرداند:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

ویژگی‌های چارچوب شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

مقدار هر ویژگی از نمونه IShapeFrame بازگردانده‌شده تعریف‌شده است (NaN یا NotDefined نیست). مقدار هر ویژگی از نمونه IShapeFrame اختصاص داده‌شده باید تعریف‌شده باشد (نباید NaN یا NotDefined باشد). می‌توانید مقادیر تعریف‌نشده را برای ویژگی‌های نمونه RawFrame تنظیم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

شیء LineFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**باز می‌گرداند:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

شیء ThreeDFormat که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است را برمی‌گرداند. فقط-خواندنی [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**باز می‌گرداند:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

شیء EffectFormat که شامل اثرات پیکسلی اعمال‌شده به یک شکل است را برمی‌گرداند. فقط-خواندنی [IEffectFormat](../../com.aspose.slides/ieffectformat).

**باز می‌گرداند:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

شیء FillFormat که شامل ویژگی‌های قالب‌بندی پرکننده برای یک شکل است را برمی‌گرداند. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**باز می‌گرداند:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

تصویر کوچک شکل را برمی‌گرداند. نوع ShapeThumbnailBounds.Shape به‌طور پیش‌فرض استفاده می‌شود.

**باز می‌گرداند:**
[IImage](../../com.aspose.slides/iimage) - تصویر کوچک شکل.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

تصویر کوچک شکل را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bounds | int | نوع محدوده تصویر کوچک شکل. |
| scaleX | float | مقیاس X |
| scaleY | float | مقیاس Y |

**باز می‌گرداند:**
[IImage](../../com.aspose.slides/iimage) - تصویر کوچک شکل یا null در صورتی که ShapeThumbnailBounds.Appearance استفاده شود و شکل عناصر نمایان نداشته باشد.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

تعیین می‌کند که آیا شکل مخفی است. خواندنی/نوشتنی boolean.

**باز می‌گرداند:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

تعیین می‌کند که آیا شکل مخفی است. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

موقعیت یک شکل در ترتیب z را برمی‌گرداند. Shapes[0] شکل در پشت ترتیب z را برمی‌گرداند و Shapes[Shapes.Count - 1] شکل در جلوی ترتیب z را برمی‌گرداند. فقط-خواندنی int.

**باز می‌گرداند:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

تعداد نقاط اتصال روی شکل را برمی‌گرداند. فقط-خواندنی int.

**باز می‌گرداند:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

تعداد درجه‌های چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشاندهنده چرخش ساعت‌گرد؛ مقدار منفی نشاندهنده چرخش پادساعت‌گرد است. خواندنی/نوشتنی float.

--------------------
مقدار بازگشتی همیشه تعریف شده است (Float.NaN نیست). مقدار اختصاص داده شده باید تعریف شده باشد (نه Float.NaN). می‌توانید مقادیر تعریف‌نشده را برای ویژگی‌های نمونه RawFrame تنظیم کنید.

**باز می‌گرداند:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

تعداد درجه‌های چرخش شکل مشخص شده حول محور z را برمی‌گرداند یا تنظیم می‌کند. مقدار مثبت نشاندهنده چرخش ساعت‌گرد؛ مقدار منفی نشاندهنده چرخش پادساعت‌گرد است. خواندنی/نوشتنی float.

--------------------
مقدار بازگشتی همیشه تعریف شده است (Float.NaN نیست). مقدار اختصاص داده شده باید تعریف شده باشد (نه Float.NaN). می‌توانید مقادیر تعریف‌نشده را برای ویژگی‌های نمونه RawFrame تنظیم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

مختصات x گوشه بالایی سمت چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

--------------------
مقدار بازگشتی همیشه تعریف شده است و هرگز Float.NaN نیست. مقدار اختصاص داده شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame تنظیم کنید.

**باز می‌گرداند:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

مختصات x گوشه بالایی سمت چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

--------------------
مقدار بازگشتی همیشه تعریف شده است و هرگز Float.NaN نیست. مقدار اختصاص داده شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame تنظیم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

مختصات y گوشه بالایی سمت چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

--------------------
مقدار بازگشتی همیشه تعریف شده است و هرگز Float.NaN نیست. مقدار اختصاص داده شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame تنظیم کنید.

**باز می‌گرداند:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

مختصات y گوشه بالایی سمت چپ شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

--------------------
مقدار بازگشتی همیشه تعریف شده است و هرگز Float.NaN نیست. مقدار اختصاص داده شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame تنظیم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

--------------------
مقدار بازگشتی همیشه تعریف شده است و هرگز Float.NaN نیست. مقدار اختصاص داده شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame تنظیم کنید.

**باز می‌گرداند:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

عرض شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

--------------------
مقدار بازگشتی همیشه تعریف شده است و هرگز Float.NaN نیست. مقدار اختصاص داده شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame تنظیم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

--------------------
مقدار بازگشتی همیشه تعریف شده است و هرگز Float.NaN نیست. مقدار اختصاص داده شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame تنظیم کنید.

**باز می‌گرداند:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

ارتفاع شکل را که بر حسب پوینت اندازه‌گیری می‌شود، برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی float.

--------------------
مقدار بازگشتی همیشه تعریف شده است و هرگز Float.NaN نیست. مقدار اختصاص داده شده نیز باید تعریف‌شده باشد؛ Float.NaN را فقط برای ویژگی‌های یک نمونه RawFrame تنظیم کنید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**باز می‌گرداند:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**باز می‌گرداند:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

عنوان متن جایگزین مرتبط با یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**باز می‌گرداند:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

نام یک شکل را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

گزینه 'Mark as decorative' که نوع boolean خواندنی/نوشتنی است را برمی‌گرداند یا تنظیم می‌کند.

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

گزینه 'Mark as decorative' که نوع boolean خواندنی/نوشتنی است را برمی‌گرداند یا تنظیم می‌کند.

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
public abstract IBaseShapeLock getShapeLock()
```

قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**باز می‌گرداند:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

شناسه داخلی محدوده ارائه‌ای را که برای استفاده توسط افزونه‌ها یا کدهای دیگر منظور شده است، برمی‌گرداند. چون این مقدار می‌تواند توسط کاربر یا برنامه‌نویس مجدداً اختصاص داده شود، نباید به‌عنوان کلید یکتا دائم درنظر گرفته شود. فقط-خواندنی long. همچنین مراجعه کنید به \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**باز می‌گرداند:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

شناسه یکتا محدوده اسلاید را که در طول عمر شکل ثابت می‌ماند و به PowerPoint یا کدهای interop اجازه می‌دهد شکل را از هرجای سند به‌طور قابل اعتماد ارجاع دهند، برمی‌گرداند. فقط-خواندنی long. همچنین مراجعه کنید به \#getUniqueId.getUniqueId.

**باز می‌گرداند:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

تعیین می‌کند که آیا شکل گروه‌بندی شده است. فقط-خواندنی boolean.

--------------------
ویژگی \#getParentGroup.getParentGroup شیء GroupShape والد را اگر شکل گروه‌بندی شده باشد برمی‌گرداند.

**باز می‌گرداند:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. خواندنی/نوشتنی [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**باز می‌گرداند:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

ویژگی مشخص می‌کند که یک شکل چگونه در حالت نمایش سیاه-سفید رندر شود. خواندنی/نوشتنی [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

شیء GroupShape والد را اگر شکل گروه‌بندی شده باشد برمی‌گرداند. در غیر این صورت null برمی‌گرداند. فقط-خواندنی [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------
ویژگی \#isGrouped.isGrouped تعیین می‌کند که آیا شکل گروه‌بندی شده است.

**باز می‌گرداند:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

محتواي Shape را به عنوان فایل SVG ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

محتواي Shape را به عنوان فایل SVG ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | گزینه‌های تولید SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

یک شکل placeholder پایه (شکل از چیدمان و/یا اسلاید اصلی که شکل جاری از آن ارث‌برگرفته) را برمی‌گرداند.

--------------------
> ```
> // دریافت تمام اثرات انیمیشنی (master/layout/slide) شکل placeholder
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
اگر شکل جاری ارث‌برگرفته نباشد، مقدار null برگردانده می‌شود.

**باز می‌گرداند:**
[IShape](../../com.aspose.slides/ishape)