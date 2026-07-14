---
title: IAutoShape
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง Java API
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
| [getTextFrame()](#getTextFrame--) | คืนค่าอ็อบเจ็ค TextFrame สำหรับ AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | กำหนดว่ารูปอัตโนมัตินี้ควรเติมด้วยพื้นหลังของสไลด์แทนการกำหนดโดยสไตล์หรือรูปแบบการเติมหรือไม่. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | กำหนดว่ารูปอัตโนมัตินี้ควรเติมด้วยพื้นหลังของสไลด์แทนการกำหนดโดยสไตล์หรือรูปแบบการเติมหรือไม่. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | เพิ่ม TextFrame ใหม่ให้กับรูปร่าง. |
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


คืนค่าอ็อบเจ็ค TextFrame สำหรับ AutoShape. อ่านอย่างเดียว [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


กำหนดว่ารูปอัตโนมัตินี้ควรเติมด้วยพื้นหลังของสไลด์แทนการกำหนดโดยสไตล์หรือรูปแบบการเติมหรือไม่. อ่าน/เขียน boolean.

**Returns:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


กำหนดว่ารูปอัตโนมัตินี้ควรเติมด้วยพื้นหลังของสไลด์แทนการกำหนดโดยสไตล์หรือรูปแบบการเติมหรือไม่. อ่าน/เขียน boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


เพิ่ม TextFrame ใหม่ให้กับรูปร่าง. หากรูปร่างมี TextFrame อยู่แล้วจะเปลี่ยนข้อความเท่านั้น.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Default text for a new TextFrame. |

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe) - ใหม่ [ITextFrame](../../com.aspose.slides/itextframe) อ็อบเจ็กต์.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


ระบุว่ารูปร่างเป็นกล่องข้อความหรือไม่.

--------------------

หากรูปร่างไม่ได้ระบุให้เป็นกล่องข้อความไม่ได้หมายความว่าจะไม่สามารถมีข้อความผูกต่อได้ กล่องข้อความเป็นเพียงรูปร่างที่มีคุณสมบัติเฉพาะเฉพาะ. 

**Returns:**
boolean