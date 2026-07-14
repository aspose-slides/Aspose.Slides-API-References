---
title: Shape
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
description: يمثل شكلاً على شريحة.
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

يُمثل شكلًا على شريحة.

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | يحدد ما إذا كان الشكل TextHolder\_PPT. |
| [getPlaceholder()](#getPlaceholder--) | يعيد العنصر النائب للشكل. |
| [removePlaceholder()](#removePlaceholder--) | يحدد أن هذا الشكل ليس عنصرًا نائبًا. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد. |
| [getBasePlaceholder()](#getBasePlaceholder--) | يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو شريحة النموذج التي يرث منها الشكل الحالي). |
| [getCustomData()](#getCustomData--) | يعيد البيانات المخصصة للشكل. |
| [getRawFrame()](#getRawFrame--) | يعيد أو يضبط خصائص إطار الشكل الخام. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | يعيد أو يضبط خصائص إطار الشكل الخام. |
| [getFrame()](#getFrame--) | يعيد أو يضبط خصائص إطار الشكل. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | يعيد أو يضبط خصائص إطار الشكل. |
| [getLineFormat()](#getLineFormat--) | يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. |
| [getThreeDFormat()](#getThreeDFormat--) | يعيد كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد لشكل. |
| [getEffectFormat()](#getEffectFormat--) | يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. |
| [getFillFormat()](#getFillFormat--) | يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل. |
| [getImage()](#getImage--) | يعيد صورة مصغرة للشكل. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | يعيد صورة مصغرة للشكل. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | يحفظ محتوى الشكل كملف SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | يحفظ محتوى الشكل كملف SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | يعيد أو يضبط الارتباط التشعبي المحدد للتمرير بالفأرة. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | يعيد أو يضبط الارتباط التشعبي المحدد للتمرير بالفأرة. |
| [getHyperlinkManager()](#getHyperlinkManager--) | يعيد مدير الارتباط التشعبي. |
| [getHidden()](#getHidden--) | يحدد ما إذا كان الشكل مخفيًا. |
| [setHidden(boolean value)](#setHidden-boolean-) | يحدد ما إذا كان الشكل مخفيًا. |
| [getZOrderPosition()](#getZOrderPosition--) | يعيد موضع الشكل في ترتيب Z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | يعيد عدد مواقع الاتصال على الشكل. |
| [getRotation()](#getRotation--) | يعيد أو يضبط عدد الدرجات التي يدور بها الشكل المحدد حول المحور Z. |
| [setRotation(float value)](#setRotation-float-) | يعيد أو يضبط عدد الدرجات التي يدور بها الشكل المحدد حول المحور Z. |
| [getX()](#getX--) | يحصل على إحداثي x لزاوية الشكل العليا اليسرى، مقاسة بالنقاط، أو يضبطه. |
| [setX(float value)](#setX-float-) | يحصل على إحداثي x لزاوية الشكل العليا اليسرى، مقاسة بالنقاط، أو يضبطه. |
| [getY()](#getY--) | يحصل على إحداثي y لزاوية الشكل العليا اليسرى، مقاسة بالنقاط، أو يضبطه. |
| [setY(float value)](#setY-float-) | يحصل على إحداثي y لزاوية الشكل العليا اليسرى، مقاسة بالنقاط، أو يضبطه. |
| [getWidth()](#getWidth--) | يحصل على عرض الشكل، مقاسًا بالنقاط، أو يضبطه. |
| [setWidth(float value)](#setWidth-float-) | يحصل على عرض الشكل، مقاسًا بالنقاط، أو يضبطه. |
| [getHeight()](#getHeight--) | يحصل على ارتفاع الشكل، مقاسًا بالنقاط، أو يضبطه. |
| [setHeight(float value)](#setHeight-float-) | يحصل على ارتفاع الشكل، مقاسًا بالنقاط، أو يضبطه. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | الخاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | الخاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود. |
| [getUniqueId()](#getUniqueId--) | يعيد معرفًا داخليًا يخص العرض مخصصًا للاستخدام من قبل الإضافات أو كود آخر. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | يعيد معرفًا فريدًا يخص الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل بشكل موثوق من أي مكان في المستند. |
| [getAlternativeText()](#getAlternativeText--) | يعيد أو يضبط النص البديل المرتبط بشكل. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | يعيد أو يضبط النص البديل المرتبط بشكل. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | يعيد أو يضبط عنوان النص البديل المرتبط بالشكل. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | يعيد أو يضبط عنوان النص البديل المرتبط بالشكل. |
| [getName()](#getName--) | يعيد أو يضبط اسم الشكل. |
| [setName(String value)](#setName-java.lang.String-) | يعيد أو يضبط اسم الشكل. |
| [isDecorative()](#isDecorative--) | يحصل على أو يضبط خيار 'وضع علامة كزينة' (قراءة/كتابة) بوليان. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | يحصل على أو يضبط خيار 'وضع علامة كزينة' (قراءة/كتابة) بوليان. |
| [getShapeLock()](#getShapeLock--) | يعيد أقفال الشكل. |
| [isGrouped()](#isGrouped--) | يحدد ما إذا كان الشكل مجموعة. |
| [getParentGroup()](#getParentGroup--) | يعيد كائن GroupShape الأب إذا كان الشكل مجموعة. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | يحصل على الحدود البصرية للشكل المحسوبة من محتواه المُرَسَم. |
| [getSlide()](#getSlide--) | يعيد شريحة الوالد للشكل. |
| [getPresentation()](#getPresentation--) | يعيد العرض الأب للشفرة. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

يحدد ما إذا كان الشكل TextHolder\_PPT. قراءة فقط  boolean .

**القيمة المرجعة:**  
boolean

### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

يعيد العنصر النائب للشكل. يعيد null إذا لم يكن للشكل عنصر نائب. قراءة فقط [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // ينشئ فئة Presentation
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
>      // يحفظ العرض على القرص
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
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // يعرض PowerPoint "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // يضيف عنوانًا فرعيًا
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


**القيمة المرجعة:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

يحدد أن هذا الشكل ليس عنصرًا نائبًا.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

يضيف عنصرًا نائبًا جديدًا إذا لم يكن موجودًا ويضبط خصائص العنصر النائب إلى العنصر المحدد.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | العنصر النائب لنسخ المحتوى منه. |

**القيمة المرجعة:**  
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New #getPlaceholder.getPlaceholder.

### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

يعيد شكل عنصر نائب أساسي (شكل من التخطيط و/أو شريحة النموذج التي يرث منها الشكل الحالي).

--------------------

> ```
> // احصل على جميع التأثيرات المتحركة (master/layout/slide) للعنصر النائب
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

يُعاد null إذا لم يكن الشكل الحالي مرثيًا.

**القيمة المرجعة:**  
[IShape](../../com.aspose.slides/ishape)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

يعيد البيانات المخصصة للشكل. قراءة فقط [ICustomData](../../com.aspose.slides/icustomdata).

**القيمة المرجعة:**  
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

يعيد أو يضبط خصائص إطار الشكل الخام. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

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

يعيد أو يضبط خصائص إطار الشكل الخام. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  // أو
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  // يمكن أن يؤدي مثل هذا الكود إلى حالات غير واضحة. لذا تم إضافة قيود لاستخدام القيم غير المعرفة في IShape.getFrame(). يجب أن تكون قيم x و y والعرض والارتفاع و flipH و flipV وزاوية الدوران معرفة (ليس Float.NaN أو NullableBool.NotDefined). الكود المثال أعلاه الآن يرمي استثناء ArgumentException.
>  // ينطبق هذا على حالات الاستخدام التالية:
>  IShape shape = ...;
>  shape.setFrame(...); // لا يمكن أن تكون غير معرفة
>  IShapeCollection shapes = ...;
>  // لا يمكن أن تكون معلمات x و y والعرض والارتفاع قيم Float.NaN:
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
>  // لكن خصائص إطار IShape.RawFrame يمكن أن تكون غير معرفة. هذا منطقي عندما يكون الشكل مرتبطًا بعنصر نائب. ثم يتم استبدال قيم إطار الشكل غير المعرفة من قبل عنصر النائب الأب. إذا لم يكن هناك عنصر نائب أب لهذا الشكل فإن الشكل يستخدم القيم الافتراضية عند تقييم الإطار الفعلي بناءً على IShape.RawFrame. القيم الافتراضية هي 0 و NullableBool.False لـ x و y والعرض والارتفاع و flipH و flipV وزاوية الدوران. على سبيل المثال:
>  IShape shape = ...; // الشكل مرتبط بعنصر نائب
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // الآن يرث الشكل قيم x و y والارتفاع و flipH و flipV من العنصر النائب ويستبدل العرض=100 وزاوية الدوران=0.{code}
> ```


**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

يعيد أو يضبط خصائص إطار الشكل. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

قيمة كل خاصية في كائن IShapeFrame المرجع غير معرفة (ليست NaN أو NotDefined). يجب أن تكون قيمة كل خاصية في كائن IShapeFrame المعطى غير معرفة (ليست NaN أو NotDefined). يمكنك تعيين قيم غير معرفة لخصائص كائن RawFrame.

**القيمة المرجعة:**  
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

يعيد أو يضبط خصائص إطار الشكل. قراءة/كتابة [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

قيمة كل خاصية في كائن IShapeFrame المرجع غير معرفة (ليست NaN أو NotDefined). يجب أن تكون قيمة كل خاصية في كائن IShapeFrame المعطى غير معرفة (ليست NaN أو NotDefined). يمكنك تعيين قيم غير معرفة لخصائص كائن RawFrame.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

يعيد كائن LineFormat الذي يحتوي على خصائص تنسيق الخط لشكل. ملاحظة: قد يرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص خط. قراءة فقط [ILineFormat](../../com.aspose.slides/ilineformat).

**القيمة المرجعة:**  
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

يعيد كائن ThreeDFormat الذي يحتوي على خصائص تأثير ثلاثي الأبعاد لشكل. ملاحظة: قد يرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص ثلاثية الأبعاد. قراءة فقط [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**القيمة المرجعة:**  
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

يعيد كائن EffectFormat الذي يحتوي على تأثيرات البكسل المطبقة على الشكل. ملاحظة: قد يرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص تأثير. قراءة فقط [IEffectFormat](../../com.aspose.slides/ieffectformat).

**القيمة المرجعة:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

يعيد كائن FillFormat الذي يحتوي على خصائص تنسيق التعبئة لشكل. ملاحظة: قد يرجع null لبعض أنواع الأشكال التي لا تحتوي على خصائص تعبئة. قراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

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

يعيد صورة مصغرة للشكل. يستخدم النوع ShapeThumbnailBounds.Shape كقيمة افتراضية للحدود.

**القيمة المرجعة:**  
[IImage](../../com.aspose.slides/iimage) - صورة مصغرة للشكل.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

يعيد صورة مصغرة للشكل.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| bounds | int | نوع حدود صورة الشكل المصغرة. |
| scaleX | float | مقياس X |
| scaleY | float | مقياس Y |

**القيمة المرجعة:**  
[IImage](../../com.aspose.slides/iimage) - صورة مصغرة للشكل أو null في حالة استخدام ShapeThumbnailBounds.Appearance و عدم وجود عناصر مرئية للشكل.

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

يحفظ محتوى الشكل كملف SVG.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الهدف |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

يحفظ محتوى الشكل كملف SVG.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الهدف |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | خيارات توليد SVG |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**القيمة المرجعة:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

يعيد أو يضبط الارتباط التشعبي المحدد للنقر بالفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

يعيد أو يضبط الارتباط التشعبي المحدد للتمرير بالفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**القيمة المرجعة:**  
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

يعيد أو يضبط الارتباط التشعبي المحدد للتمرير بالفأرة. قراءة/كتابة [IHyperlink](../../com.aspose.slides/ihyperlink).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public HH ???  ???  ???
```

يعيد مدير الارتباط التشعبي. قراءة فقط [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**القيمة المرجعة:**  
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة  boolean .

**القيمة المرجعة:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

يحدد ما إذا كان الشكل مخفيًا. قراءة/كتابة  boolean .

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

يعيد موضع الشكل في ترتيب Z. تُعيد Shapes[0] الشكل الموجود في خلفية ترتيب Z، وتُعيد Shapes[Shapes.Count - 1] الشكل الموجود في مقدمة ترتيب Z. قراءة فقط  int .

**القيمة المرجعة:**  
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

يعيد عدد مواقع الاتصال على الشكل. قراءة فقط  int .

**القيمة المرجعة:**  
int

### getRotation() {#getRotation--}
```
public final float getRotation()
```

يعيد أو يضبط عدد الدرجات التي يدور بها الشكل المحدد حول المحور Z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. قراءة/كتابة float.

--------------------

القيمة المرجعة تكون دائمًا معرفة (ليست Float.NaN). يجب أن تكون القيمة المعطاة معرفة (ليست Float.NaN). يمكنك تعيين قيم غير معرفة لخصائص كائن RawFrame.

**القيمة المرجعة:**  
float

### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

يعيد أو يضبط عدد الدرجات التي يدور بها الشكل المحدد حول المحور Z. القيمة الموجبة تشير إلى دوران باتجاه عقارب الساعة؛ القيمة السالبة تشير إلى دوران عكس اتجاه عقارب الساعة. قراءة/كتابة float.

--------------------

القيمة المرجعة تكون دائمًا معرفة (ليست Float.NaN). يجب أن تكون القيمة المعطاة معرفة (ليست Float.NaN). يمكنك تعيين قيم غير معرفة لخصائص كائن RawFrame.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

يحصل على إحداثي x لزاوية الشكل العليا اليسرى، مقاسة بالنقاط، أو يضبطه. قراءة/كتابة float.

--------------------

القيمة المرجعة تكون دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعطاة معرفة أيضًا؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**القيمة المرجعة:**  
float

### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

يحصل على إحداثي x لزاوية الشكل العليا اليسرى، مقاسة بالنقاط، أو يضبطه. قراءة/كتابة float.

--------------------

القيمة المرجعة تكون دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعطاة معرفة أيضًا؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

يحصل على إحداثي y لزاوية الشكل العليا اليسرى، مقاسة بالنقاط، أو يضبطه. قراءة/كتابة float.

--------------------

القيمة المرجعة تكون دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعطاة معرفة أيضًا؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**القيمة المرجعة:**  
float

### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

يحصل على إحداثي y لزاوية الشكل العليا اليسرى، مقاسة بالنقاط، أو يضبطه. قراءة/كتابة float.

--------------------

القيمة المرجعة تكون دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعطاة معرفة أيضًا؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

يحصل على عرض الشكل، مقاسًا بالنقاط، أو يضبطه. قراءة/كتابة float.

--------------------

القيمة المرجعة تكون دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعطاة معرفة أيضًا؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**القيمة المرجعة:**  
float

### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

يحصل على عرض الشكل، مقاسًا بالنقاط، أو يضبطه. قراءة/كتابة float.

--------------------

القيمة المرجعة تكون دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعطاة معرفة أيضًا؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

يحصل على ارتفاع الشكل، مقاسًا بالنقاط، أو يضبطه. قراءة/كتابة float.

--------------------

القيمة المرجعة تكون دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعطاة معرفة أيضًا؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**القيمة المرجعة:**  
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

يحصل على ارتفاع الشكل، مقاسًا بالنقاط، أو يضبطه. قراءة/كتابة float.

--------------------

القيمة المرجعة تكون دائمًا معرفة ولا تكون Float.NaN. يجب أن تكون القيمة المعطاة معرفة أيضًا؛ يمكن تعيين Float.NaN فقط لخصائص كائن RawFrame.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

الخاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**القيمة المرجعة:**  
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public    



```

الخاصية تحدد كيفية عرض الشكل في وضع العرض بالأبيض والأسود. قراءة/كتابة [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

يعيد معرفًا داخليًا يخص العرض مخصصًا للاستخدام من قبل الإضافات أو كود آخر. بما أن هذه القيمة يمكن إعادة تعيينها من قبل المستخدم أو برمجيًا، فلا يجب التعامل معها كمعرف فريد دائم. قراءة فقط long. انظر أيضًا #getOfficeInteropShapeId.getOfficeInteropShapeId.

**القيمة المرجعة:**  
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

يعيد معرفًا فريدًا يخص الشريحة يبقى ثابتًا طوال عمر الشكل ويسمح لبرنامج PowerPoint أو كود التفاعل بالإشارة إلى الشكل بشكل موثوق من أي مكان في المستند. قراءة فقط long. انظر أيضًا #getUniqueId.getUniqueId.

**القيمة المرجعة:**  
long

### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

يعيد أو يضبط النص البديل المرتبط بشكل. قراءة/كتابة String.

**القيمة المرجعة:**  
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

يعيد أو يضبط النص البديل المرتبط بشكل. قراءة/كتابة String.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

يعيد أو يضبط عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String.

**القيمة المرجعة:**  
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

يعيد أو يضبط عنوان النص البديل المرتبط بالشكل. قراءة/كتابة String.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

يعيد أو يضبط اسم الشكل. يجب ألا يكون null. استخدم سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String.

**القيمة المرجعة:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

يعيد أو يضبط اسم الشكل. يجب ألا يكون null. استخدم سلسلة فارغة إذا لزم الأمر. قراءة/كتابة String.

**المعلمات:**  
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

يحصل على أو يضبط خيار 'وضع علامة كزينة' (قراءة/كتابة) بوليان.

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

يحصل على أو يضبط خيار 'وضع علامة كزينة' (قراءة/كتابة) بوليان.

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
public IBaseShapeLock getShapeLock()
```

يعيد أقفال الشكل. قراءة فقط [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**القيمة المرجعة:**  
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

يحدد ما إذا كان الشكل مجموعة. قراءة فقط boolean.

--------------------

خاصية #getParentGroup.getParentGroup تُعيد كائن GroupShape الأب إذا كان الشكل مجموعة.

**القيمة المرجعة:**  
boolean

### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

يعيد كائن GroupShape الأب إذا كان الشكل مجموعة. وإلا يُعيد null. قراءة فقط [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

خاصية #isGrouped.isGrouped تحدد ما إذا كان الشكل مجموعة.

**القيمة المرجعة:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

يعيد الكائن Parent_Immediate. قراءة فقط IDOMObject.

**القيمة المرجعة:**  
com.aspose.slides.IDOMObject

### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

يحصل على الحدود البصرية للشكل المحسوبة من محتواه المُرَسَم.

**القيمة المرجعة:**  
android.graphics.RectF - A android.graphics.RectF that represents the visual bounds of the shape in slide coordinates.

--------------------

المستطيل المرجع يمثل الحدود المحاذية للمحور لجميع المحتويات التي ينتجها الشكل خلال العرض في مساحة إحداثيات الشريحة. قد تختلف هذه الحدود عن حدود النموذج لل shape \#getX.getX/\#setX(float).setX(float)، \#getY.getY/\#setY(float).setY(float)، \#getWidth.getWidth/\#setWidth(float).setWidth(float)، \#getHeight.getHeight/\#setHeight(float).setHeight(float) وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المُرَسَم إلى ما وراء أصل الشريحة. تأخذ الحدود البصرية في الاعتبار جوانب العرض المتعلقة بالتحويلات (مثل الدوران)، وعرض الخطوط والموصلات، وتخطيط النص والفيض، وجيومتريات SmartArt، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المُرَسَم للشكل. الحدود المرجعة ليست مقصوصة إلى مستطيل الشريحة.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

يعيد شريحة الوالد للشكل. قراءة فقط [IBaseSlide](../../com.aspose.slides/ibaseslide).

**القيمة المرجعة:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

يعيد العرض الأب للشفرة. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**القيمة المرجعة:**  
[IPresentation](../../com.aspose.slides/ipresentation)