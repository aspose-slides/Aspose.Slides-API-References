---
title: Shape
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงรูปร่างบนสไลด์.
type: docs
url: /th/com.aspose.slides/shape/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำการ Implement:**
[com.aspose.slides.IShape](../../com.aspose.slides/ishape), com.aspose.slides.IDOMObject
```
public class Shape implements IShape, IDOMObject
```

แสดงถึงรูปร่างบนสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. |
| [getPlaceholder()](#getPlaceholder--) | คืนค่า placeholder สำหรับรูปร่าง. |
| [removePlaceholder()](#removePlaceholder--) | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้กับอันที่ระบุ. |
| [getBasePlaceholder()](#getBasePlaceholder--) | คืนรูป placeholder พื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือสไลด์แม่ที่รูปปัจจุบันสืบทอดมาจาก). |
| [getCustomData()](#getCustomData--) | คืนข้อมูลที่กำหนดเองของรูปร่าง. |
| [getRawFrame()](#getRawFrame--) | คืนหรือกำหนดคุณสมบัติของเฟรมรูปดิบของรูปร่าง. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | คืนหรือกำหนดคุณสมบัติของเฟรมรูปดิบของรูปร่าง. |
| [getFrame()](#getFrame--) | คืนหรือกำหนดคุณสมบัติของเฟรมรูปดิบของรูปร่าง. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | คืนหรือกำหนดคุณสมบัติของเฟรมรูปดิบของรูปร่าง. |
| [getLineFormat()](#getLineFormat--) | คืนออบเจกต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. |
| [getThreeDFormat()](#getThreeDFormat--) | คืนออบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง. |
| [getEffectFormat()](#getEffectFormat--) | คืนออบเจกต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. |
| [getFillFormat()](#getFillFormat--) | คืนออบเจกต์ FillFormat ที่มีคุณสมบัติการเติมสีสำหรับรูปร่าง. |
| [getImage()](#getImage--) | คืนภาพย่อของรูปร่าง. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | คืนภาพย่อของรูปร่าง. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | บันทึกเนื้อหของ Shape เป็นไฟล์ SVG. |
| [getHyperlinkClick()](#getHyperlinkClick--) | คืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับการคลิกเมาส์. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | คืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับการคลิกเมาส์. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | คืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับการวางเมาส์เหนือ. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | คืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับการวางเมาส์เหนือ. |
| [getHyperlinkManager()](#getHyperlinkManager--) | คืนตัวจัดการไฮเปอร์ลิงก์. |
| [getHidden()](#getHidden--) | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. |
| [setHidden(boolean value)](#setHidden-boolean-) | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. |
| [getZOrderPosition()](#getZOrderPosition--) | คืนตำแหน่งของรูปร่างในลำดับ z. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | คืนจำนวนจุดเชื่อมต่อบนรูปร่าง. |
| [getRotation()](#getRotation--) | คืนหรือกำหนดจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z. |
| [setRotation(float value)](#setRotation-float-) | คืนหรือกำหนดจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z. |
| [getX()](#getX--) | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. |
| [setX(float value)](#setX-float-) | รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. |
| [getY()](#getY--) | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. |
| [setY(float value)](#setY-float-) | รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. |
| [getWidth()](#getWidth--) | รับหรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด. |
| [setWidth(float value)](#setWidth-float-) | รับหรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด. |
| [getHeight()](#getHeight--) | รับหรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด. |
| [setHeight(float value)](#setHeight-float-) | รับหรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | คุณสมบัติระบุว่ารูปร่างจะเรนเดอร์ในโหมดสีขาว-ดำอย่างไร. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | คุณสมบัติระบุว่ารูปร่างจะเรนเดอร์ในโหมดสีขาว-ดำอย่างไร. |
| [getUniqueId()](#getUniqueId--) | คืนค่า identifier ภายในที่มีขอบเขตการนำเสนอ เพื่อใช้โดยส่วนเสริมหรือโค้ดอื่น. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | คืนค่า identifier ที่มีขอบเขตสไลด์และเป็นค่าเฉพาะที่คงที่ตลอดอายุของรูปร่าง และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากทุกตำแหน่งในเอกสารได้อย่างน่าเชื่อถือ. |
| [getAlternativeText()](#getAlternativeText--) | คืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปร่าง. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | คืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปร่าง. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | คืนหรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปร่าง. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | คืนหรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปร่าง. |
| [getName()](#getName--) | คืนหรือกำหนดชื่อของรูปร่าง. |
| [setName(String value)](#setName-java.lang.String-) | คืนหรือกำหนดชื่อของรูปร่าง. |
| [isDecorative()](#isDecorative--) | รับหรือกำหนดตัวเลือก 'Mark as decorative' แบบอ่าน/เขียน เป็น boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | รับหรือกำหนดตัวเลือก 'Mark as decorative' แบบอ่าน/เขียน เป็น boolean. |
| [getShapeLock()](#getShapeLock--) | คืนค่าการล็อกของรูปร่าง. |
| [isGrouped()](#isGrouped--) | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่. |
| [getParentGroup()](#getParentGroup--) | คืนออบเจกต์ GroupShape พ่อแม่หากรูปร่างเป็นกลุ่ม. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVisualBounds()](#getVisualBounds--) | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| [getSlide()](#getSlide--) | คืนสไลด์แม่ของรูปร่าง. |
| [getPresentation()](#getPresentation--) | คืนการนำเสนอแม่ของสไลด์. |

### isTextHolder() {#isTextHolder--}
```
public final boolean isTextHolder()
```

กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว boolean .

**คืนค่า:**
boolean
### getPlaceholder() {#getPlaceholder--}
```
public final IPlaceholder getPlaceholder()
```

คืนค่า placeholder สำหรับรูปร่าง. คืนค่า null หากรูปร่างไม่มี placeholder. อ่านอย่างเดียว [IPlaceholder](../../com.aspose.slides/iplaceholder).

--------------------

> ```
> The following example shows how to change Text in Placeholder.
>  
>  // สร้างอินสแตนซ์ของคลาส Presentation
>  Presentation pres = new Presentation("ReplacingText.pptx");
>  try {
>      // เข้าถึงสไลด์แรก
>      ISlide sld = pres.getSlides().get_Item(0);
>      // วนผ่านรูปร่างเพื่อค้นหา placeholder
>      for (IShape shp : sld.getShapes())
>          if (shp.getPlaceholder() != null)
>          {
>              // เปลี่ยนข้อความในแต่ละ placeholder
>              ((IAutoShape)shp).getTextFrame().setText("This is a Placeholder");
>          }
>      // บันทึกการนำเสนอไปยังดิสก์
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
>      for (IShape shape : slide.getSlide().getShapes()) // วนผ่านสไลด์
>      {
>          if (shape.getPlaceholder() != null && shape instanceof AutoShape)
>          {
>              String text = "";
>              if (shape.getPlaceholder().getType() == PlaceholderType.CenteredTitle) // PowerPoint แสดงข้อความ "Click to add title"
>              {
>                  text = "Add Title";
>              }
>              else if (shape.getPlaceholder().getType() == PlaceholderType.Subtitle) // เพิ่ม subtitle
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


**คืนค่า:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)
### removePlaceholder() {#removePlaceholder--}
```
public final void removePlaceholder()
```

กำหนดว่รูปร่างนี้ไม่ใช่ placeholder.

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public final IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้กับอันที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder ที่จะคัดลอกเนื้อหา. |

**คืนค่า:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - ใหม่ #getPlaceholder.getPlaceholder.
### getBasePlaceholder() {#getBasePlaceholder--}
```
public final IShape getBasePlaceholder()
```

คืนรูป placeholder พื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือสไลด์แม่ที่รูปปัจจุบันสืบทอดมาจาก).

--------------------

> ```
> // ดึงเอฟเฟกต์แอนิเมชันทั้งหมด (master/layout/slide) ของรูปร่าง placeholder
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

จะคืนค่า null หากรูปร่างปัจจุบันไม่ได้สืบทอด.

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

คืนข้อมูลที่กำหนดเองของรูปร่าง. อ่านอย่างเดียว [ICustomData](../../com.aspose.slides/icustomdata).

**คืนค่า:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public final IShapeFrame getRawFrame()
```

คืนหรือกำหนดคุณสมบัติของเฟรมรูปดิบของรูปร่าง. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //หรือ
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //โค้ดเช่นนี้อาจทำให้สถานการณ์ไม่ชัดเจน ดังนั้นได้มีการเพิ่มข้อจำกัดสำหรับการใช้ค่า undefined กับ IShape.getFrame() ค่า x, y, width, height, flipH, flipV และ rotationAngle ต้องถูกกำหนด (ไม่ใช่ Float.NaN หรือ NullableBool.NotDefined) ตัวอย่างโค้ดด้านบนตอนนี้จะโยนข้อยกเว้น ArgumentException exception.
>  //นี่ใช้กับกรณีต่อไปนี้:
>  IShape shape = ...;
>  shape.setFrame(...); // ไม่สามารถเป็น undefined ได้
>  IShapeCollection shapes = ...;
>  //พารามิเตอร์ x, y, width, height ไม่สามารถเป็น Float.NaN:
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
>  //แต่คุณสมบัติของเฟรม IShape.RawFrame สามารถเป็น undefined ได้ ซึ่งทำให้มีเหตุผลเมื่อรูปร่างเชื่อมโยงกับ placeholder แล้วค่าที่เป็น undefined ของเฟรมรูปร่างจะถูกแทนที่จาก placeholder พ่อแม่ หากไม่มี placeholder พ่อแม่สำหรับรูปร่างนั้น รูปร่างจะใช้ค่าเริ่มต้นเมื่อคำนวณเฟรมที่มีประสิทธิภาพบนพื้นฐานของ IShape.RawFrame ค่าเริ่มต้นคือ 0 และ NullableBool.False สำหรับ x, y, width, height, flipH, flipV และ rotationAngle ตัวอย่างเช่น:
>  IShape shape = ...; // รูปร่างเชื่อมโยงกับ placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ขณะนี้รูปร่างสืบทอดค่า x, y, height, flipH, flipV จาก placeholder และทำการทับค่า width=100 และ rotationAngle=0.{code}
> ```


**คืนค่า:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public final void setRawFrame(IShapeFrame value)
```

คืนหรือกำหนดคุณสมบัติของเฟรมรูปดิบของรูปร่าง. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //หรือ
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //โค้ดเช่นนี้อาจทำให้สถานการณ์ไม่ชัดเจน ดังนั้นได้เพิ่มข้อจำกัดสำหรับการใช้ค่า undefined กับ IShape.getFrame() ค่า x, y, width, height, flipH, flipV และ rotationAngle ต้องถูกกำหนด (ไม่ใช่ Float.NaN หรือ NullableBool.NotDefined) ตัวอย่างโค้ดด้านบนตอนนี้จะโยนข้อยกเว้น ArgumentException exception.
>  //นี่ใช้กับกรณีต่อไปนี้:
>  IShape shape = ...;
>  shape.setFrame(...); // ไม่สามารถเป็น undefined ได้
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
>  //แต่คุณสมบัติของเฟรม IShape.RawFrame สามารถเป็น undefined ได้ ซึ่งมีเหตุผลเมื่อรูปร่างเชื่อมโยงกับ placeholder จากนั้นค่าที่เป็น undefined ของเฟรมรูปร่างจะถูกทับโดยค่าใน placeholder พ่อแม่ หากไม่มี placeholder พ่อแม่สำหรับรูปร่างนั้น รูปร่างจะใช้ค่าเริ่มต้นเมื่อคำนวณเฟรมที่มีประสิทธิภาพบนพื้นฐานของ IShape.RawFrame ค่าเริ่มต้นคือ 0 และ NullableBool.False สำหรับ x, y, width, height, flipH, flipV และ rotationAngle. ตัวอย่างเช่น:
>  IShape shape = ...; // รูปร่างเชื่อมโยงกับ placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ตอนนี้รูปร่างสืบทอดค่า x, y, height, flipH, flipV จาก placeholder และแทนที่ค่า width=100 และ rotationAngle=0.{code}
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

คืนหรือกำหนดคุณสมบัติของเฟรมรูปร่าง. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

ค่าของแต่ละคุณสมบัติของอินสแตนซ์ IShapeFrame ที่คืนค่ามาไม่เป็น undefined (ไม่ใช่ NaN หรือ NotDefined). ค่าของแต่ละคุณสมบัติของอินสแตนซ์ IShapeFrame ที่กำหนดต้องไม่เป็น undefined (ต้องไม่เป็น NaN หรือ NotDefined). คุณสามารถตั้งค่าที่เป็น undefined ให้กับคุณสมบัติของอินสแตนซ์ RawFrame ได้.

**คืนค่า:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

คืนหรือกำหนดคุณสมบัติของเฟรมรูปร่าง. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

ค่าของแต่ละคุณสมบัติของอินสแตนซ์ IShapeFrame ที่คืนค่ามาไม่เป็น undefined (ไม่ใช่ NaN หรือ NotDefined). ค่าของแต่ละคุณสมบัติของอินสแตนซ์ IShapeFrame ที่กำหนดต้องไม่เป็น undefined (ต้องไม่เป็น NaN หรือ NotDefined). คุณสามารถตั้งค่าที่เป็น undefined ให้กับคุณสมบัติของอินสแตนซ์ RawFrame ได้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

คืนออบเจกต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public IThreeDFormat getThreeDFormat()
```

คืนออบเจกต์ ThreeDFormat ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3d. อ่านอย่างเดียว [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**คืนค่า:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public IEffectFormat getEffectFormat()
```

คืนออบเจกต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [IEffectFormat](../../com.aspose.slides/ieffectformat).

**คืนค่า:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public IFillFormat getFillFormat()
```

คืนออบเจกต์ FillFormat ที่มีคุณสมบัติการเติมสีสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเติมสี. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

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
>      // Accent 4, เบาขึ้น 80%
>      IShape shape2 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 70, 50, 50);
>      shape2.getFillFormat().setFillType(FillType.Solid);
>      shape2.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.2f);
>      shape2.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.8f);
>      // Accent 4, เบาขึ้น 60%
>      IShape shape3 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 130, 50, 50);
>      shape3.getFillFormat().setFillType(FillType.Solid);
>      shape3.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.4f);
>      shape3.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.6f);
>      // Accent 4, เบาขึ้น 40%
>      IShape shape4 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 190, 50, 50);
>      shape4.getFillFormat().setFillType(FillType.Solid);
>      shape4.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.6f);
>      shape4.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.AddLuminance, 0.4f);
>      // Accent 4, เข้มขึ้น 25%
>      IShape shape5 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 250, 50, 50);
>      shape5.getFillFormat().setFillType(FillType.Solid);
>      shape5.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape5.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.75f);
>      // Accent 4, เข้มขึ้น 50%
>      IShape shape6 = slide.getShapes().addAutoShape(ShapeType.Rectangle, 10, 310, 50, 50);
>      shape6.getFillFormat().setFillType(FillType.Solid);
>      shape6.getFillFormat().getSolidFillColor().setSchemeColor(SchemeColor.Accent4);
>      shape6.getFillFormat().getSolidFillColor().getColorTransform().add(ColorTransformOperation.MultiplyLuminance, 0.5f);
>      pres.save("example_accent4.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public final IImage getImage()
```

คืนภาพย่อของรูปร่าง. ShapeThumbnailBounds.Shape ประเภทขอบเขตภาพย่อของรูปร่างจะถูกใช้โดยค่าเริ่มต้น.

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public final IImage getImage(int bounds, float scaleX, float scaleY)
```

คืนภาพย่อของรูปร่าง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bounds | int | ประเภทขอบเขตภาพย่อของรูปร่าง. |
| scaleX | float | สเกล X |
| scaleY | float | สเกล Y |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - ภาพย่อของรูปร่างหรือ null ในกรณีที่ใช้ ShapeThumbnailBounds.Appearance และรูปร่างไม่มีองค์ประกอบที่มองเห็น.
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

คืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับการคลิกเมาส์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**คืนค่า:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

คืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับการคลิกเมาส์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

คืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับการวางเมาส์เหนือ. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**คืนค่า:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

คืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับการวางเมาส์เหนือ. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

คืนตัวจัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**คืนค่า:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน boolean .

**คืนค่า:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public int getZOrderPosition()
```

คืนตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่ตำแหน่งสุดท้ายของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่ตำแหน่งแรกของลำดับ z. อ่านอย่างเดียว int .

**คืนค่า:**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public final int getConnectionSiteCount()
```

คืนจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว int .

**คืนค่า:**
int
### getRotation() {#getRotation--}
```
public final float getRotation()
```

คืนหรือกำหนดจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z. ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทับเข็มนาฬิกา. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาจะถูกกำหนดเสมอ (ไม่ใช่ Float.NaN). ค่าที่กำหนดต้องเป็นที่กำหนด (ไม่ใช่ Float.NaN). คุณสามารถตั้งค่าที่เป็น undefined ให้กับคุณสมบัติของอินสแตนซ์ RawFrame ได้.

**คืนค่า:**
float
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```

คืนหรือกำหนดจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z. ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทับเข็มนาฬิกา. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาจะถูกกำหนดเสมอ (ไม่ใช่ Float.NaN). ค่าที่กำหนดต้องเป็นที่กำหนด (ไม่ใช่ Float.NaN). คุณสามารถตั้งค่าที่เป็น undefined ให้กับคุณสมบัติของอินสแตนซ์ RawFrame ได้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public final float getX()
```

รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาจะถูกกำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นที่กำหนด; กำหนด Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น.

**คืนค่า:**
float
### setX(float value) {#setX-float-}
```
public final void setX(float value)
```

รับหรือกำหนดพิกัด x ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาจะถูกกำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นที่กำหนด; กำหนด Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public final float getY()
```

รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาจะถูกกำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นที่กำหนด; กำหนด Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น.

**คืนค่า:**
float
### setY(float value) {#setY-float-}
```
public final void setY(float value)
```

รับหรือกำหนดพิกัด y ของมุมซ้ายบนของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาจะถูกกำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นที่กำหนด; กำหนด Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public final float getWidth()
```

รับหรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาจะถูกกำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นที่กำหนด; กำหนด Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น.

**คืนค่า:**
float
### setWidth(float value) {#setWidth-float-}
```
public final void setWidth(float value)
```

รับหรือกำหนดความกว้างของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาจะถูกกำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นที่กำหนด; กำหนด Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

รับหรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาจะถูกกำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นที่กำหนด; กำหนด Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น.

**คืนค่า:**
float
### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

รับหรือกำหนดความสูงของรูปร่าง, วัดเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาจะถูกกำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นที่กำหนด; กำหนด Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public final byte getBlackWhiteMode()
```

คุณสมบัติระบุว่ารูปร่างจะเรนเดอร์ในโหมดสีขาว-ดำอย่างไร. อ่าน/เขียน [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**คืนค่า:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public final void setBlackWhiteMode(byte value)
```

คุณสมบัติระบุว่ารูปร่างจะเรนเดอร์ในโหมดสีขาว-ดำอย่างไร. อ่าน/เขียน [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getUniqueId() {#getUniqueId--}
```
public final long getUniqueId()
```

คืนค่า identifier ภายในที่มีขอบเขตการนำเสนอเพื่อใช้โดยส่วนเสริมหรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร. อ่านอย่างเดียว long. ดูเพิ่มเติม #getOfficeInteropShapeId.getOfficeInteropShapeId.

**คืนค่า:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public final long getOfficeInteropShapeId()
```

คืนค่า identifier ที่มีขอบเขตสไลด์และเป็นค่าเฉพาะที่คงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากทุกตำแหน่งในเอกสารได้อย่างน่าเชื่อถือ. อ่านอย่างเดียว long. ดูเพิ่มเติม #getUniqueId.getUniqueId.

**คืนค่า:**
long
### getAlternativeText() {#getAlternativeText--}
```
public final String getAlternativeText()
```

คืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public final void setAlternativeText(String value)
```

คืนหรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public final String getAlternativeTextTitle()
```

คืนหรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public final void setAlternativeTextTitle(String value)
```

คืนหรือกำหนดหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```

คืนหรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่าเป็นสตริงว่างหากต้องการ. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

คืนหรือกำหนดชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่าเป็นสตริงว่างหากต้องการ. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public final boolean isDecorative()
```

รับหรือกำหนดตัวเลือก 'Mark as decorative' แบบอ่าน/เขียน เป็น boolean.

--------------------

> ```
> Presentation pres = new Presentation("sample.pptx");
>  try {
>     pres.getSlides().get_Item(0).getShapes().get_Item(0).setDecorative(true);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
boolean
### setDecorative(boolean value) {#setDecorative-boolean-}
```
public final void setDecorative(boolean value)
```

รับหรือกำหนดตัวเลือก 'Mark as decorative' แบบอ่าน/เขียน เป็น boolean.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShapeLock() {#getShapeLock--}
```
public IBaseShapeLock getShapeLock()
```

คืนค่าการล็อกของรูปร่าง. อ่านอย่างเดียว [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**คืนค่า:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### isGrouped() {#isGrouped--}
```
public final boolean isGrouped()
```

กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่. อ่านอย่างเดียว boolean.

--------------------

Property #getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**คืนค่า:**
boolean
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

คืนออบเจกต์ GroupShape พ่อแม่หากรูปร่างเป็นกลุ่ม. มิฉะนั้นคืน null. อ่านอย่างเดียว [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Property #isGrouped.isGrouped determines whether the shape is grouped.

**คืนค่า:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนออบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject
### getVisualBounds() {#getVisualBounds--}
```
public final RectF getVisualBounds()
```

รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์.

**คืนค่า:**
android.graphics.RectF - android.graphics.RectF ที่แสดงขอบเขตภาพของรูปร่างในพิกัดสไลด์.

--------------------

สี่เหลี่ยมที่คืนมาตัวแทนขอบเขตแนวแกนของเนื้อหาทั้งหมดที่รูปสร้างระหว่างการเรนเดอร์ในพื้นที่พิกัดสไลด์. ขอบเขตเหล่านี้อาจต่างจากขอบเขตโมเดลของรูปร่าง #getX.getX/#setX(float), #getY.getY/#setY(float), #getWidth.getWidth/#setWidth(float), #getHeight.getHeight/#setHeight(float) และอาจมีพิกัดเป็นลบหากเนื้อหาที่เรนเดอร์ขยายออกนอกจุดกำเนิดของสไลด์. ขอบเขตภาพคำนึงถึงแง่มุมที่เกี่ยวกับการเรนเดอร์ เช่น การแปลง (เช่น การหมุน), ความกว้างและการต่อของเส้น, การจัดวางข้อความและการล้น, รูปทรง SmartArt, และผลลัพธ์การจัดวางอื่น ๆ ที่มีผลต่อภาพสุดท้ายที่เรนเดอร์ของรูปร่าง. ขอบเขตที่คืนมาจะไม่ถูกตัดตามสี่เหลี่ยมสไลด์.
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนสไลด์แม่ของรูปร่าง. อ่านอย่างเดียว [IBaseSlide](../../com.aspose.slides/ibaseslide).

**คืนค่า:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนการนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation)