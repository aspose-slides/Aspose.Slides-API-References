---
title: IShape
second_title: مرجع API Aspose.Slides للغة Java
description: يمثل شكلًا على شريحة.
type: docs
url: /ar/com.aspose.slides/ishape/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

يمثل شكلاً على شريحة.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | يحدد ما إذا كان الشكل TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | إرجاع العنصر النائب لشكل. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | إضافة عنصر نائب جديد إذا لم يكن موجودًا وتعيين خصائص العنصر النائب إلى العنصر المحدد. |
| [removePlaceholder()](#removePlaceholder--) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [getCustomData()](#getCustomData--) | إرجاع البيانات المخصصة للشكل. |
| [getRawFrame()](#getRawFrame--) | إرجاع أو تعيين خصائص إطار الشكل الخام. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | إرجاع أو تعيين خصائص إطار الشكل الخام. |
| [getFrame()](#getFrame--) | إرجاع أو تعيين خصائص إطار الشكل. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | إرجاع أو تعيين خصائص إطار الشكل. |
| [getLineFormat()](#getLineFormat--) | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. |
| [getThreeDFormat()](#getThreeDFormat--) | إرجاع كائن ThreeDFormat الذي يحتوي على خصائص تنسيق الخط للشكل. |
| [getEffectFormat()](#getEffectFormat--) | إرجاع كائن EffectFormat الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل. |
| [getFillFormat()](#getFillFormat--) | إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. |
| [getImage()](#getImage--) | إرجاع صورة مصغرة للشكل. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | إرجاع صورة مصغرة للشكل. |
| [getHidden()](#getHidden--) | يحدد ما إذا كان الشكل مخفيًا. |
| [setHidden(boolean value)](#setHidden-boolean-) | يحدد ما إذا كان الشكل مخفيًا. |
| [getZOrderPosition()](#getZOrderPosition--) | إرجاع موضع الشكل في ترتيب Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | إرجاع عدد نقاط الاتصال على الشكل. |
| [getRotation()](#getRotation--) | إرجاع أو تعيين عدد الدرجات التي يدور بها الشكل حول محور Z. |
| [setRotation(float value)](#setRotation-float-) | إرجاع أو تعيين عدد الدرجات التي يدور بها الشكل حول محور Z. |
| [getX()](#getX--) | الحصول على أو تعيين إحداثي X للزاوية العلوية اليسرى للشكل، بوحدة النقاط. |
| [setX(float value)](#setX-float-) | الحصول على أو تعيين إحداثي X للزاوية العلوية اليسرى للشكل، بوحدة النقاط. |
| [getY()](#getY--) | الحصول على أو تعيين إحداثي Y للزاوية العلوية اليسرى للشكل، بوحدة النقاط. |
| [setY(float value)](#setY-float-) | الحصول على أو تعيين إحداثي Y للزاوية العلوية اليسرى للشكل، بوحدة النقاط. |
| [getWidth()](#getWidth--) | الحصول على أو تعيين عرض الشكل، بوحدة النقاط. |
| [setWidth(float value)](#setWidth-float-) | الحصول على أو تعيين عرض الشكل، بوحدة النقاط. |
| [getHeight()](#getHeight--) | الحصول على أو تعيين ارتفاع الشكل، بوحدة النقاط. |
| [setHeight(float value)](#setHeight-float-) | الحصول على أو تعيين ارتفاع الشكل، بوحدة النقاط. |
| [getAlternativeText()](#getAlternativeText--) | إرجاع أو تعيين النص البديل المرتبط بالشكل. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | إرجاع أو تعيين النص البديل المرتبط بالشكل. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. |
| [getName()](#getName--) | إرجاع أو تعيين اسم الشكل. |
| [setName(String value)](#setName-java.lang.String-) | إرجاع أو تعيين اسم الشكل. |
| [isDecorative()](#isDecorative--) | الحصول على أو تعيين خيار “وضع علامة كديكوري” من النوع قراءة/كتابة. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | الحصول على أو تعيين خيار “وضع علامة كديكوري” من النوع قراءة/كتابة. |
| [getShapeLock()](#getShapeLock--) | إرجاع أقفال الشكل. |
| [getUniqueId()](#getUniqueId--) | إرجاع معرف داخلي نطاق العرض مخصص لاستخدام الإضافات أو الكود الآخر. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | إرجاع معرف فريد للنطاق الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لPowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. |
| [isGrouped()](#isGrouped--) | يحدد ما إذا كان الشكل مجموعة. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | الخاصية تحدد كيف سيُعرض الشكل في وضعية أبيض وأسود. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | الخاصية تحدد كيف سيُعرض الشكل في وضعية أبيض وأسود. |
| [getParentGroup()](#getParentGroup--) | إرجاع كائن GroupShape الأب إذا كان الشكل مجموعة. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | حفظ محتوى الشكل كملف SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | حفظ محتوى الشكل كملف SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | إرجاع شكل عنصر نائب أساسي (الشكل من التخطيط أو الشريحة الرئيسية التي يُورث منها الشكل الحالي). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

يحدد ما إذا كان الشكل TextHolder. قراءة فقط منطقية.

**الإرجاع:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

إرجاع العنصر النائب للشكل. قراءة فقط [IPlaceholder](../../com.aspose.slides/iplaceholder).

**الإرجاع:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

إضافة عنصر نائب جديد إذا لم يكن موجودًا وتعيين خصائص العنصر النائب إلى العنصر المحدد.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | العنصر النائب لنسخ المحتوى منه. |

**الإرجاع:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - [IPlaceholder](../../com.aspose.slides/iplaceholder) جديد.

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

يحدد أن هذا الشكل ليس عنصرًا نائبًا.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

إرجاع البيانات المخصصة للشكل. قراءة فقط [ICustomData](../../com.aspose.slides/icustomdata).

**الإرجاع:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

إرجاع أو تعيين خصائص إطار الشكل الخام. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //أو
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //يمكن أن يؤدي مثل هذا الكود إلى مواقف غير واضحة. لذلك تمت إضافة قيود لاستخدام القيم غير المعرفة لـ IShape.getFrame(). يجب أن تكون قيم x و y والعرض والارتفاع و flipH و flipV وزاوية الدوران معرفة (ليست Float.NaN أو NullableBool.NotDefined). الآن يُظهر الكود المثال أعلاه استثناء ArgumentException استثناء.
>  //هذا ينطبق على حالات الاستخدام هذه:
>  IShape shape = ...;
>  shape.setFrame(...); // لا يمكن أن تكون غير معرفة
>  IShapeCollection shapes = ...;
>  // معلمات x و y والعرض والارتفاع لا يمكن أن تكون Float.NaN:
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
>  IShape shape = ...; // الشكل مرتبط بعنصر نائب
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // الآن يرث الشكل قيم x و y والارتفاع و flipH و flipV من العنصر النائب ويستبدل العرض=100 وزاوية الدوران=0.
```

**الإرجاع:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

إرجاع أو تعيين خصائص إطار الشكل الخام. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //أو
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //يمكن أن يؤدي مثل هذا الكود إلى مواقف غير واضحة. لذلك تمت إضافة قيود لاستخدام القيم غير المعرفة لـ IShape.getFrame(). يجب أن تكون قيم x و y والعرض والارتفاع و flipH و flipV وزاوية الدوران معرفة (ليس Float.NaN أو NullableBool.NotDefined). الآن يرمى الكود أعلاه استثناء ArgumentException.
>  //هذا ينطبق على حالات الاستخدام هذه:
>  IShape shape = ...;
>  shape.setFrame(...); // لا يمكن أن تكون غير معرفة
>  IShapeCollection shapes = ...;
>  // لا يمكن أن تكون معلمات x و y والعرض والارتفاع Float.NaN:
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
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // الآن يرث الشكل قيم x و y والارتفاع و flipH و flipV من العنصر النائب ويستبدل العرض=100 وزاوية الدوران=0.
> ```


**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

إرجاع أو تعيين خصائص إطار الشكل. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

قيمة كل خاصية في مثيل IShapeFrame المرجع ليست غير معرفة (ليست NaN أو NotDefined). يجب أن تكون قيمة كل خاصية في مثيل IShapeFrame المعين غير معرفة (يجب ألا تكون NaN أو NotDefined). يمكنك تعيين قيم غير معرفة لخصائص مثيل RawFrame.

**الإرجاع:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

إرجاع أو تعيين خصائص إطار الشكل. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

قيمة كل خاصية في مثيل IShapeFrame المرجع ليست غير معرفة (ليست NaN أو NotDefined). يجب أن تكون قيمة كل خاصية في مثيل IShapeFrame المعين غير معرفة (يجب ألا تكون NaN أو NotDefined). يمكنك تعيين قيم غير معرفة لخصائص مثيل RawFrame.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

إرجاع كائن ThreeDFormat الذي يحتوي على خصائص تنسيق الخط للشكل. قراءة فقط [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**الإرجاع:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

إرجاع كائن EffectFormat الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل. قراءة فقط [IEffectFormat](../../com.aspose.slides/ieffectformat).

**الإرجاع:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. قراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

إرجاع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كقيمة افتراضية.

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - صورة مصغرة للشكل.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

إرجاع صورة مصغرة للشكل.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| bounds | int | نوع حدود الصورة المصغرة. |
| scaleX | float | مقياس X |
| scaleY | float | مقياس Y |

**الإرجاع:**
[IImage](../../com.aspose.slides/iimage) - صورة مصغرة للشكل أو null إذا استُخدم ShapeThumbnailBounds.Appearance وكان الشكل لا يحتوي على عناصر مرئية.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة منطقية.

**الإرجاع:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة منطقية.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

إرجاع موضع الشكل في ترتيب Z. Shapes[0] تُعيد الشكل في مؤخرة الترتيب، و Shapes[Shapes.Count - 1] تُعيد الشكل في مقدمة الترتيب. قراءة فقط عدد صحيح.

**الإرجاع:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

إرجاع عدد نقاط الاتصال على الشكل. قراءة فقط عدد صحيح.

**الإرجاع:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

إرجاع أو تعيين عدد الدرجات التي يدور بها الشكل حول محور Z. القيمة الموجبة تدل على دوران باتجاه عقارب الساعة؛ السالبة تدل على دوران عكس اتجاه العقارب. قراءة/كتابة عدد عشري.

--------------------

القيمة المرجعة دائمًا معرفة (ليست Float.NaN). يجب أن تكون القيمة المعينة معرفة (ليست Float.NaN). يمكنك تعيين قيم غير معرفة لخصائص مثيل RawFrame.

**الإرجاع:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

إرجاع أو تعيين عدد الدرجات التي يدور بها الشكل حول محور Z. القيمة الموجبة تدل على دوران باتجاه عقارب الساعة؛ السالبة تدل على دوران عكس اتجاه العقارب. قراءة/كتابة عدد عشري.

--------------------

القيمة المرجعة دائمًا معرفة (ليست Float.NaN). يجب أن تكون القيمة المعينة معرفة (ليست Float.NaN). يمكنك تعيين قيم غير معرفة لخصائص مثيل RawFrame.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

الحصول على أو تعيين إحداثي X للزاوية العلوية اليسرى للشكل، بوحدة النقاط. قراءة/كتابة عدد عشري.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعينة معرفة أيضًا؛ لا تقم بتعيين Float.NaN إلا لخصائص مثيل RawFrame.

**الإرجاع:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

الحصول على أو تعيين إحداثي X للزاوية العلوية اليسرى للشكل، بوحدة النقاط. قراءة/كتابة عدد عشري.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعينة معرفة أيضًا؛ لا تقم بتعيين Float.NaN إلا لخصائص مثيل RawFrame.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

الحصول على أو تعيين إحداثي Y للزاوية العلوية اليسرى للشكل، بوحدة النقاط. قراءة/كتابة عدد عشري.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعينة معرفة أيضًا؛ لا تقم بتعيين Float.NaN إلا لخصائص مثيل RawFrame.

**الإرجاع:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

الحصول على أو تعيين إحداثي Y للزاوية العلوية اليسرى للشكل، بوحدة النقاط. قراءة/كتابة عدد عشري.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعينة معرفة أيضًا؛ لا تقم بتعيين Float.NaN إلا لخصائص مثيل RawFrame.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

الحصول على أو تعيين عرض الشكل، بوحدة النقاط. قراءة/كتابة عدد عشري.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعينة معرفة أيضًا؛ لا تقم بتعيين Float.NaN إلا لخصائص مثيل RawFrame.

**الإرجاع:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

الحصول على أو تعيين عرض الشكل، بوحدة النقاط. قراءة/كتابة عدد عشري.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعينة معرفة أيضًا؛ لا تقم بتعيين Float.NaN إلا لخصائص مثيل RawFrame.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

الحصول على أو تعيين ارتفاع الشكل، بوحدة النقاط. قراءة/كتابة عدد عشري.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعينة معرفة أيضًا؛ لا تقم بتعيين Float.NaN إلا لخصائص مثيل RawFrame.

**الإرجاع:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

الحصول على أو تعيين ارتفاع الشكل، بوحدة النقاط. قراءة/كتابة عدد عشري.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعينة معرفة أيضًا؛ لا تقم بتعيين Float.NaN إلا لخصائص مثيل RawFrame.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

إرجاع أو تعيين النص البديل المرتبط بالشكل. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

إرجاع أو تعيين النص البديل المرتبط بالشكل. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

إرجاع أو تعيين اسم الشكل. قراءة/كتابة String.

**الإرجاع:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```




```

إرجاع أو تعيين اسم الشكل. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

الحصول على أو تعيين خيار “وضع علامة كديكوري” من النوع قراءة/كتابة منطقية.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
boolean

### setDecorative(boolean value) {#setDecorative-boolean-}
```
public abstract void setDecorative(boolean value)
```

الحصول على أو تعيين خيار “وضع علامة كديكوري” من النوع قراءة/كتابة منطقية.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

إرجاع أقفال الشكل. قراءة فقط [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**الإرجاع:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

إرجاع معرف داخلي نطاق العرض مخصص لاستخدام الإضافات أو الكود الآخر. نظرًا لأنه يمكن إعادة تعيينه من قبل المستخدم أو برمجيًا، يجب عدم اعتباره مفتاحًا فريدًا دائمًا. قراءة فقط long. راجع أيضًا \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**الإرجاع:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

إرجاع معرف فريد للنطاق الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لPowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. قراءة فقط long. راجع أيضًا \#getUniqueId.getUniqueId.

**الإرجاع:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

يحدد ما إذا كان الشكل مجموعة. قراءة فقط منطقية.

--------------------

خاصية \#getParentGroup.getParentGroup تُعيد كائن GroupShape الأب إذا كان الشكل مجموعة.

**الإرجاع:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public 



```

الخاصية تحدد كيف سيُعرض الشكل في وضعية أبيض وأسود. قراءة/كتابة [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**الإرجاع:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

الخاصية تحدد كيف سيُعرض الشكل في وضعية أبيض وأسود. قراءة/كتابة [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

إرجاع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا تُعيد null. قراءة فقط [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

خاصية \#isGrouped.isGrouped تحدد ما إذا كان الشكل مجموعة.

**الإرجاع:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

حفظ محتوى الشكل كملف SVG.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الهدف |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

حفظ محتوى الشكل كملف SVG.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الهدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | خيارات توليد SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public 



```

إرجاع شكل عنصر نائب أساسي (الشكل من التخطيط أو الشريحة الرئيسية التي يُورث منها الشكل الحالي).

--------------------

> ```
> // الحصول على جميع التأثيرات المتحركة (master/layout/slide) للعنصر النائب
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

يتم إرجاع null إذا لم يكن الشكل الحالي مُوروثًا.

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)