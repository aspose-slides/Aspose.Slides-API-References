---
title: IBaseSlide
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นข้อมูลส่วนกลางที่ใช้ร่วมกันสำหรับทุกประเภทของสไลด์.
type: docs
url: /th/com.aspose.slides/ibaseslide/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

เป็นข้อมูลส่วนกลางที่ใช้ร่วมกันสำหรับทุกประเภทของสไลด์.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShapes()](#getShapes--) | ส่งคืนรูปทรงของสไลด์. |
| [getControls()](#getControls--) | ส่งคืนคอลเลกชันของควบคุม ActiveX บนสไลด์. |
| [getName()](#getName--) | ส่งคืนหรือกำหนดชื่อของสไลด์. |
| [setName(String value)](#setName-java.lang.String-) | ส่งคืนหรือกำหนดชื่อของสไลด์. |
| [getSlideId()](#getSlideId--) | ส่งคืน ID ของสไลด์. |
| [getCustomData()](#getCustomData--) | ส่งคืนข้อมูลส่วนกำหนดของสไลด์. |
| [getTimeline()](#getTimeline--) | ส่งคืนอ็อบเจ็กต์ไทม์ไลน์ของแอนิเมชัน. |
| [getSlideShowTransition()](#getSlideShowTransition--) | ส่งคืนอ็อบเจ็กต์ TransitionEx ซึ่งประกอบด้วยข้อมูลเกี่ยวกับวิธีที่สไลด์ที่ระบุดำเนินต่อไประหว่างการแสดงสไลด์. |
| [getBackground()](#getBackground--) | ส่งคืนพื้นหลังของสไลด์. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึงไฮเปอร์ลิงก์ที่ประกอบอยู่ได้อย่างง่ายดาย. |
| [getShowMasterShapes()](#getShowMasterShapes--) | ระบุว่ารูปร่างบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | ระบุว่ารูปร่างบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | ค้นหาการปรากฏครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวมรันที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมดของรูปร่างที่ยอมรับได้ทั้งหมด. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | กำหนดว่าตัวอย่างของ IBaseSlide สองตัวเท่ากันหรือไม่. |

### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


ส่งคืนรูปทรงของสไลด์ อ่านอย่างเดียว [IShapeCollection](../../com.aspose.slides/ishapecollection).

**ส่งคืน:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)

### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```


ส่งคืนคอลเลกชันของควบคุม ActiveX บนสไลด์ อ่านอย่างเดียว [IControlCollection](../../com.aspose.slides/icontrolcollection).

**ส่งคืน:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)

### getName() {#getName--}
```
public abstract String getName()
```


ส่งคืนหรือกำหนดชื่อของสไลด์ อ่าน/เขียน String.

**ส่งคืน:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


ส่งคืนหรือกำหนดชื่อของสไลด์ อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```


ส่งคืน ID ของสไลด์ อ่านอย่างเดียว long.

**ส่งคืน:**
long

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


ส่งคืนข้อมูลส่วนกำหนดของสไลด์ อ่านอย่างเดียว [ICustomData](../../com.aspose.slides/icustomdata).

**ส่งคืน:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```


ส่งคืนอ็อบเจ็กต์ไทม์ไลน์ของแอนิเมชัน อ่านอย่างเดียว [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**ส่งคืน:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)

### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```


ส่งคืนอ็อบเจ็กต์ TransitionEx ซึ่งประกอบด้วยข้อมูลเกี่ยวกับวิธีที่สไลด์ที่ระบุดำเนินต่อไประหว่างการแสดงสไลด์ อ่านอย่างเดียว [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**ส่งคืน:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)

### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```


ส่งคืนพื้นหลังของสไลด์ อ่านอย่างเดียว [IBackground](../../com.aspose.slides/ibackground).

**ส่งคืน:**
[IBackground](../../com.aspose.slides/ibackground)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


ให้การเข้าถึงไฮเปอร์ลิงก์ที่ประกอบอยู่ได้อย่างง่ายดาย อ่านอย่างเดียว [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**ส่งคืน:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


ระบุว่ารูปร่างบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์แม่เองคุณสมบัตินี้จะคืนค่า false เสมอ อ่าน/เขียน boolean.

**ส่งคืน:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


ระบุว่ารูปร่างบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์แม่เองคุณสมบัตินี้จะคืนค่า false เสมอ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```


ค้นหาการปรากฏครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| altText | java.lang.String | ข้อความแทนที่. |

**ส่งคืน:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx object or null.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


รวมรันที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมดของรูปร่างที่ยอมรับได้ทั้งหมด.

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```


กำหนดว่าตัวอย่างของ IBaseSlide สองตัวเท่ากันหรือไม่ ค่าที่ส่งกลับจะคำนวณตามโครงสร้างและเนื้อหาคงที่ของสไลด์ สไลด์สองสไลด์จะเท่ากันหากรูปทรง, สไตล์, ข้อความ, แอนิเมชันและการตั้งค่าอื่น ๆ ฯลฯ เท่ากัน การเปรียบเทียบจะไม่พิจารณาค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาไดนามิก เช่น ค่าของวันที่ปัจจุบันในตำแหน่งตัวแปรวันที่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide ที่จะเปรียบเทียบกับ IBaseSlide ปัจจุบัน. |

**ส่งคืน:**
boolean - **true** หาก IBaseSlide ที่ระบุเท่ากับ IBaseSlide ปัจจุบัน; มิฉะนั้น, **false**.