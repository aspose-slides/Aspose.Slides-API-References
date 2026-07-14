---
title: IShape
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงรูปทรงบนสไลด์.
type: docs
url: /th/com.aspose.slides/ishape/
---
**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

แสดงถึงรูปร่างบนสไลด์.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | Determines whether the shape is TextHolder. |
| [getPlaceholder()](#getPlaceholder--) | Returns the placeholder for a shape. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | Adds a new placeholder if there is no and sets placeholder properties to a specified one. |
| [removePlaceholder()](#removePlaceholder--) | Defines that this shape isn't a placeholder. |
| [getCustomData()](#getCustomData--) | Returns the shape's custom data. |
| [getRawFrame()](#getRawFrame--) | Returns or sets the raw shape frame's properties. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | Returns or sets the raw shape frame's properties. |
| [getFrame()](#getFrame--) | Returns or sets the shape frame's properties. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | Returns or sets the shape frame's properties. |
| [getLineFormat()](#getLineFormat--) | Returns the LineFormat object that contains line formatting properties for a shape. |
| [getThreeDFormat()](#getThreeDFormat--) | Returns the ThreeDFormat object that contains line formatting properties for a shape. |
| [getEffectFormat()](#getEffectFormat--) | Returns the EffectFormat object which contains pixel effects applied to a shape. |
| [getFillFormat()](#getFillFormat--) | Returns the FillFormat object that contains fill formatting properties for a shape. |
| [getImage()](#getImage--) | Returns shape thumbnail. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | Returns shape thumbnail. |
| [getHidden()](#getHidden--) | Determines whether the shape is hidden. |
| [setHidden(boolean value)](#setHidden-boolean-) | Determines whether the shape is hidden. |
| [getZOrderPosition()](#getZOrderPosition--) | Returns the position of a shape in the z-order. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | Returns the number of connection sites on the shape. |
| [getRotation()](#getRotation--) | Returns or sets the number of degrees the specified shape is rotated around the z-axis. |
| [setRotation(float value)](#setRotation-float-) | Returns or sets the number of degrees the specified shape is rotated around the z-axis. |
| [getX()](#getX--) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. |
| [setX(float value)](#setX-float-) | Gets or sets the x-coordinate of the shape's upper-left corner, measured in points. |
| [getY()](#getY--) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. |
| [setY(float value)](#setY-float-) | Gets or sets the y-coordinate of the shape's upper-left corner, measured in points. |
| [getWidth()](#getWidth--) | Gets or sets the width of the shape, measured in points. |
| [setWidth(float value)](#setWidth-float-) | Gets or sets the width of the shape, measured in points. |
| [getHeight()](#getHeight--) | Gets or sets the height of the shape, measured in points. |
| [setHeight(float value)](#setHeight-float-) | Gets or sets the height of the shape, measured in points. |
| [getAlternativeText()](#getAlternativeText--) | Returns or sets the alternative text associated with a shape. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | Returns or sets the alternative text associated with a shape. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | Returns or sets the title of alternative text associated with a shape. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | Returns or sets the title of alternative text associated with a shape. |
| [getName()](#getName--) | Returns or sets the name of a shape. |
| [setName(String value)](#setName-java.lang.String-) | Returns or sets the name of a shape. |
| [isDecorative()](#isDecorative--) | Gets or sets 'Mark as decorative' option Reed/write boolean. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | Gets or sets 'Mark as decorative' option Reed/write boolean. |
| [getShapeLock()](#getShapeLock--) | Returns shape's locks. |
| [getUniqueId()](#getUniqueId--) | Returns an internal, presentation-scoped identifier intended for use by add-ins or other code. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | Returns a slide-scoped unique identifier that remains constant for the lifetime of the shape and lets PowerPoint or interop code reliably reference the shape from anywhere in the document. |
| [isGrouped()](#isGrouped--) | Determines whether the shape is grouped. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | Property specifies how a shape will render in black-and-white display mode.. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | Property specifies how a shape will render in black-and-white display mode.. |
| [getParentGroup()](#getParentGroup--) | Returns parent GroupShape object if shape is grouped. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | Saves content of Shape as SVG file. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | Saves content of Shape as SVG file. |
| [getBasePlaceholder()](#getBasePlaceholder--) | Returns a basic placeholder shape (shape from the layout and/or master slide that the current shape is inherited from). |
### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

กำหนดว่ารูปร่างเป็น TextHolder หรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean
### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

คืนค่า placeholder สำหรับรูปร่าง. อ่านอย่างเดียว [IPlaceholder](../../com.aspose.slides/iplaceholder).

**คืนค่า:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)
### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ไปยังอ็อบเจ็กต์ที่ระบุ

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder to copy content from. |

**คืนค่า:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - New [IPlaceholder](../../com.aspose.slides/iplaceholder).
### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

คืนค่าข้อมูลแบบกำหนดเองของรูปร่าง. อ่านอย่างเดียว [ICustomData](../../com.aspose.slides/icustomdata).

**คืนค่า:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

คืนค่าหรือกำหนดคุณสมบัติของ raw shape frame. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //หรือ
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //โค้ดเช่นนี้อาจทำให้เกิดสถานการณ์ที่ไม่ชัดเจน ดังนั้นจึงมีการเพิ่มข้อจำกัดในการใช้ค่าที่ไม่ได้กำหนดสำหรับ IShape.getFrame() ค่าของ x, y, width, height, flipH, flipV และ rotationAngle ต้องถูกกำหนด (ไม่ใช่ Float.NaN หรือ NullableBool.NotDefined) ตัวอย่างโค้ดข้างต้นตอนนี้จะโยนข้อยกเว้น ArgumentException exception.
>  //นี่ใช้กับกรณีการใช้งานเหล่านี้:
>  IShape shape = ...;
>  shape.setFrame(...); // ไม่สามารถเป็นค่าที่ไม่ได้กำหนด
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // รูปเชื่อมโยงกับ placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ตอนนี้รูปสืบทอดค่า x, y, height, flipH, flipV จาก placeholder และตั้งค่าความกว้าง=100 และ rotationAngle=0.
```

**คืนค่า:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

คืนค่าหรือกำหนดคุณสมบัติของ raw shape frame. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //หรือ
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //โค้ดดังกล่าวอาจทำให้เกิดสถานการณ์ที่ไม่ชัดเจน ดังนั้นจึงมีการเพิ่มข้อจำกัดในการใช้ค่าที่ไม่ได้กำหนดสำหรับ IShape.getFrame() ค่าของ x, y, width, height, flipH, flipV และ rotationAngle ต้องถูกกำหนด (ไม่ใช่ Float.NaN หรือ NullableBool.NotDefined) ตัวอย่างโค้ดด้านบนตอนนี้จะโยนข้อยกเว้น ArgumentException
>  //ใช้กับกรณีการใช้งานเหล่านี้:
>  IShape shape = ...;
>  shape.setFrame(...); // ไม่สามารถเป็นค่าที่ไม่ได้กำหนด
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
>  But IShape.RawFrame frame properties can be undefined. This make sense when shape is linked to placeholder. Then undefined shape frame values is overridden from the parent placeholder shape. If there is no parent placeholder shape for that shape then that shape uses default values when it evaluates effective frame based on its IShape.RawFrame. Default values are 0 and NullableBool.False for x, y, width, height, flipH, flipV and rotationAngle. For example:
>  IShape shape = ...; // shape is linked to placeholder
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ตอนนี้รูปสืบทอดค่า x, y, height, flipH, flipV จาก placeholder และตั้งค่าความกว้าง=100 และ rotationAngle=0.
```

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

คืนค่า或กำหนดคุณสมบัติของ shape frame. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

ค่าของแต่ละคุณสมบัติของอินสแตนซ์ IShapeFrame ที่ส่งคืนจะไม่เป็น undefined (ไม่ใช่ NaN หรือ NotDefined) ค่าของแต่ละคุณสมบัติของอินสแตนซ์ IShapeFrame ที่กำหนดต้องไม่เป็น undefined (ต้องไม่เป็น NaN หรือ NotDefined) คุณสามารถตั้งค่าที่ไม่กำหนดให้กับคุณสมบัติของอินสแตนซ์ RawFrame ได้

**คืนค่า:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

คืนค่า或กำหนดคุณสมบัติของ shape frame. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

ค่าของแต่ละคุณสมบัติของอินสแตนซ์ IShapeFrame ที่ส่งคืนจะไม่เป็น undefined (ไม่ใช่ NaN หรือ NotDefined) ค่าของแต่ละคุณสมบัติของอินสแตนซ์ IShapeFrame ที่กำหนดต้องไม่เป็น undefined (ต้องไม่เป็น NaN หรือ NotDefined) คุณสามารถตั้งค่าที่ไม่กำหนดให้กับคุณสมบัติของอินสแตนซ์ RawFrame ได้

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

คืนค่าอ็อบเจ็กต์ LineFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

คืนค่าอ็อบเจ็กต์ ThreeDFormat ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. อ่านอย่างเดียว [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**คืนค่า:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

คืนค่าอ็อบเจ็กต์ EffectFormat ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. อ่านอย่างเดียว [IEffectFormat](../../com.aspose.slides/ieffectformat).

**คืนค่า:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

คืนค่าอ็อบเจ็กต์ FillFormat ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับรูปร่าง. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

คืนค่าภาพย่อของรูปร่าง. ShapeThumbnailBounds.Shape shape thumbnail bounds type is used by default.

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.
### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

คืนค่าภาพย่อของรูปร่าง.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| bounds | int | Shape thumbnail bounds type. |
| scaleX | float | X scale |
| scaleY | float | Y scale |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail or null in case when ShapeThumbnailBounds.Appearance is used and a shape doesn't have visible elements.
### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

คืนค่าตำแหน่งของรูปร่างใน z-order. Shapes[0] คืนค่ารูปร่างที่ด้านหลังของ z-order, และ Shapes[Shapes.Count - 1] คืนค่ารูปร่างที่ด้านหน้าของ z-order. อ่านอย่างเดียว int.

**คืนค่า:**
int
### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว int.

**คืนค่า:**
int
### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

คืนค่า或กำหนดจำนวนองศาที่รูปร่างระบุถูกหมุนรอบแกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน float.

--------------------

ค่าที่ส่งกลับจะเป็นค่าที่กำหนดเสมอ (ไม่เป็น Float.NaN) ค่าที่กำหนดต้องเป็นค่าที่กำหนด (ไม่เป็น Float.NaN) คุณสามารถตั้งค่าที่ไม่กำหนดให้กับคุณสมบัติของอินสแตนซ์ RawFrame ได้

**คืนค่า:**
float
### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

คืนค่า或กำหนดจำนวนองศาที่รูปร่างระบุถูกหมุนรอบแกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนา�Clock. อ่าน/เขียน float.

--------------------

ค่าที่ส่งกลับจะเป็นค่าที่กำหนดเสมอ (ไม่เป็น Float.NaN) ค่าที่กำหนดต้องเป็นค่าที่กำหนด (ไม่เป็น Float.NaN) คุณสามารถตั้งค่าที่ไม่กำหนดให้กับคุณสมบัติของอินสแตนซ์ RawFrame ได้

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

รับหรือกำหนดค่าพิกัด x ของมุมซ้ายบนของรูปร่าง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งกลับจะเป็นค่าที่กำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นค่าที่กำหนด; ให้ตั้งค่า Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น

**คืนค่า:**
float
### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

รับหรือกำหนดค่าพิกัด x ของมุมซ้ายบนของรูปร่าง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งกลับจะเป็นค่าที่กำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นค่าที่กำหนด; ให้ตั้งค่า Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

รับหรือกำหนดค่าพิกัด y ของมุมซ้ายบนของรูปร่าง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งกลับจะเป็นค่าที่กำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นค่าที่กำหนด; ให้ตั้งค่า Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น

**คืนค่า:**
float
### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

รับหรือกำหนดค่าพิกัด y ของมุมซ้ายบนของรูปร่าง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งกลับจะเป็นค่าที่กำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นค่าที่กำหนด; ให้ตั้งค่า Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

รับหรือกำหนดความกว้างของรูปร่าง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งกลับจะเป็นค่าที่กำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นค่าที่กำหนด; ให้ตั้งค่า Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น

**คืนค่า:**
float
### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

รับหรือกำหนดความกว้างของรูปร่าง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งกลับจะเป็นค่าที่กำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นค่าที่กำหนด; ให้ตั้งค่า Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

รับหรือกำหนดความสูงของรูปร่าง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งกลับจะเป็นค่าที่กำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นค่าที่กำหนด; ให้ตั้งค่า Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น

**คืนค่า:**
float
### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

รับหรือกำหนดความสูงของรูปร่าง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่ส่งกลับจะเป็นค่าที่กำหนดเสมอและไม่เป็น Float.NaN. ค่าที่กำหนดต้องเป็นค่าที่กำหนด; ให้ตั้งค่า Float.NaN เฉพาะกับคุณสมบัติของอินสแตนซ์ RawFrame เท่านั้น

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

คืนค่า或กำหนดข้อความสำรองที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

คืนค่า或กำหนดข้อความสำรองที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

คืนค่า或กำหนดชื่อเรื่องของข้อความสำรองที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

คืนค่า或กำหนดชื่อเรื่องของข้อความสำรองที่เชื่อมโยงกับรูปร่าง. อ่าน/เขียน String.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

คืนค่า或กำหนดชื่อของรูปร่าง. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

คืนค่า或กำหนดชื่อของรูปร่าง. อ่าน/เขียน String.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

รับหรือกำหนดตัวเลือก 'Mark as decorative' Reed/write boolean.

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
public abstract void setDecorative(boolean value)
```

รับหรือกำหนดตัวเลือก 'Mark as decorative' Reed/write boolean.

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
public abstract IBaseShapeLock getShapeLock()
```

คืนค่าล็อคของรูปร่าง. อ่านอย่างเดียว [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**คืนค่า:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

คืนค่าอัลกอริทึมภายใน, presentation-scoped identifier ที่ใช้สำหรับ add-ins หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกเปลี่ยนโดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือเป็นคีย์ที่คงที่. อ่านอย่างเดียว long. See also \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**คืนค่า:**
long
### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

คืนค่า slide-scoped unique identifier ที่คงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop อ้างอิงรูปร่างได้อย่างมั่นคงจากที่ใดก็ได้ในเอกสาร. อ่านอย่างเดียว long. See also \#getUniqueId.getUniqueId.

**คืนค่า:**
long
### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่. อ่านอย่างเดียว boolean.

--------------------

Property \#getParentGroup.getParentGroup returns parent GroupShape object if shape is grouped.

**คืนค่า:**
boolean
### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

Property ระบุว่ารูปร่างจะเรนเดอร์อย่างไรในโหมดสีขาว-ดำ. อ่าน/เขียน [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**คืนค่า:**
byte
### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

Property ระบุว่ารูปร่างจะเรนเดอร์อย่างไรในโหมดสีขาว-ดำ. อ่าน/เขียน [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

คืนค่า parent GroupShape object หากรูปร่างเป็นกลุ่ม. หากไม่ใช่จะคืนค่า null. อ่านอย่างเดียว [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

Property \#isGrouped.isGrouped determines whether the shape is grouped.

**คืนค่า:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Target stream |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG generation options |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

คืนค่า placeholder พื้นฐาน (รูปร่างจาก layout และ/หรือ master slide ที่รูปร่างปัจจุบันสืบทอดมาจาก)

--------------------

> ```
> // ดึงเอาเอฟเฟกต์การเคลื่อนไหวทั้งหมด (master/layout/slide) ของรูปร่าง placeholder
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

null จะถูกคืนค่าหากรูปร่างปัจจุบันไม่ได้สืบทอด

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)