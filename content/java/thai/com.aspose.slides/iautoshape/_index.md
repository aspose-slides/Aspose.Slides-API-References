---
title: IAutoShape
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของ AutoShape.
type: docs
url: /th/com.aspose.slides/iautoshape/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Represents an AutoShape.  
## Methods

| Method | Description |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | คืนค่า lock ของ AutoShape. |
| [getTextFrame()](#getTextFrame--) | คืนค่าอ็อบเจ็กต์ TextFrame สำหรับ AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | กำหนดว่ารูปร่าง autoshape นี้ควรจะถูกเติมด้วยพื้นหลังของสไลด์แทนที่จะกำหนดโดยสไตล์หรือรูปแบบการเติม. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | กำหนดว่ารูปร่าง autoshape นี้ควรจะถูกเติมด้วยพื้นหลังของสไลด์แทนที่จะกำหนดโดยสไตล์หรือรูปแบบการเติม. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | เพิ่ม TextFrame ใหม่ไปยังรูปร่าง. |
| [isTextBox()](#isTextBox--) | ระบุว่ารูปร่างเป็นกล่องข้อความหรือไม่. |

### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```

คืนค่า lock ของ AutoShape. อ่านอย่างเดียว [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Returns:**  
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)

### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

คืนค่าอ็อบเจ็กต์ TextFrame สำหรับ AutoShape. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```

กำหนดว่ารูปร่าง autoshape นี้ควรจะถูกเติมด้วยพื้นหลังของสไลด์แทนที่จะกำหนดโดยสไตล์หรือรูปแบบการเติม. บูลีน อ่าน/เขียน.

**Returns:**  
boolean

### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

กำหนดว่ารูปร่าง autoshape นี้ควรจะถูกเติมด้วยพื้นหลังของสไลด์แทนที่จะกำหนดโดยสไตล์หรือรูปแบบการเติม. บูลีน อ่าน/เขียน.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```

เพิ่ม TextFrame ใหม่ไปยังรูปร่าง. หากรูปร่างมี TextFrame อยู่แล้วจะเปลี่ยนข้อความเท่านั้น.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | ข้อความเริ่มต้นสำหรับ TextFrame ใหม่. |

**Returns:**  
[ITextFrame](../../com.aspose.slides/itextframe) - วัตถุ [ITextFrame](../../com.aspose.slides/itextframe) ใหม่.

### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```

ระบุว่ารูปร่างเป็นกล่องข้อความหรือไม่.

--------------------

หากรูปร่างไม่ได้ระบุว่าเป็นกล่องข้อความไม่ได้หมายความว่าไม่สามารถมีข้อความแนบอยู่ได้. กล่องข้อความเป็นเพียงรูปร่างประเภทพิเศษที่มีคุณสมบัติเฉพาะ.

**Returns:**  
boolean