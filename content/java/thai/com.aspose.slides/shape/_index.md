---
title: Shape
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงรูปทรงบนสไลด์หนึ่ง.
type: docs
url: /th/com.aspose.slides/shape/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ถูกใช้งานทั้งหมด:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

เป็นการแสดงรูปทรงบนสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่. |
| [getPlaceholder()](#getPlaceholder--) | ส่งกลับ placeholder สำหรับรูปทรง. |
| [removePlaceholder()](#removePlaceholder--) | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้เป็นค่าเฉพาะที่ระบุ. |
| [getBasePlaceholder()](#getBasePlaceholder--) | ส่งกลับรูปทรง placeholder ขั้นพื้นฐาน (รูปทรงจากเลเอาต์และ/หรือสไลด์แม่ที่รูปทรงปัจจุบันสืบทอดมาจาก). |
| [getCustomData()](#getCustomData--) | ส่งกลับข้อมูลที่กำหนดเองของรูปทรง. |
| [getRawFrame()](#getRawFrame--) | ส่งกลับหรือกำหนดคุณสมบัติ raw shape frame. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | ส่งกลับหรือกำหนดคุณสมบัติ raw shape frame. |
| [getFrame()](#getFrame--) | ส่งกลับหรือกำหนดคุณสมบัติ shape frame. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | ส่งกลับหรือกำหนดคุณสมบัติ shape frame. |
| [getLineFormat()](#getLineFormat--) | ส่งกลับออบเจกต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง. |
| [getThreeDFormat()](#getThreeDFormat--) | ส่งกลับออบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปทรง. |
| [getEffectFormat()](#getEffectFormat--) | ส่งกลับออบเจกต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง. |
| [getFillFormat()](#getFillFormat--) | ส่งกลับออบเจกต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปทรง. |
| [getImage()](#getImage--) | ส่งกลับ thumbnail ของรูปทรง. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | ส่งกลับ thumbnail ของรูปทรง. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | ส่งกลับหรือกำหนด hyperlink ที่กำหนดสำหรับคลิกเมาส์. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | ส่งกลับหรือกำหนด hyperlink ที่กำหนดสำหรับคลิกเมาส์. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | ส่งกลับหรือกำหนด hyperlink ที่กำหนดสำหรับการวางเมาส์. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | ส่งกลับหรือกำหนด hyperlink ที่กำหนดสำหรับการวางเมาส์. |
| [getHyperlinkManager()](#getHyperlinkManager--) | ส่งกลับผู้จัดการ hyperlink. |
| [getHidden()](#getHidden--) | กำหนดว่ารูปทรงถูกซ่อนหรือไม่. |
| [setHidden(boolean value)](#setHidden-boolean-) | กำหนดว่ารูปทรงถูกซ่อนหรือไม่. |
| [getZOrderPosition()](#getZOrderPosition--) | ส่งกลับตำแหน่งของรูปทรงใน z-order. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | ส่งกลับจำนวนจุดเชื่อมต่อบนรูปทรง. |
| [getRotation()](#getRotation--) | ส่งกลับหรือกำหนดจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z. |
| [setRotation(float value)](#setRotation-float-) | ส่งกลับหรือกำหนดจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z. |
| [getX()](#getX--) | รับหรือกำหนดค่าพิกัด x ของมุมซ้ายบนของรูปทรง, วัดเป็นจุด. |
| [setX(float value)](#setX-float-) | รับหรือกำหนดค่าพิกัด x ของมุมซ้ายบนของรูปทรง, วัดเป็นจุด. |
| [getY()](#getY--) | รับหรือกำหนดค่าพิกัด y ของมุมซ้ายบนของรูปทรง, วัดเป็นจุด. |
| [setY(float value)](#setY-float-) | รับหรือกำหนดค่าพิกัด y ของมุมซ้ายบนของรูปทรง, วัดเป็นจุด. |
| [getWidth()](#getWidth--) | รับหรือกำหนดความกว้างของรูปทรง, วัดเป็นจุด. |
| [setWidth(float value)](#setWidth-float-) | รับหรือกำหนดความกว้างของรูปทรง, วัดเป็นจุด. |
| [getHeight()](#getHeight--) | รับหรือกำหนดความสูงของรูปทรง, วัดเป็นจุด. |
| [setHeight(float value)](#setHeight-float-) | รับหรือกำหนดความสูงของรูปทรง, วัดเป็นจุด. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | คุณสมบัติระบุว่ารูปทรงจะถูกแสดงผลในโหมดสีขาว-ดำอย่างไร. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | คุณสมบัติระบุว่ารูปทรงจะถูกแสดงผลในโหมดสีขาว-ดำอย่างไร. |
| [getUniqueId()](#getUniqueId--) | ส่งกลับตัวระบุภายในที่มีขอบเขตของการนำเสนอ สำหรับใช้โดยส่วนเสริมหรือโค้ดอื่น. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | ส่งกลับตัวระบุที่มีขอบเขตเฉพาะสไลด์และไม่ซ้ำ ซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างเชื่อถือจากทุกตำแหน่งในเอกสาร. |
| [getAlternativeText()](#getAlternativeText--) | ส่งกลับหรือกำหนดข้อความแทนที่เกี่ยวข้องกับรูปทรง. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | ส่งกลับหรือกำหนดข้อความแทนที่เกี่ยวข้องกับรูปทรง. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | ส่งกลับหรือกำหนดหัวข้อของข้อความแทนที่เกี่ยวข้องกับรูปทรง. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | ส่งกลับหรือกำหนดหัวข้อของข้อความแทนที่เกี่ยวข้องกับรูปทรง. |
| [getName()](#getName--) | ส่งกลับหรือกำหนดชื่อของรูปทรง. |
| [setName(String value)](#setName-java.lang.String-) | ส่งกลับหรือกำหนดชื่อของรูปทรง. |
| [isDecorative()](#isDecorative--) | รับหรือกำหนดตัวเลือก 'Mark as decorative' เป็นบูลีนแบบอ่าน/เขียน. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | รับหรือกำหนดตัวเลือก 'Mark as decorative' เป็นบูลีนแบบอ่าน/เขียน. |
| [getShapeLock()](#getShapeLock--) | ส่งกลับการล็อคของรูปทรง. |
| [isGrouped()](#isGrouped--) | กำหนดว่ารูปทรงอยู่ในกลุ่มหรือไม่. |
| [getParentGroup()](#getParentGroup--) | ส่งกลับออบเจกต์ GroupShape พาเรนต์ หากรูปทรงถูกจัดกลุ่ม. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [getSlide()](#getSlide--) | ส่งกลับสไลด์พาเรนต์ของรูปทรง. |
| [getPresentation()](#getPresentation--) | ส่งกลับการนำเสนอพาเรนต์ของสไลด์. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว boolean .

**ส่งกลับ:**
boolean
### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

ส่งกลับ placeholder สำหรับรูปทรง. ส่งกลับ null หากรูปทรงไม่มี placeholder. อ่านอย่างเดียว [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // Instantiates a Presentation class
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // Accesses the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Iterates through shapes to find the placeholder
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // Changes the text in each placeholder
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // Saves the presentation to disk
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
>      for (IShape shape : slide.getSlide().getShapes()) // Iterates through the slide
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint displays "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // Adds subtitle
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

**ส่งกลับ:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)
### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้เป็นค่าเฉพาะที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder ที่คัดลอกเนื้อหาจาก. |

**ส่งกลับ:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - ใหม่ \#getPlaceholder.getPlaceholder.
### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

ส่งกลับรูปทรง placeholder ขั้นพื้นฐาน (รูปทรงจากเลเอาต์และ/หรือสไลด์แม่ที่รูปทรงปัจจุบันสืบทอดมาจาก).

--------------------

> ```
> // รับเอฟเฟกต์แบบเคลื่อนไหวทั้งหมด (master/layout/slide) ของรูปทรง placeholder
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


A null is returned if the current shape is not inherited.

**ส่งกลับ:**
[IShape](../../com.aspose.slides/ishape)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

ส่งกลับข้อมูลที่กำหนดเองของรูปทรง. อ่านอย่างเดียว [ICustomData](../../com.aspose.slides/icustomdata).

**ส่งกลับ:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

ส่งกลับหรือกำหนดคุณสมบัติ raw shape frame. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //หรือ
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //โค้ดลักษณะนี้อาจทำให้เกิดสถานการณ์ที่ไม่ชัดเจน ดังนั้นจึงมีการเพิ่มข้อจำกัดสำหรับการใช้ค่าที่ไม่ได้กำหนดสำหรับ IShape.getFrame() ค่าของ x, y, width, height, flipH, flipV และ rotationAngle ต้องถูกกำหนด (ไม่ใช่ Float.NaN หรือ NullableBool.NotDefined) ตัวอย่างโค้ดด้านบนตอนนี้จะทำให้เกิดข้อยกเว้น ArgumentException exception.
>  //ใช้กับกรณีการใช้งานเหล่านี้:
>  IShape shape = ...;
>  shape.setFrame(...); // ไม่สามารถเป็นค่าไม่ได้กำหนด
>  IShapeCollection shapes = ...;
>  // พารามิเตอร์ x, y, width, height ไม่สามารถเป็น Float.NaN:
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
>  //แต่คุณสมบัติของเฟรม IShape.RawFrame สามารถเป็นค่าไม่ได้กำหนดได้ สิ่งนี้มีความหมายเมื่อรูปทรงเชื่อมโยงกับ placeholder จากนั้นค่าที่ไม่ได้กำหนดของเฟรมรูปทรงจะถูกทับโดยค่าใน placeholder พาเรนท์ หากไม่มี placeholder พาเรนท์สำหรับรูปทรงนั้น รูปทรงจะใช้ค่าดีฟอลต์เมื่อประเมินเฟรมที่มีประสิทธิภาพตาม IShape.RawFrame ของมัน ค่าเริ่มต้นคือ 0 และ NullableBool.False สำหรับ x, y, width, height, flipH, flipV และ rotationAngle ตัวอย่าง:
>  IShape shape = ...; // รูปทรงเชื่อมโยงกับ placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ตอนนี้รูปทรงสืบทอดค่า x, y, height, flipH, flipV จาก placeholder และแทนที่ width=100 และ rotationAngle=0.{code}
> ```


**ส่งกลับ:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

ส่งกลับหรือกำหนดคุณสมบัติ raw shape frame. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

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

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

ส่งกลับหรือกำหนดคุณสมบัติ shape frame. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

ค่าของแต่ละคุณสมบัติของอินสแตนซ์ IShapeFrame ที่ส่งกลับจะไม่เป็นค่าที่ไม่ได้กำหนด (ไม่เป็น NaN หรือ NotDefined). ค่าของแต่ละคุณสมบัติของอินสแตนซ์ IShapeFrame ที่กำหนดต้องไม่เป็นค่าที่ไม่ได้กำหนด (ต้องไม่เป็น NaN หรือ NotDefined). คุณสามารถตั้งค่าที่ไม่ได้กำหนดให้กับคุณสมบัติของอินสแตนซ์ RawFrame ได้.

**ส่งกลับ:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

ส่งกลับหรือกำหนดคุณสมบัติ shape frame. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

ค่าของแต่ละคุณสมบัติของอินสแตนซ์ IShapeFrame ที่ส่งกลับจะไม่เป็นค่าที่ไม่ได้กำหนด (ไม่เป็น NaN หรือ NotDefined). ค่าของแต่ละคุณสมบัติของอินสแตนซ์ IShapeFrame ที่กำหนดต้องไม่เป็นค่าที่ไม่ได้กำหนด (ต้องไม่เป็น NaN หรือ NotDefined). คุณสามารถตั้งค่าที่ไม่ได้กำหนดให้กับคุณสมบัติของอินสแตนซ์ RawFrame ได้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

ส่งกลับออบเจกต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง. หมายเหตุ: สามารถส่งกลับ null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**ส่งกลับ:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

ส่งกลับออบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปทรง. หมายเหตุ: สามารถส่งกลับ null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**ส่งกลับ:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

ส่งกลับออบเจกต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง. หมายเหตุ: สามารถส่งกลับ null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [IEffectFormat](../../com.aspose.slides/ieffectformat).

**ส่งกลับ:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

ส่งกลับออบเจกต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปทรง. หมายเหตุ: สามารถส่งกลับ null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

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

**ส่งกลับ:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public final IImage getImage()
```

ส่งกลับ thumbnail ของรูปทรง. ชนิด ShapeThumbnailBounds.Shape จะใช้เป็นค่าเริ่มต้นสำหรับขอบเขต thumbnail ของรูปทรง.

**ส่งกลับ:**
[IImage](../../com.aspose.slides/iimage) - thumbnail ของรูปทรง.
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

ส่งกลับ thumbnail ของรูปทรง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bounds | int | ชนิดขอบเขต thumbnail ของรูปทรง. |
| scaleX | float | สเกล X |
| scaleY | float | สเกล Y |

**ส่งกลับ:**
[IImage](../../com.aspose.slides/iimage) - thumbnail ของรูปทรง หรือ null ในกรณีที่ใช้ ShapeThumbnailBounds.Appearance และรูปทรงไม่มีองค์ประกอบที่มองเห็นได้.
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |
### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | ตัวเลือกการสร้าง SVG |
### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

ส่งกลับหรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**ส่งกลับ:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

ส่งกลับหรือกำหนด hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |
### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

ส่งกลับหรือกำหนด hyperlink ที่กำหนดสำหรับการวางเมาส์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**ส่งกลับ:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

ส่งกลับหรือกำหนด hyperlink ที่กำหนดสำหรับการวางเมาส์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |
### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

ส่งกลับผู้จัดการ hyperlink. อ่านอย่างเดียว [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**ส่งกลับ:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

กำหนดว่รูปทรงถูกซ่อนหรือไม่. อ่าน/เขียน boolean .

**ส่งกลับ:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

กำหนดว่ารูปทรงถูกซ่อนหรือไม่. อ่าน/เขียน boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

ส่งกลับตำแหน่งของรูปทรงใน z-order. Shapes[0] ส่งกลับรูปทรงที่อยู่ด้านหลังของ z-order, และ Shapes[Shapes.Count - 1] ส่งกลับรูปทรงที่อยู่ด้านหน้าของ z-order. อ่านอย่างเดียว int .

**ส่งกลับ:**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

ส่งกลับจำนวนจุดเชื่อมต่อบนรูปทรง. อ่านอย่างเดียว int .

**ส่งกลับ:**
int
### getRotation() {#getRotation--}
```
public final float getRotation()
```

ส่งกลับหรือกำหนดจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z. ค่าเป็นบวกบ่งบอกการหมุนตามเข็มนาฬิกา; ค่าเป็นลบบ่งบอกการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน float.

--------------------

ค่าที่ส่งกลับจะต้องกำหนดเสมอ (ไม่เป็น Float.NaN). ค่าที่กำหนดต้องเป็นค่าที่กำหนด (ไม่เป็น Float.NaN). คุณสามารถกำหนดค่าที่ไม่ได้กำหนดให้กับคุณสมบัติของอินสแตนซ์ RawFrame ได้.

**ส่งกลับ:**
float
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```
คืนค่า หรือกำหนดจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z. ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน float.

--------------------

ค่าที่ส่งคืนจะต้องถูกกำหนดเสมอ (ไม่ใช่ Float.NaN). ค่าที่กำหนดต้องถูกกำหนด (ไม่ใช่ Float.NaN). คุณสามารถตั้งค่าที่ไม่ได้กำหนดสำหรับคุณสมบัติของอินสแตนซ์ RawFrame.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งคืนจะต้องถูกกำหนดเสมอและไม่มี Float.NaN. ค่าที่กำหนดจะต้องถูกกำหนดด้วย; กำหนด Float.NaN เฉพาะคุณสมบัติของอินสแตนซ์ RawFrame.

**ผลลัพธ์:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งคืนจะต้องถูกกำหนดเสมอและไม่มี Float.NaN. ค่าที่กำหนดจะต้องถูกกำหนดด้วย; กำหนด Float.NaN เฉพาะคุณสมบัติของอินสแตนซ์ RawFrame.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งคืนจะต้องถูกกำหนดเสมอและไม่มี Float.NaN. ค่าที่กำหนดจะต้องถูกกำหนดด้วย; กำหนด Float.NaN เฉพาะคุณสมบัติของอินสแตนซ์ RawFrame.

**ผลลัพธ์:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งคืนจะต้องถูกกำหนดเสมอและไม่มี Float.NaN. ค่าที่กำหนดจะต้องถูกกำหนดด้วย; กำหนด Float.NaN เฉพาะคุณสมบัติของอินสแตนซ์ RawFrame.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

รับหรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งคืนจะต้องถูกกำหนดเสมอและไม่มี Float.NaN. ค่าที่กำหนดจะต้องถูกกำหนดด้วย; กำหนด Float.NaN เฉพาะคุณสมบัติของอินสแตนซ์ RawFrame.

**ผลลัพธ์:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

รับหรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งคืนจะต้องถูกกำหนดเสมอและไม่มี Float.NaN. ค่าที่กำหนดจะต้องถูกกำหนดด้วย; กำหนด Float.NaN เฉพาะคุณสมบัติของอินสแตนซ์ RawFrame.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

รับหรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งคืนจะต้องถูกกำหนดเสมอและไม่มี Float.NaN. ค่าที่กำหนดจะต้องถูกกำหนดด้วย; กำหนด Float.NaN เฉพาะคุณสมบัติของอินสแตนซ์ RawFrame.

**ผลลัพธ์:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

รับหรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งคืนจะต้องถูกกำหนดเสมอและไม่มี Float.NaN. ค่าที่กำหนดจะต้องถูกกำหนดด้วย; กำหนด Float.NaN เฉพาะคุณสมบัติของอินสแตนซ์ RawFrame.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

คุณสมบัติกำหนดว่ารูปร่างจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ. อ่าน/เขียน [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**ผลลัพธ์:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

คุณสมบัติกำหนดว่ารูปร่างจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ. อ่าน/เขียน [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

คืนค่าอัตลักษณ์ภายในที่มีขอบเขตการนำเสนอซึ่งตั้งใจให้ใช้โดยแอด-อินหรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร. อ่านอย่างเดียว long. ดูเพิ่มเติม \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**ผลลัพธ์:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

คืนค่ารหัสเฉพาะสไลด์ที่คงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากที่ใดในเอกสารก็ได้. อ่านอย่างเดียว long. ดูเพิ่มเติม \#getUniqueId.getUniqueId.

**ผลลัพธ์:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

คืนค่าหรือกำหนดข้อความแทนที่สัมพันธ์กับรูปร่าง. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

คืนค่าหรือกำหนดข้อความแทนที่สัมพันธ์กับรูปร่าง. อ่าน/เขียน String.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

คืนค่าหรือกำหนดหัวข้อความแทนที่สัมพันธ์กับรูปร่าง. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

คืนค่าหรือกำหนดหัวข้อความแทนที่สัมพันธ์กับรูปร่าง. อ่าน/เขียน String.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

คืนค่า หรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่าเป็นสตริงว่างหากต้องการ. อ่าน/เขียน String.

**ผลลัพธ์:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

คืนค่า หรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่าเป็นสตริงว่างหากต้องการ. อ่าน/เขียน String.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

รับหรือกำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ผลลัพธ์:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

รับหรือกำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

คืนค่าการล็อกของรูปร่าง. อ่านอย่างเดียว [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**ผลลัพธ์:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

กำหนดว่ารูปร่างถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว boolean.

--------------------

คุณสมบัติ #getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**ผลลัพธ์:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

คืนค่า parent GroupShape object หากรูปร่างถูกจัดกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

คุณสมบัติ #isGrouped.isGrouped determines whether the shape is grouped.

**ผลลัพธ์:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่า Parent_Immediate object. อ่านอย่างเดียว IDOMObject.

**ผลลัพธ์:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final Rectangle2D.Float getVisualBounds()
```

รับขอบเขตการมองเห็นของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์.

**ผลลัพธ์:**
java.awt.geom.Rectangle2D.Float - A java.awt.geom.Rectangle2D.Float that represents the visual bounds of the shape in slide coordinates.

--------------------

สี่เหลี่ยมที่ส่งคืนแสดงขอบเขตที่แนวแกนของเนื้อหาทั้งหมดที่สร้างโดยรูปร่างระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์. ขอบเขตเหล่านี้อาจแตกต่างจากขอบเขตโมเดลของรูปร่าง \#getX.getX/\#setX(float).setX(float), \#getY.getY/\#setY(float).setY(float), \#getWidth.getWidth/\#setWidth(float).setWidth(float), \#getHeight.getHeight/\#setHeight(float).setHeight(float) และอาจมีพิกัดลบหากเนื้อหาที่เรนเดร่อออกนอกต้นจุดของสไลด์. ขอบเขตการมองเห็นคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์เช่นการแปลง (เช่น การหมุน), ความกว้างและการเชื่อมต่อของเส้น, การจัดวางข้อความและการล้น, รูปร่าง SmartArt, และผลลัพธ์การจัดวางอื่น ๆ ที่ส่งผลต่อลักษณะที่แสดงผลสุดท้ายของรูปร่าง. ขอบเขตที่ส่งคืนไม่ได้ถูกตัดคลิปให้พอดีกับสี่เหลี่ยมสไลด์.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนค่า parent slide ของรูปร่าง. อ่านอย่างเดียว [IBaseSlide](../../com.aspose.slides/ibaseslide).

**ผลลัพธ์:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่า parent presentation ของสไลด์. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**ผลลัพธ์:**
[IPresentation](../../com.aspose.slides/ipresentation)