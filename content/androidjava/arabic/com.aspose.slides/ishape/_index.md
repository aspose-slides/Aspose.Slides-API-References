---
title: IShape
second_title: Aspose.Slides لنظام Android عبر مرجع API لـ Java
description: يمثل شكلاً على الشريحة.
type: docs
url: /ar/com.aspose.slides/ishape/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

يمثل شكلًا على الشريحة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | يحدد ما إذا كان الشكل TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | يُعيد العنصر النائب للشكل. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | يضيف عنصرًا نائبًا جديدًا إذا لم يوجد ويضبط خصائص العنصر النائب إلى المحدد. |
| [removePlaceholder()](#removePlaceholder--) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [getCustomData()](#getCustomData--) | يُعيد البيانات المخصصة للشكل. |
| [getRawFrame()](#getRawFrame--) | يُعيد أو يضبط خصائص إطار الشكل الخام. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | يُعيد أو يضبط خصائص إطار الشكل الخام. |
| [getFrame()](#getFrame--) | يُعيد أو يضبط خصائص إطار الشكل. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | يُعيد أو يضبط خصائص إطار الشكل. |
| [getLineFormat()](#getLineFormat--) | يُعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. |
| [getThreeDFormat()](#getThreeDFormat--) | يُعيد كائن ThreeDFormat الذي يحتوي على خصائص تنسيق الخط للشكل. |
| [getEffectFormat()](#getEffectFormat--) | يُعيد كائن EffectFormat الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل. |
| [getFillFormat()](#getFillFormat--) | يُعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. |
| [getImage()](#getImage--) | يُعيد صورة مصغرة للشكل. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | يُعيد صورة مصغرة للشكل. |
| [getHidden()](#getHidden--) | يحدد ما إذا كان الشكل مخفيًا. |
| [setHidden(boolean value)](#setHidden-boolean-) | يحدد ما إذا كان الشكل مخفيًا. |
| [getZOrderPosition()](#getZOrderPosition--) | يُعيد موضع الشكل في ترتيب z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | يُعيد عدد مواقع الاتصال على الشكل. |
| [getRotation()](#getRotation--) | يُعيد أو يضبط عدد درجات دوران الشكل المحدد حول محور z. |
| [setRotation(float value)](#setRotation-float-) | يُعيد أو يضبط عدد درجات دوران الشكل المحدد حول محور z. |
| [getX()](#getX--) | يحصل أو يضبط الإحداثي السيني للزاوية اليسرى العليا للشكل، مقاسًا بالنقاط. |
| [setX(float value)](#setX-float-) | يحصل أو يضبط الإحداثي السيني للزاوية اليسرى العليا للشكل، مقاسًا بالنقاط. |
| [getY()](#getY--) | يحصل أو يضبط الإحداثي الصادي للزاوية اليسرى العليا للشكل، مقاسًا بالنقاط. |
| [setY(float value)](#setY-float-) | يحصل أو يضبط الإحداثي الصادي للزاوية اليسرى العليا للشكل، مقاسًا بالنقاط. |
| [getWidth()](#getWidth--) | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط. |
| [setWidth(float value)](#setWidth-float-) | يحصل أو يضبط عرض الشكل، مقاسًا بالنقاط. |
| [getHeight()](#getHeight--) | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط. |
| [setHeight(float value)](#setHeight-float-) | يحصل أو يضبط ارتفاع الشكل، مقاسًا بالنقاط. |
| [getAlternativeText()](#getAlternativeText--) | يُعيد أو يضبط النص البديل المرتبط بالشكل. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | يُعيد أو يضبط النص البديل المرتبط بالشكل. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | يُعيد أو يضبط عنوان النص البديل المرتبط بالشكل. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | يُعيد أو يضبط عنوان النص البديل المرتبط بالشكل. |
| [getName()](#getName--) | يُعيد أو يضبط اسم الشكل. |
| [setName(String value)](#setName-java.lang.String-) | يُعيد أو يضبط اسم الشكل. |
| [isDecorative()](#isDecorative--) | يحصل أو يضبط خيار 'Mark as decorative' للقراءة/الكتابة boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | يحصل أو يضبط خيار 'Mark as decorative' للقراءة/الكتابة boolean. |
| [getShapeLock()](#getShapeLock--) | يُعيد أقفال الشكل. |
| [getUniqueId()](#getUniqueId--) | يُعيد معرفًا داخليًا نطاقه العرض التقديمي مخصصًا للاستخدام من قبل الإضافات أو غيرها من الشيفرات. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | يُعيد معرفًا فريدًا نطاقه الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل بشكل موثوق من أي مكان في المستند. |
| [isGrouped()](#isGrouped--) | يحدد ما إذا كان الشكل مجموعة. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | الخاصية تحدد كيفية عرض الشكل في وضع اللونين الأبيض والأسود. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | الخاصية تحدد كيفية عرض الشكل في وضع اللونين الأبيض والأسود. |
| [getParentGroup()](#getParentGroup--) | يُعيد كائن GroupShape الأب إذا كان الشكل مجموعة. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | يحفظ محتوى الشكل كملف SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | يحفظ محتوى الشكل كملف SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | يُعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

يحدد ما إذا كان الشكل TextHolder. للقراءة فقط boolean.

**الإرجاع:**  
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

يُعيد العنصر النائب للشكل. للقراءة فقط [IPlaceholder](../../com.aspose.slides/iplaceholder).

**الإرجاع:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

يضيف عنصرًا نائبًا جديدًا إذا لم يوجد ويضبط خصائص العنصر النائب إلى المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | العنصر النائب لنسخ المحتوى منه. |

**الإرجاع:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder) - جديد [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

يحدد أن هذا الشكل ليس عنصرًا نائبًا.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

يُعيد البيانات المخصصة للشكل. للقراءة فقط [ICustomData](../../com.aspose.slides/icustomdata).

**الإرجاع:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

يُعيد أو يضبط خصائص إطار الشكل الخام. للقراءة/الكتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //أو
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //مثل هذا الكود يمكن أن يؤدي إلى أوضاع غير واضحة. لذا تم إضافة قيود لاستخدام القيم غير المعرفة لـ IShape.getFrame(). يجب تعريف قيم x و y والعرض والارتفاع و flipH و flipV وزاوية الدوران (ليس Float.NaN أو NullableBool.NotDefined). الكود السابق الآن يرمي استثناء ArgumentException.
>  //ينطبق هذا على حالات الاستخدام التالية:
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
>  IShape shape = ...; // الشكل مرتبط بالمكان النائب
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // الآن يرث الشكل قيم x و y والارتفاع و flipH و flipV من المكوّن النائب ويتجاوز العرض=100 وزاوية الدوران=0.
```

**الإرجاع:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

يُعيد أو يضبط خصائص إطار الشكل الخام. للقراءة/الكتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //أو
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //يمكن أن يؤدي مثل هذا الكود إلى أوضاع غير واضحة. لذلك تم إضافة قيود لاستخدام القيم غير المعرفة لـ IShape.getFrame(). يجب أن تكون قيم x و y والعرض والارتفاع و flipH و flipV وزاوية الدوران معرفة (ليس Float.NaN أو NullableBool.NotDefined). الكود أعلاه الآن يرمي استثناء ArgumentException.
>  //ينطبق هذا على حالات الاستخدام التالية:
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
>  IShape shape = ...; // الشكل مرتبط بالمكان النائب
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // الآن يرث الشكل قيم x و y والارتفاع و flipH و flipV من العنصر النائب ويتجاوز العرض=100 وزاوية الدوران=0.
```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

يُعيد أو يضبط خصائص إطار الشكل. للقراءة/الكتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

قيمة كل خاصية في كائن IShapeFrame المعاد ليست غير معرفة (ليست NaN أو NotDefined). يجب أن تكون قيمة كل خاصية في كائن IShapeFrame المُسند غير معرفة (ليست NaN أو NotDefined). يمكنك تعيين قيم غير معرفة لخصائص كائن RawFrame.

**الإرجاع:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

يُعيد أو يضبط خصائص إطار الشكل. للقراءة/الكتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

قيمة كل خاصية في كائن IShapeFrame المعاد ليست غير معرفة (ليست NaN أو NotDefined). يجب أن تكون قيمة كل خاصية في كائن IShapeFrame المُسند غير معرفة (ليست NaN أو NotDefined). يمكنك تعيين قيم غير معرفة لخصائص كائن RawFrame.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

يُعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط للشكل. للقراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**الإرجاع:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

يُعيد كائن ThreeDFormat الذي يحتوي على خصائص تنسيق الخط للشكل. للقراءة فقط [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**الإرجاع:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

يُعيد كائن EffectFormat الذي يحتوي على التأثيرات البكسلية المطبقة على الشكل. للقراءة فقط [IEffectFormat](../../com.aspose.slides/ieffectformat).

**الإرجاع:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

يُعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة للشكل. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

يُعيد صورة مصغرة للشكل. ShapeThumbnailBounds.Shape نوع حدود الصورة المصغرة يُستخدم افتراضيًا.

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - صورة مصغرة للشكل.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

يُعيد صورة مصغرة للشكل.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| bounds | int | نوع حدود الصورة المصغرة. |
| scaleX | float | مقياس X |
| scaleY | float | مقياس Y |

**الإرجاع:**  
[IImage](../../com.aspose.slides/iimage) - صورة مصغرة للشكل أو null في حال استخدام ShapeThumbnailBounds.Appearance ولا يمتلك الشكل عناصر مرئية.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

يحدد ما إذا كان الشكل مخفيًا. للقراءة/الكتابة boolean.

**الإرجاع:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

يحدد ما إذا كان الشكل مخفيًا. للقراءة/الكتابة boolean.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

يُعيد موضع الشكل في ترتيب z. Shapes[0] يُعيد الشكل في خلفية ترتيب z، و Shapes[Shapes.Count - 1] يُعيد الشكل في مقدمة ترتيب z. للقراءة فقط int.

**الإرجاع:**  
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

يُعيد عدد مواقع الاتصال على الشكل. للقراءة فقط int.

**الإرجاع:**  
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

يُعيد أو يضبط عدد درجات دوران الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقرب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقرب الساعة. للقراءة/الكتابة float.

--------------------

القيمة المعادة دائمًا معرفة (ليست Float.NaN). يجب أن تكون القيمة المسندة معرفة (ليست Float.NaN). يمكنك تعيين قيم غير معرفة لخصائص كائن RawFrame.

**الإرجاع:**  
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

يُعيد أو يضبط عدد درجات دوران الشكل المحدد حول محور z. القيمة الموجبة تشير إلى دوران باتجاه عقرب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقرب الساعة. للقراءة/الكتابة float.

--------------------

القيمة المعادة دائمًا معرفة (ليست Float.NaN). يجب أن تكون القيمة المسندة معرفة (ليست Float.NaN). يمكنك تعيين قيم غير معرفة لخصائص كائن RawFrame.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

يحصل أو yضبط الإحداثي السيني للزاوية اليسرى العليا للشكل، مقاسًا بالنقاط. للقراءة/الكتابة float.

--------------------

القيمة المعادة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المسندة معرفة؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**الإرجاع:**  
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

يحصل أو yضبط الإحداثي السيني للزاوية اليسرى العليا للشكل، مقاسًا بالنقاط. للقراءة/الكتابة float.

--------------------

القيمة المعادة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المسندة معرفة؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

يحصل أو yضبط الإحداثي الصادي للزاوية اليسرى العليا للشكل، مقاسًا بالنقاط. للقراءة/الكتابة float.

--------------------

القيمة المعادة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المسندة معرفة؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**الإرجاع:**  
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

يحصل أو yضبط الإحداثي الصادي للزاوية اليسرى العليا للشكل، مقاسًا بالنقاط. للقراءة/الكتابة float.

--------------------

القيمة المعادة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المسندة معرفة؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

يحصل أو yضبط عرض الشكل، مقاسًا بالنقاط. للقراءة/الكتابة float.

--------------------

القيمة المعادة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المسندة معرفة؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**الإرجاع:**  
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

يحصل أو yضبط عرض الشكل، مقاسًا بالنقاط. للقراءة/الكتابة float.

--------------------

القيمة المعادة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المسندة معرفة؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

يحصل أو yضبط ارتفاع الشكل، مقاسًا بالنقاط. للقراءة/الكتابة float.

--------------------

القيمة المعادة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المسندة معرفة؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**الإرجاع:**  
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

يحصل أو yضبط ارتفاع الشكل، مقاسًا بالنقاط. للقراءة/الكتابة float.

--------------------

القيمة المعادة دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المسندة معرفة؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

يُعيد أو يضبط النص البديل المرتبط بالشكل. للقراءة/الكتابة String.

**الإرجاع:**  
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

يُعيد أو يضبط النص البديل المرتبط بالشكل. للقراءة/الكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

يُعيد أو يضبط عنوان النص البديل المرتبط بالشكل. للقراءة/الكتابة String.

**الإرجاع:**  
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

يُعيد أو يضبط عنوان النص البديل المرتبط بالشكل. للقراءة/الكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

يُعيد أو يضبط اسم الشكل. للقراءة/الكتابة String.

**الإرجاع:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

يُعيد أو يضبط اسم الشكل. للقراءة/الكتابة String.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

يحصل أو yضبط خيار 'Mark as decorative' للقراءة/الكتابة boolean.

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

يحصل أو yضبط خيار 'Mark as decorative' للقراءة/الكتابة boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public abstract IBaseShapeLock getShapeLock()
```

يُعيد أقفال الشكل. للقراءة فقط [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**الإرجاع:**  
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

يُعيد معرفًا داخليًا نطاقه العرض التقديمي مخصصًا للاستخدام من قبل الإضافات أو غيرها من الشيفرات. نظرًا لأن هذه القيمة يمكن أن يعيد تعيينها المستخدم أو برمجيًا، يجب عدم اعتبارها مفتاحًا فريدًا دائمًا. للقراءة فقط long. راجع أيضًا \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**الإرجاع:**  
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

يُعيد معرفًا فريدًا نطاقه الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالإشارة إلى الشكل بشكل موثوق من أي مكان في المستند. للقراءة فقط long. راجع أيضًا \#getUniqueId.getUniqueId.

**الإرجاع:**  
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

يحدد ما إذا كان الشكل مجموعة. للقراءة فقط boolean.

--------------------

الخاصية \#getParentGroup.getParentGroup تُعيد كائن GroupShape الأب إذا كان الشكل مجموعة.

**الإرجاع:**  
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public {  }  

```

الخاصية تحدد كيفية عرض الشكل في وضع اللونين الأبيض والأسود. للقراءة/الكتابة [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**الإرجاع:**  
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

الخاصية تحدد كيفية عرض الشكل في وضع اللونين الأبيض والأسود. للقراءة/الكتابة [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

يُعيد كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يُعيد null. للقراءة فقط [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

الخاصية \#isGrouped.isGrouped تحدد ما إذا كان الشكل مجموعة.

**الإرجاع:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

يحفظ محتوى الشكل كملف SVG.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الهدف |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

يحفظ محتوى الشكل كملف SVG.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الهدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | خيارات توليد SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

يُعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو الشريحة الرئيسية التي يرث منها الشكل الحالي).

--------------------

> ```
> // احصل على جميع التأثيرات المتحركة (master/layout/slide) للشكل النائب
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

يُعيد null إذا لم يكن الشكل الحالي موروثًا.

**الإرجاع:**  
[IShape](../../com.aspose.slides/ishape)