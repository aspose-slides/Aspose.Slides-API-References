---
title: IBaseSlide
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แทนข้อมูลทั่วไปสำหรับประเภทสไลด์ทั้งหมด.
type: docs
url: /th/com.aspose.slides/ibaseslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

แทนข้อมูลทั่วไปสำหรับประเภทสไลด์ทั้งหมด.
## Methods

| Method | Description |
| --- | --- |
| [getShapes()](#getShapes--) | คืนค่า shapes ของสไลด์. |
| [getControls()](#getControls--) | คืนค่า collection ของ ActiveX controls บนสไลด์. |
| [getName()](#getName--) | คืนค่าหรือกำหนดชื่อของสไลด์. |
| [setName(String value)](#setName-java.lang.String-) | คืนค่าหรือกำหนดชื่อของสไลด์. |
| [getSlideId()](#getSlideId--) | คืนค่า ID ของสไลด์. |
| [getCustomData()](#getCustomData--) | คืนค่าข้อมูลกำหนดเองของสไลด์. |
| [getTimeline()](#getTimeline--) | คืนค่า animation timeline object. |
| [getSlideShowTransition()](#getSlideShowTransition--) | คืนค่า TransitionEx object ที่มีข้อมูลเกี่ยวกับวิธีที่สไลด์ที่ระบุดำเนินการต่อในการแสดงสไลด์. |
| [getBackground()](#getBackground--) | คืนค่าพื้นหลังของสไลด์. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึง hyperlinks ที่อยู่ภายในอย่างง่ายดาย. |
| [getShowMasterShapes()](#getShowMasterShapes--) | ระบุว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | ระบุว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | ค้นหาการปรากฏแรกของ shape ที่มีข้อความแทนที่ระบุ. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวม runs ที่มีรูปแบบเดียวกันในทุก paragraph ในทุก shape ที่ยอมรับ. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


คืนค่า shapes ของสไลด์. อ่านอย่างเดียว [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Returns:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```


คืนค่า collection ของ ActiveX controls บนสไลด์. อ่านอย่างเดียว [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Returns:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```


คืนค่าหรือกำหนดชื่อของสไลด์. อ่าน/เขียน String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


คืนค่าหรือกำหนดชื่อของสไลด์. อ่าน/เขียน String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```


คืนค่า ID ของสไลด์. อ่านอย่างเดียว long.

**Returns:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


คืนค่าข้อมูลกำหนดเองของสไลด์. อ่านอย่างเดียว [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```


คืนค่า animation timeline object. อ่านอย่างเดียว [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Returns:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```


คืนค่า TransitionEx object ที่มีข้อมูลเกี่ยวกับวิธีที่สไลด์ที่ระบุดำเนินการต่อในการแสดงสไลด์. อ่านอย่างเดียว [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Returns:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```


คืนค่าพื้นหลังของสไลด์. อ่านอย่างเดียว [IBackground](../../com.aspose.slides/ibackground).

**Returns:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


ให้การเข้าถึง hyperlinks ที่อยู่ภายในอย่างง่ายดาย. อ่านอย่างเดียว [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returns:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


ระบุว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. สำหรับ master slide เองคุณสมบัตินี้จะคืนค่า false เสมอ. อ่าน/เขียน boolean.

**Returns:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


ระบุว่ารูปร่างบน master slide ควรแสดงบนสไลด์หรือไม่. สำหรับ master slide เองคุณสมบัตินี้จะคืนค่า false เสมอ. อ่าน/เขียน boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```


ค้นหาการปรากฏแรกของ shape ที่มีข้อความแทนที่ระบุ.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| altText | java.lang.String | Alternative text. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx object or null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


รวม runs ที่มีรูปแบบเดียวกันในทุก paragraph ในทุก shape ที่ยอมรับ.

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```


กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่. ค่าที่คืนคำนวณจากโครงสร้างและเนื้อหาคงที่ของสไลด์. สไลด์สองสไลด์เท่ากันหาก shapes, styles, texts, animation และการตั้งค่าอื่น ๆ เป็นต้นทั้งหมดเท่ากัน. การเปรียบเทียบไม่ได้คำนึงถึงค่าตัวระบุเฉพาะ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าจาก Date Placeholder ปัจจุบัน.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | The IBaseSlide to compare with the current IBaseSlide. |

**Returns:**
boolean - **true** if the specified IBaseSlide is equal to the current IBaseSlide; otherwise, **false**.