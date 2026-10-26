---
title: Shape
second_title: مرجع API لـ Aspose.Slides for Java
description: يمثل شكلاً على الشريحة.
type: docs
url: /ar/com.aspose.slides/shape/
---
**الوراثة:**  
java.lang.Object

**جميع الواجهات المنفذة:**  
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject  
```
public class Shape implements IShape, IDOMObject
```

يمثل شكلاً على شريحة.  
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | تحدد ما إذا كان الشكل هو TextHolder_PPT. |
| [getPlaceholder()](#getPlaceholder--) | إرجاع العنصر النائب لشكل. |
| [removePlaceholder()](#removePlaceholder--) | تحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | إضافة عنصر نائب جديد إذا لم يكن موجودًا وتعيين خصائص العنصر النائب إلى العنصر المحدد. |
| [getBasePlaceholder()](#getBasePlaceholder--) | إرجاع شكل عنصر نائب أساسي (الشكل من التخطيط و/أو الشريحة الرئيسية الذي يُورث منه الشكل الحالي). |
| [getCustomData()](#getCustomData--) | إرجاع البيانات المخصصة للشكل. |
| [getRawFrame()](#getRawFrame--) | إرجاع أو تعيين خصائص إطار الشكل الخام. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | إرجاع أو تعيين خصائص إطار الشكل الخام. |
| [getFrame()](#getFrame--) | إرجاع أو تعيين خصائص إطار الشكل. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | إرجاع أو تعيين خصائص إطار الشكل. |
| [getLineFormat()](#getLineFormat--) | إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. |
| [getThreeDFormat()](#getThreeDFormat--) | إرجاع كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد لشكل. |
| [getEffectFormat()](#getEffectFormat--) | إرجاع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على شكل. |
| [getFillFormat()](#getFillFormat--) | إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل. |
| [getImage()](#getImage--) | إرجاع صورة مصغرة للشكل. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | إرجاع صورة مصغرة للشكل. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | حفظ محتوى الشكل كملف SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | حفظ محتوى الشكل كملف SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | إرجاع أو تعيين الارتباط التشعبي المحدد للنقر بالفأرة. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | إرجاع أو تعيين الارتباط التشعبي المحدد للنقر بالفأرة. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | إرجاع أو تعيين الارتباط التشعبي المحدد للتحريك فوق الفأرة. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | إرجاع أو تعيين الارتباط التشعبي المحدد للتحريك فوق الفأرة. |
| [getHyperlinkManager()](#getHyperlinkManager--) | إرجاع مدير الارتباطات التشعبية. |
| [getHidden()](#getHidden--) | تحدد ما إذا كان الشكل مخفيًا. |
| [setHidden(boolean value)](#setHidden-boolean-) | تحدد ما إذا كان الشكل مخفيًا. |
| [getZOrderPosition()](#getZOrderPosition--) | إرجاع موضع الشكل في ترتيب الـ z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | إرجاع عدد نقاط الربط على الشكل. |
| [getRotation()](#getRotation--) | إرجاع أو تعيين عدد الدرجات التي يدور فيها الشكل حول محور الـ z. |
| [setRotation(float value)](#setRotation-float-) | إرجاع أو تعيين عدد الدرجات التي يدور فيها الشكل حول محور الـ z. |
| [getX()](#getX--) | الحصول على أو تعيين إحداثي x للزاوية العلوية اليسرى للشكل، بوحدات النقاط. |
| [setX(float value)](#setX-float-) | الحصول على أو تعيين إحداثي x للزاوية العلوية اليسرى للشكل، بوحدات النقاط. |
| [getY()](#getY--) | الحصول على أو تعيين إحداثي y للزاوية العلوية اليسرى للشكل، بوحدات النقاط. |
| [setY(float value)](#setY-float-) | الحصول على أو تعيين إحداثي y للزاوية العلوية اليسرى للشكل، بوحدات النقاط. |
| [getWidth()](#getWidth--) | الحصول على أو تعيين عرض الشكل، بوحدات النقاط. |
| [setWidth(float value)](#setWidth-float-) | الحصول على أو تعيين عرض الشكل، بوحدات النقاط. |
| [getHeight()](#getHeight--) | الحصول على أو تعيين ارتفاع الشكل، بوحدات النقاط. |
| [setHeight(float value)](#setHeight-float-) | الحصول على أو تعيين ارتفاع الشكل، بوحدات النقاط. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | الخاصية تحدد كيف سيتم عرض الشكل في وضع العرض بالأبيض والأسود. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | الخاصية تحدد كيف سيتم عرض الشكل في وضع العرض بالأبيض والأسود. |
| [getUniqueId()](#getUniqueId--) | إرجاع معرف داخلي يخص العرض يُقصد به الاستخدام من قبل الإضافات أو الشفرات الأخرى. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | إرجاع معرف فريد خاص بالشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل من أي مكان في المستند. |
| [getAlternativeText()](#getAlternativeText--) | إرجاع أو تعيين النص البديل المرتبط بالشكل. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | إرجاع أو تعيين النص البديل المرتبط بالشكل. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. |
| [getName()](#getName--) | إرجاع أو تعيين اسم الشكل. |
| [setName(String value)](#setName-java.lang.String-) | إرجاع أو تعيين اسم الشكل. |
| [isDecorative()](#isDecorative--) | الحصول على أو تعيين خيار "وضع علامة كديكور" (قراءة/كتابة). |
| [setDecorative(boolean value)](#setDecorative-boolean-) | الحصول على أو تعيين خيار "وضع علامة كديكور" (قراءة/كتابة). |
| [getShapeLock()](#getShapeLock--) | إرجاع أقفال الشكل. |
| [isGrouped()](#isGrouped--) | تحديد ما إذا كان الشكل جزءًا من مجموعة. |
| [getParentGroup()](#getParentGroup--) | إرجاع كائن GroupShape الأب إذا كان الشكل جزءًا من مجموعة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | الحصول على الحدود البصرية للشكل المُحسب من محتواه المرسوم. |
| [getSlide()](#getSlide--) | إرجاع الشريحة الأب للشكل. |
| [getPresentation()](#getPresentation--) | إرجاع العرض التقديمي الأب للشرائح. |
### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

تحدد ما إذا كان الشكل هو TextHolder_PPT. قراءة فقط  boolean .

**القيمة المرجعة:**  
boolean
### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

إرجاع العنصر النائب لشكل. إرجاع null إذا لم يكن للشكل عنصر نائب. قراءة فقط [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // يقوم بإنشاء كائن من فئة Presentation
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // يصل إلى الشريحة الأولى
>      ISlide sld = pres.getSlides().get_Item(0);
>      // يتنقل عبر الأشكال للعثور على العنصر النائب
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // يغيّر النص في كل عنصر نائب
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // يحفظ العرض التقديمي على القرص
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
>      for (IShape shape : slide.getSlide().getShapes()) // يتنقل عبر الشريحة
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // يعرض PowerPoint "انقر لإضافة عنوان"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // يضيف العنوان الفرعي
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
```

**القيمة المرجعة:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder)
### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

تحدد أن هذا الشكل ليس عنصرًا نائبًا.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويعين خصائص العنصر النائب إلى العنصر المحدد.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | العنصر النائب لنسخ المحتوى منه. |

**القيمة المرجعة:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder) - جديد #getPlaceholder.getPlaceholder.
### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

إرجاع شكل عنصر نائب أساسي (الشكل من التخطيط و/أو الشريحة الرئيسية الذي يُورث منه الشكل الحالي).

--------------------

> ```
> // احصل على جميع المؤثرات المتحركة (الماستر/التخطيط/الشريحة) للشكل العنصر النائب
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

يُرجع null إذا لم يكن الشكل الحالي مُورثًا.

**القيمة المرجعة:**  
[IShape](../../com.aspose.slides/ishape)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

إرجاع البيانات المخصصة للشكل. قراءة فقط [ICustomData](../../com.aspose.slides/icustomdata).

**القيمة المرجعة:**  
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

إرجاع أو تعيين خصائص إطار الشكل الخام. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

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

**القيمة المرجعة:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

إرجاع أو تعيين خصائص إطار الشكل الخام. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

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

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

إرجاع أو تعيين خصائص إطار الشكل. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

قيمة كل خاصية في كائن IShapeFrame المُرجَع ليست غير مُعرفة (ليست NaN أو NotDefined). قيمة كل خاصية في كائن IShapeFrame المُعيّن يجب أن تكون معرفة (ليس NaN أو NotDefined). يمكنك تعيين قيم غير معرفة لخصائص كائن RawFrame.

**القيمة المرجعة:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

إرجاع أو تعيين خصائص إطار الشكل. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

قيمة كل خاصية في كائن IShapeFrame المُرجَع ليست غير مُعرفة (ليست NaN أو NotDefined). قيمة كل خاصية في كائن IShapeFrame المُعيّن يجب أن تكون معرفة (ليس NaN أو NotDefined). يمكنك تعيين قيم غير معرفة لخصائص كائن RawFrame.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

إرجاع كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص خط. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**القيمة المرجعة:**  
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

إرجاع كائن ThreeDFormat الذي يحتوي على خصائص التأثير ثلاثي الأبعاد لشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص ثلاثية الأبعاد. قراءة فقط [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**القيمة المرجعة:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

إرجاع كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على شكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [IEffectFormat](../../com.aspose.slides/ieffectformat).

**القيمة المرجعة:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

إرجاع كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل. ملاحظة: قد يُرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص تعبئة. قراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Accent 4, Lighter 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, Lighter 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, Lighter 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, Darker 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, Darker 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**القيمة المرجعة:**  
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public final IImage getImage()
```

إرجاع صورة مصغرة للشكل. يُستخدم النوع ShapeThumbnailBounds.Shape كقيمة افتراضية لحدود الصورة المصغرة.

**القيمة المرجعة:**  
[IImage](../../com.aspose.slides/iimage) - صورة مصغرة للشكل.
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

إرجاع صورة مصغرة للشكل.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| bounds | int | نوع حدود الصورة المصغرة للشكل. |
| scaleX | float | مقياس X |
| scaleY | float | مقياس Y |

**القيمة المرجعة:**  
[IImage](../../com.aspose.slides/iimage) - صورة مصغرة للشكل أو null في حال استخدام النوع ShapeThumbnailBounds.Appearance وكان الشكل لا يحتوي على عناصر مرئية.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

حفظ محتوى الشكل كملف SVG.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | الدفق الهدف |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

حفظ محتوى الشكل كملف SVG.

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | الدفق الهدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | خيارات توليد SVG |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

إرجاع أو تعيين الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**القيمة المرجعة:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

إرجاع أو تعيين الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

إرجاع أو تعيين الارتباط التشعبي المحدد للتحريك فوق الفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**القيمة المرجعة:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

إرجاع أو تعيين الارتباط التشعبي المحدد للتحريك فوق الفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

إرجاع مدير الارتباطات التشعبية. قراءة فقط [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**القيمة المرجعة:**  
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

تحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة  boolean .

**القيمة المرجعة:**  
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

تحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة  boolean .

**المعاملات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

إرجاع موضع الشكل في ترتيب الـ z. Shapes[0] تُرجع الشكل في خلفية الترتيب، وShapes[Shapes.Count - 1] تُرجع الشكل في مقدمة الترتيب. قراءة فقط  int .

**القيمة المرجعة:**  
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

إرجاع عدد نقاط الربط على الشكل. قراءة فقط  int .

**القيمة المرجعة:**  
int
### getRotation() {#getRotation--}
```
public final float getRotation()
```

إرجاع أو تعيين عدد الدرجات التي يدور فيها الشكل حول محور الـ z. القيمة الموجبة تشير إلى دوران باتجاه عقرب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقرب الساعة. قراءة/كتابة float.

--------------------

القيمة المُرجَعة دائمًا معرفة (ليست Float.NaN). القيمة المُعيَّنة يجب أن تكون معرفة (ليست Float.NaN). يمكنك تعيين قيم غير معرفة لخصائص كائن RawFrame.

**القيمة المرجعة:**  
float
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
إرجاع أو تعيين عدد الدرجات التي يتم تدوير الشكل المحدد حول المحور z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ والقيمة السلبية تشير إلى دوران عكس اتجاه عقارب الساعة. قراءة/كتابة float.

--------------------

القيمة المرجعة تكون دائمًا معرفة (ليست Float.NaN). يجب أن تكون القيمة المعينة معرفة (ليس Float.NaN). يمكنك تعيين قيم غير معرفة لخصائص كائن RawFrame.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```


إرجاع أو تعيين إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة float.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون أبدًا Float.NaN. يجب أن تكون القيمة المعينة أيضًا معرفة؛ عيّن Float.NaN فقط لخصائص كائن RawFrame.

**القيمة المرجعة:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```


إرجاع أو تعيين إحداثي x للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة float.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون أبدًا Float.NaN. يجب أن تكون القيمة المعينة أيضًا معرفة؛ عيّن Float.NaN فقط لخصائص كائن RawFrame.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```


إرجاع أو تعيين إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة float.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون أبدًا Float.NaN. يجب أن تكون القيمة المعينة أيضًا معرفة؛ عيّن Float.NaN فقط لخصائص كائن RawFrame.

**القيمة المرجعة:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```


إرجاع أو تعيين إحداثي y للزاوية العلوية اليسرى للشكل، مقاسًا بالنقاط. قراءة/كتابة float.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون أبدًا Float.NaN. يجب أن تكون القيمة المعينة أيضًا معرفة؛ عيّن Float.NaN فقط لخصائص كائن RawFrame.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```


إرجاع أو تعيين عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة float.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون أبدًا Float.NaN. يجب أن تكون القيمة المعينة أيضًا معرفة؛ عيّن Float.NaN فقط لخصائص كائن RawFrame.

**القيمة المرجعة:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```


إرجاع أو تعيين عرض الشكل، مقاسًا بالنقاط. قراءة/كتابة float.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون أبدًا Float.NaN. يجب أن تكون القيمة المعينة أيضًا معرفة؛ عيّن Float.NaN فقط لخصائص كائن RawFrame.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```


إرجاع أو تعيين ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة float.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون أبدًا Float.NaN. يجب أن تكون القيمة المعينة أيضًا معرفة؛ عيّن Float.NaN فقط لخصائص كائن RawFrame.

**القيمة المرجعة:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```


إرجاع أو تعيين ارتفاع الشكل، مقاسًا بالنقاط. قراءة/كتابة float.

--------------------

القيمة المرجعة دائمًا معرفة ولا تكون أبدًا Float.NaN. يجب أن تكون القيمة المعينة أيضًا معرفة؛ عيّن Float.NaN فقط لخصائص كائن RawFrame.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```


الخاصية تحدد كيفية عرض الشكل في وضع اللونين الأبيض والأسود. قراءة/كتابة [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**القيمة المرجعة:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```


الخاصية تحدد كيفية عرض الشكل في وضع اللونين الأبيض والأسود. قراءة/كتابة [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```


إرجاع معرف داخلي خاص بالعرض مخصص للاستخدام من قبل الملحقات أو التعليمات البرمجية الأخرى. نظرًا لأن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، لا يجب اعتبارها مفتاحًا فريدًا دائمًا. قراءة فقط long. راجع أيضًا \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**القيمة المرجعة:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```


إرجاع معرف فريد خاص بالشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لـ PowerPoint أو كود التفاعل بالرجوع إلى الشكل من أي مكان في المستند. قراءة فقط long. راجع أيضًا \#getUniqueId.getUniqueId.

**القيمة المرجعة:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```


إرجاع أو تعيين النص البديل المرتبط بالشكل. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```


إرجاع أو تعيين النص البديل المرتبط بالشكل. قراءة/كتابة String.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```


إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```


إرجاع أو تعيين عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```


إرجاع أو تعيين اسم الشكل. يجب ألا يكون فارغًا. استخدم سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String.

**القيمة المرجعة:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


إرجاع أو تعيين اسم الشكل. يجب ألا يكون فارغًا. استخدم سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String.

**المعاملات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```


إرجاع أو تعيين خيار 'وضع علامة كزخرفة' قراءة/كتابة boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**القيمة المرجعة:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```


إرجاع أو تعيين خيار 'وضع علامة كزخرفة' قراءة/كتابة boolean.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```


إرجاع أقفال الشكل. قراءة فقط [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**القيمة المرجعة:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```


تحديد ما إذا كان الشكل مجموعة. قراءة فقط boolean.

--------------------

الخاصية \#getParentGroup.getParentGroup تُرجع كائن GroupShape الأب إذا كان الشكل مجموعة.

**القيمة المرجعة:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```


إرجاع كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يُرجع null. قراءة فقط [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

الخاصية \#isGrouped.isGrouped تحدد ما إذا كان الشكل مجموعة.

**القيمة المرجعة:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


إرجاع كائن Parent_Immediate. قراءة فقط IDOMObject.

**القيمة المرجعة:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```


إرجاع الحدود البصرية للشكل محسوبة من محتواه المُعرض.

**القيمة المرجعة:**
java.awt.geom.Rectangle2D.Float - java.awt.geom.Rectangle2D.Float يمثل الحدود البصرية للشكل بإحداثيات الشريحة.

--------------------

المستطيل المرجع يمثل الحدود المتعامدة لجميع المحتويات التي ينتجها الشكل أثناء العرض في فضاء إحداثيات الشريحة. قد تختلف هذه الحدود عن حدود نموذج الشكل \#getX.getX/\#setX(float).setX(float)، \#getY.getY/\#setY(float).setY(float)، \#getWidth.getWidth/\#setWidth(float).setWidth(float)، \#getHeight.getHeight/\#setHeight(float).setHeight(float) وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المعروض خارج أصل الشريحة. تأخذ الحدود البصرية في الاعتبار جوانب متعلقة بالعرض مثل التحويلات (مثلاً، الدوران)، عرض الحد والوصلات، تخطيط النص وتدفقه، هندسة SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المعروض للشكل. الحدود المرجعة ليست مقصوصة إلى مستطيل الشريحة.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


إرجاع الشريحة الأم للشكل. قراءة فقط [IBaseSlide](../../com.aspose.slides/ibaseslide).

**القيمة المرجعة:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


إرجاع العرض التقديمي الأم للشريحة. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المرجعة:**
[IPresentation](../../com.aspose.slides/ipresentation)