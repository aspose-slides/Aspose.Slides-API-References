---
title: IShape
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงรูปทรงบนสไลด์หนึ่ง.
type: docs
url: /th/com.aspose.slides/ishape/
---
**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IHyperlinkContainer](../../com.aspose.slides/ihyperlinkcontainer)
```
public interface IShape extends ISlideComponent, IHyperlinkContainer
```

แสดงถึงรูปทรงบนสไลด์หนึ่ง.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isTextHolder()](#isTextHolder--) | กำหนดว่ารูปทรงเป็น TextHolder หรือไม่. |
| [getPlaceholder()](#getPlaceholder--) | คืนค่า placeholder สำหรับรูปทรง. |
| [addPlaceholder(IPlaceholder placeholderToCopyFrom)](#addPlaceholder-com.aspose.slides.IPlaceholder-) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่า properties ของ placeholder ให้เป็นค่าที่ระบุ. |
| [removePlaceholder()](#removePlaceholder--) | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder. |
| [getCustomData()](#getCustomData--) | คืนค่าข้อมูลกำหนดเองของรูปทรง. |
| [getRawFrame()](#getRawFrame--) | คืนค่าหรือกำหนด properties ของ raw shape frame. |
| [setRawFrame(IShapeFrame value)](#setRawFrame-com.aspose.slides.IShapeFrame-) | คืนค่าหรือกำหนด properties ของ raw shape frame. |
| [getFrame()](#getFrame--) | คืนค่าหรือกำหนด properties ของ shape frame. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | คืนค่าหรือกำหนด properties ของ shape frame. |
| [getLineFormat()](#getLineFormat--) | คืนค่าอ็อบเจกต์ LineFormat ที่มี properties การจัดรูปแบบเส้นสำหรับรูปทรง. |
| [getThreeDFormat()](#getThreeDFormat--) | คืนค่าอ็อบเจกต์ ThreeDFormat ที่มี properties การจัดรูปแบบสามมิติสำหรับรูปทรง. |
| [getEffectFormat()](#getEffectFormat--) | คืนค่าอ็อบเจกต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง. |
| [getFillFormat()](#getFillFormat--) | คืนค่าอ็อบเจกต์ FillFormat ที่มี properties การจัดรูปแบบการเติมสำหรับรูปทรง. |
| [getImage()](#getImage--) | คืนค่า thumbnail ของรูปทรง. |
| [getImage(int bounds, float scaleX, float scaleY)](#getImage-int-float-float-) | คืนค่า thumbnail ของรูปทรง. |
| [getHidden()](#getHidden--) | กำหนดว่ารูปทรงถูกซ่อนหรือไม่. |
| [setHidden(boolean value)](#setHidden-boolean-) | กำหนดว่ารูปทรงถูกซ่อนหรือไม่. |
| [getZOrderPosition()](#getZOrderPosition--) | คืนค่าตำแหน่งของรูปทรงใน z-order. |
| [getConnectionSiteCount()](#getConnectionSiteCount--) | คืนค่าจำนวน connection sites ของรูปทรง. |
| [getRotation()](#getRotation--) | คืนค่าหรือกำหนดจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z. |
| [setRotation(float value)](#setRotation-float-) | คืนค่าหรือกำหนดจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z. |
| [getX()](#getX--) | รับหรือกำหนดค่า x-coordinate ของมุมบนซ้ายของรูปทรง, หน่วยเป็นจุด. |
| [setX(float value)](#setX-float-) | รับหรือกำหนดค่า x-coordinate ของมุมบนซ้ายของรูปทรง, หน่วยเป็นจุด. |
| [getY()](#getY--) | รับหรือกำหนดค่า y-coordinate ของมุมบนซ้ายของรูปทรง, หน่วยเป็นจุด. |
| [setY(float value)](#setY-float-) | รับหรือกำหนดค่า y-coordinate ของมุมบนซ้ายของรูปทรง, หน่วยเป็นจุด. |
| [getWidth()](#getWidth--) | รับหรือกำหนดความกว้างของรูปทรง, หน่วยเป็นจุด. |
| [setWidth(float value)](#setWidth-float-) | รับหรือกำหนดความกว้างของรูปทรง, หน่วยเป็นจุด. |
| [getHeight()](#getHeight--) | รับหรือกำหนดความสูงของรูปทรง, หน่วยเป็นจุด. |
| [setHeight(float value)](#setHeight-float-) | รับหรือกำหนดความสูงของรูปทรง, หน่วยเป็นจุด. |
| [getAlternativeText()](#getAlternativeText--) | คืนค่า หรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง. |
| [setAlternativeText(String value)](#setAlternativeText-java.lang.String-) | คืนค่า หรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง. |
| [getAlternativeTextTitle()](#getAlternativeTextTitle--) | คืนค่า หรือกำหนดชื่อของข้อความแทนที่เชื่อมโยงกับรูปทรง. |
| [setAlternativeTextTitle(String value)](#setAlternativeTextTitle-java.lang.String-) | คืนค่า หรือกำหนดชื่อของข้อความแทนที่เชื่อมโยงกับรูปทรง. |
| [getName()](#getName--) | คืนค่า หรือกำหนดชื่อของรูปทรง. |
| [setName(String value)](#setName-java.lang.String-) | คืนค่า หรือกำหนดชื่อของรูปทรง. |
| [isDecorative()](#isDecorative--) | รับหรือกำหนดตัวเลือก 'Mark as decorative' แบบ boolean อ่าน/เขียน. |
| [setDecorative(boolean value)](#setDecorative-boolean-) | รับหรือกำหนดตัวเลือก 'Mark as decorative' แบบ boolean อ่าน/เขียน. |
| [getShapeLock()](#getShapeLock--) | คืนค่าการล็อกของรูปทรง. |
| [getUniqueId()](#getUniqueId--) | คืนค่า identifier ภายในที่มีขอบเขตระดับการนำเสนอ เพื่อใช้โดย add-ins หรือโค้ดอื่น. |
| [getOfficeInteropShapeId()](#getOfficeInteropShapeId--) | คืนค่า identifier ที่มีขอบเขตระดับสไลด์และคงที่ตลอดอายุของรูปทรง เพื่อให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงจากที่ใดในเอกสารก็ได้อย่างเชื่อถือได้. |
| [isGrouped()](#isGrouped--) | กำหนดว่ารูปทรงเป็นกลุ่มหรือไม่. |
| [getBlackWhiteMode()](#getBlackWhiteMode--) | คุณสมบัติระบุว่ารูปทรงจะถูกเรนเดอร์อย่างไรในโหมดสีดำ-ขาว. |
| [setBlackWhiteMode(byte value)](#setBlackWhiteMode-byte-) | คุณสมบัติระบุว่ารูปทรงจะถูกเรนเดอร์อย่างไรในโหมดสีดำ-ขาว. |
| [getParentGroup()](#getParentGroup--) | คืนค่าอ็อบเจกต์ GroupShape พาเรนท์ถ้ารูปทรงเป็นกลุ่ม. |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG. |
| [getBasePlaceholder()](#getBasePlaceholder--) | คืนค่า shape placeholder พื้นฐาน (shape จากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอดมาจาก). |

### isTextHolder() {#isTextHolder--}
```
public abstract boolean isTextHolder()
```

กำหนดว่ารูปทรงเป็น TextHolder หรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getPlaceholder() {#getPlaceholder--}
```
public abstract IPlaceholder getPlaceholder()
```

คืนค่า placeholder สำหรับรูปทรง. อ่านอย่างเดียว [IPlaceholder](../../com.aspose.slides/iplaceholder).

**คืนค่า:**
[IPlaceholder](../../com.aspose.slides/iplaceholder)

### addPlaceholder(IPlaceholder placeholderToCopyFrom) {#addPlaceholder-com.aspose.slides.IPlaceholder-}
```
public abstract IPlaceholder addPlaceholder(IPlaceholder placeholderToCopyFrom)
```

เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่า properties ของ placeholder ให้เป็นค่าที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| placeholderToCopyFrom | [IPlaceholder](../../com.aspose.slides/iplaceholder) | Placeholder เพื่อคัดลอกเนื้อหา. |

**คืนค่า:**
[IPlaceholder](../../com.aspose.slides/iplaceholder) - ใหม่ [IPlaceholder](../../com.aspose.slides/iplaceholder).

### removePlaceholder() {#removePlaceholder--}
```
public abstract void removePlaceholder()
```

กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder.

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

คืนค่าข้อมูลกำหนดเองของรูปทรง. อ่านอย่างเดียว [ICustomData](../../com.aspose.slides/icustomdata).

**คืนค่า:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getRawFrame() {#getRawFrame--}
```
public abstract IShapeFrame getRawFrame()
```

คืนค่าหรือกำหนด properties ของ raw shape frame. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //หรือ
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //โค้ดนี้อาจทำให้เกิดสถานการณ์ที่ไม่ชัดเจน. ดังนั้นจึงมีการเพิ่มข้อจำกัดสำหรับการใช้ค่าที่ไม่ได้กำหนดสำหรับ IShape.getFrame(). ค่าของ x, y, width, height, flipH, flipV และ rotationAngle ต้องถูกกำหนด (ไม่ใช่ Float.NaN หรือ NullableBool.NotDefined). ตัวอย่างโค้ดข้างต้นตอนนี้จะโยนข้อยกเว้น ArgumentException exception.
>  //ใช้ได้กับกรณีต่อไปนี้:
>  IShape shape = ...;
>  shape.setFrame(...); // ไม่สามารถเป็น undefined
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
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ตอนนี้ shape สืบทอดค่า x, y, height, flipH, flipV จาก placeholder และกำหนดค่า width=100 และ rotationAngle=0.
> ```


**คืนค่า:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setRawFrame(IShapeFrame value) {#setRawFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setRawFrame(IShapeFrame value)
```

คืนค่าหรือกำหนด properties ของ raw shape frame. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

> ```
> Code that attempts to assign undefined frame to IShape.getFrame() doesn't make sense in general case (particularly in case when parent GroupShape is multiple nested into other GroupShape-s). For example:
>  
>  IShape shape = ...;
>  shape.setFrame(new ShapeFrame(Float.NaN, Float.NaN, Float.NaN, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, Float.NaN));
>  //หรือ
>  slide.getShapes().addAutoShape(ShapeType.RoundCornerRectangle, Float.NaN, Float.NaN, Float.NaN, Float.NaN);
>  //โค้ดเช่นนี้อาจทำให้เกิดสถานการณ์ที่ไม่ชัดเจน ดังนั้นจึงมีการเพิ่มข้อจำกัดสำหรับการใช้ค่าที่ไม่ได้กำหนดสำหรับ IShape.getFrame() ค่าของ x, y, width, height, flipH, flipV และ rotationAngle ต้องถูกกำหนด (ไม่เป็น Float.NaN หรือ NullableBool.NotDefined) ตัวอย่างโค้ดข้างต้นตอนนี้จะโยนข้อยกเว้น ArgumentException exception.
>  //ใช้ได้กับกรณีต่อไปนี้:
>  IShape shape = ...;
>  shape.setFrame(...); // ไม่สามารถเป็น undefined
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
>  shape.setRawFrame(new ShapeFrame(Float.NaN, Float.NaN, 100, Float.NaN, NullableBool.NotDefined, NullableBool.NotDefined, 0)); // ตอนนี้ shape สืบทอดค่า x, y, height, flipH, flipV จาก placeholder และกำหนดค่า width=100 และ rotationAngle=0.
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

คืนค่าหรือกำหนด properties ของ shape frame. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

ค่าของแต่ละ property ของอินสแตนซ์ IShapeFrame ที่คืนค่าไม่เป็น undefined (ไม่เป็น NaN หรือ NotDefined). ค่าของแต่ละ property ของอินสแตนซ์ IShapeFrame ที่กำหนดต้องไม่เป็น undefined (ต้องไม่เป็น NaN หรือ NotDefined). คุณสามารถตั้งค่าที่เป็น undefined ให้กับ property ของอินสแตนซ์ RawFrame ได้.

**คืนค่า:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

คืนค่าหรือกำหนด properties ของ shape frame. อ่าน/เขียน [IShapeFrame](../../com.aspose.slides/ishapeframe).

--------------------

ค่าของแต่ละ property ของอินสแตนซ์ IShapeFrame ที่คืนค่าไม่เป็น undefined (ไม่เป็น NaN หรือ NotDefined). ค่าของแต่ละ property ของอินสแตนซ์ IShapeFrame ที่กำหนดต้องไม่เป็น undefined (ต้องไม่เป็น NaN หรือ NotDefined). คุณสามารถตั้งค่าที่เป็น undefined ให้กับ property ของอินสแตนซ์ RawFrame ได้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getLineFormat() {#getLineFormat--}
```
public abstract ILineFormat getLineFormat()
```

คืนค่าอ็อบเจกต์ LineFormat ที่มี properties การจัดรูปแบบเส้นสำหรับรูปทรง. อ่านอย่างเดียว [ILineFormat](../../com.aspose.slides/ilineformat).

**คืนค่า:**
[ILineFormat](../../com.aspose.slides/ilineformat)

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

คืนค่าอ็อบเจกต์ ThreeDFormat ที่มี properties การจัดรูปแบบสามมิติสำหรับรูปทรง. อ่านอย่างเดียว [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**คืนค่า:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

คืนค่าอ็อบเจกต์ EffectFormat ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง. อ่านอย่างเดียว [IEffectFormat](../../com.aspose.slides/ieffectformat).

**คืนค่า:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

คืนค่าอ็อบเจกต์ FillFormat ที่มี properties การจัดรูปแบบการเติมสำหรับรูปทรง. อ่านอย่างเดียว [IFillFormat](../../com.aspose.slides/ifillformat).

**คืนค่า:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

คืนค่า thumbnail ของรูปทรง. ShapeThumbnailBounds.Shape shape thumbnail bounds type ถูกใช้เป็นค่าเริ่มต้น.

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail.

### getImage(int bounds, float scaleX, float scaleY) {#getImage-int-float-float-}
```
public abstract IImage getImage(int bounds, float scaleX, float scaleY)
```

คืนค่า thumbnail ของรูปทรง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| bounds | int | ชนิดของ shape thumbnail bounds. |
| scaleX | float | สเกล X |
| scaleY | float | สเกล Y |

**คืนค่า:**
[IImage](../../com.aspose.slides/iimage) - Shape thumbnail หรือ null ในกรณีที่ใช้ ShapeThumbnailBounds.Appearance และรูปทรงไม่มีองค์ประกอบที่มองเห็นได้.

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

กำหนดว่ารูปทรงถูกซ่อนหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

กำหนดว่ารูปทรงถูกซ่อนหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getZOrderPosition() {#getZOrderPosition--}
```
public abstract int getZOrderPosition()
```

คืนค่าตำแหน่งของรูปทรงใน z-order. Shapes[0] คืนค่า shape ที่อยู่ด้านหลังสุดของ z-order, และ Shapes[Shapes.Count - 1] คืนค่า shape ที่อยู่ด้านหน้าสุดของ z-order. อ่านอย่างเดียว int.

**คืนค่า:**
int

### getConnectionSiteCount() {#getConnectionSiteCount--}
```
public abstract int getConnectionSiteCount()
```

คืนค่าจำนวน connection sites ของรูปทรง. อ่านอย่างเดียว int.

**คืนค่า:**
int

### getRotation() {#getRotation--}
```
public abstract float getRotation()
```

คืนค่าหรือกำหนดจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z. ค่าบวกบ่งบอกการหมุนตามเข็มนาฬิกา; ค่าลบบ่งบอกการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาตลอดจะถูกกำหนด (ไม่เป็น Float.NaN). ค่าที่กำหนดต้องถูกกำหนด (ไม่เป็น Float.NaN). คุณสามารถตั้งค่าเป็น undefined ให้กับ property ของ RawFrame ได้.

**คืนค่า:**
float

### setRotation(float value) {#setRotation-float-}
```
public abstract void setRotation(float value)
```

คืนค่าหรือกำหนดจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z. ค่าบวกบ่งบอกการหมุนตามเข็มนาฬิกา; ค่าลบบ่งบอกการหมุนทวนเข็มนาฬิกา. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาตลอดจะถูกกำหนด (ไม่เป็น Float.NaN). ค่าที่กำหนดต้องถูกกำหนด (ไม่เป็น Float.NaN). คุณสามารถตั้งค่าเป็น undefined ให้กับ property ของ RawFrame ได้.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getX() {#getX--}
```
public abstract float getX()
```

รับหรือกำหนดค่า x-coordinate ของมุมบนซ้ายของรูปทรง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาตลอดจะถูกกำหนดและไม่เป็น Float.NaN. ค่าที่กำหนดต้องกำหนดเช่นกัน; ให้กำหนด Float.NaN เพียงกับ property ของ RawFrame เท่านั้น.

**คืนค่า:**
float

### setX(float value) {#setX-float-}
```
public abstract void setX(float value)
```

รับหรือกำหนดค่า x-coordinate ของมุมบนซ้ายของรูปทรง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาตลอดจะถูกกำหนดและไม่เป็น Float.NaN. ค่าที่กำหนดต้องกำหนดเช่นกัน; ให้กำหนด Float.NaN เพียงกับ property ของ RawFrame เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getY() {#getY--}
```
public abstract float getY()
```

รับหรือกำหนดค่า y-coordinate ของมุมบนซ้ายของรูปทรง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาตลอดจะถูกกำหนดและไม่เป็น Float.NaN. ค่าที่กำหนดต้องกำหนดเช่นกัน; ให้กำหนด Float.NaN เพียงกับ property ของ RawFrame เท่านั้น.

**คืนค่า:**
float

### setY(float value) {#setY-float-}
```
public abstract void setY(float value)
```

รับหรือกำหนดค่า y-coordinate ของมุมบนซ้ายของรูปทรง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาตลอดจะถูกกำหนดและไม่เป็น Float.NaN. ค่าที่กำหนดต้องกำหนดเช่นกัน; ให้กำหนด Float.NaN เพียงกับ property ของ RawFrame เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getWidth() {#getWidth--}
```
public abstract float getWidth()
```

รับหรือกำหนดความกว้างของรูปทรง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาตลอดจะถูกกำหนดและไม่เป็น Float.NaN. ค่าที่กำหนดต้องกำหนดเช่นกัน; ให้กำหนด Float.NaN เพียงกับ property ของ RawFrame เท่านั้น.

**คืนค่า:**
float

### setWidth(float value) {#setWidth-float-}
```
public abstract void setWidth(float value)
```

รับหรือกำหนดความกว้างของรูปทรง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาตลอดจะถูกกำหนดและไม่เป็น Float.NaN. ค่าที่กำหนดต้องกำหนดเช่นกัน; ให้กำหนด Float.NaN เพียงกับ property ของ RawFrame เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

รับหรือกำหนดความสูงของรูปทรง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาตลอดจะถูกกำหนดและไม่เป็น Float.NaN. ค่าที่กำหนดต้องกำหนดเช่นกัน; ให้กำหนด Float.NaN เพียงกับ property ของ RawFrame เท่านั้น.

**คืนค่า:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

รับหรือกำหนดความสูงของรูปทรง, หน่วยเป็นจุด. อ่าน/เขียน float.

--------------------

ค่าที่คืนมาตลอดจะถูกกำหนดและไม่เป็น Float.NaN. ค่าที่กำหนดต้องกำหนดเช่นกัน; ให้กำหนด Float.NaN เพียงกับ property ของ RawFrame เท่านั้น.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getAlternativeText() {#getAlternativeText--}
```
public abstract String getAlternativeText()
```

คืนค่า หรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setAlternativeText(String value) {#setAlternativeText-java.lang.String-}
```
public abstract void setAlternativeText(String value)
```

คืนค่า หรือกำหนดข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternativeTextTitle() {#getAlternativeTextTitle--}
```
public abstract String getAlternativeTextTitle()
```

คืนค่า หรือกำหนดชื่อของข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setAlternativeTextTitle(String value) {#setAlternativeTextTitle-java.lang.String-}
```
public abstract void setAlternativeTextTitle(String value)
```

คืนค่า หรือกำหนดชื่อของข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public abstract String getName()
```

คืนค่า หรือกำหนดชื่อของรูปทรง. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

คืนค่า หรือกำหนดชื่อของรูปทรง. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### isDecorative() {#isDecorative--}
```
public abstract boolean isDecorative()
```

รับหรือกำหนดตัวเลือก 'Mark as decorative' แบบ boolean อ่าน/เขียน.

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

รับหรือกำหนดตัวเลือก 'Mark as decorative' แบบ boolean อ่าน/เขียน.

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
public abstract IBaseShapeLock getShapeLock()
```

คืนค่าการล็อกของรูปทรง. อ่านอย่างเดียว [IBaseShapeLock](../../com.aspose.slides/ibaseshapelock).

**คืนค่า:**
[IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)

### getUniqueId() {#getUniqueId--}
```
public abstract long getUniqueId()
```

คืนค่า identifier ภายในที่มีขอบเขตระดับการนำเสนอ เพื่อใช้โดย add-ins หรือโค้ดอื่น. เนื่องจากค่าอาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม จึงไม่ควรถือว่าเป็นคีย์ที่คงที่ตลอด. อ่านอย่างเดียว long. ดูเพิ่มเติม \#getOfficeInteropShapeId.getOfficeInteropShapeId.

**คืนค่า:**
long

### getOfficeInteropShapeId() {#getOfficeInteropShapeId--}
```
public abstract long getOfficeInteropShapeId()
```

คืนค่า identifier ที่มีขอบเขตระดับสไลด์และคงที่ตลอดอายุของรูปทรง เพื่อให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงจากที่ใดในเอกสารก็ได้อย่างเชื่อถือได้. อ่านอย่างเดียว long. ดูเพิ่มเติม \#getUniqueId.getUniqueId.

**คืนค่า:**
long

### isGrouped() {#isGrouped--}
```
public abstract boolean isGrouped()
```

กำหนดว่ารูปทรงเป็นกลุ่มหรือไม่. อ่านอย่างเดียว boolean.

--------------------

คุณลักษณะ \#getParentGroup.getParentGroup คืนค่าอ็อบเจกต์ GroupShape พาเรนท์ถ้ารูปทรงเป็นกลุ่ม.

**คืนค่า:**
boolean

### getBlackWhiteMode() {#getBlackWhiteMode--}
```
public abstract byte getBlackWhiteMode()
```

คุณสมบัติระบุว่ารูปทรงจะถูกเรนเดอร์อย่างไรในโหมดสีดำ-ขาว. อ่าน/เขียน [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**คืนค่า:**
byte

### setBlackWhiteMode(byte value) {#setBlackWhiteMode-byte-}
```
public abstract void setBlackWhiteMode(byte value)
```

คุณสมบัติระบุว่ารูปทรงจะถูกเรนเดอร์อย่างไรในโหมดสีดํา-ขาว. อ่าน/เขียน [BlackWhiteMode](../../com.aspose.slides/blackwhitemode).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

คืนค่าอ็อบเจกต์ GroupShape พาเรนท์ถ้ารูปทรงเป็นกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [IGroupShape](../../com.aspose.slides/igroupshape).

--------------------

คุณลักษณะ \#isGrouped.isGrouped กำหนดว่ารูปทรงเป็นกลุ่มหรือไม่.

**คืนค่า:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

บันทึกเนื้อหาของ Shape เป็นไฟล์ SVG.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | ตัวเลือกการสร้าง SVG |

### getBasePlaceholder() {#getBasePlaceholder--}
```
public abstract IShape getBasePlaceholder()
```

คืนค่า shape placeholder พื้นฐาน (shape จากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอดมาจาก).

--------------------

> ```
> // ดึงเอฟเฟ็กต์แอนิเมชันทั้งหมด (master/layout/slide) ของรูปทรง placeholder
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

จะคืนค่า null หากรูปทรงปัจจุบันไม่ได้สืบทอด.

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape)