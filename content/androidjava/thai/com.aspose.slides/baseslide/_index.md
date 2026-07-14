---
title: BaseSlide
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงข้อมูลทั่วไปสำหรับสไลด์ประเภททั้งหมด.
type: docs
url: /th/com.aspose.slides/baseslide/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

แสดงข้อมูลทั่วไปสำหรับสไลด์ประเภททั้งหมด.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShapes()](#getShapes--) | คืนค่ารูปร่างของสไลด์หนึ่ง. |
| [getControls()](#getControls--) | คืนค่าชุดของคอนโทรล ActiveX บนสไลด์หนึ่ง. |
| [getName()](#getName--) | คืนค่า หรือ ตั้งค่าชื่อของสไลด์. |
| [setName(String value)](#setName-java.lang.String-) | คืนค่า หรือ ตั้งค่าชื่อของสไลด์. |
| [getSlideId()](#getSlideId--) | คืนค่า ID ของสไลด์. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวมรันที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าของรูปร่างที่ยอมรับทั้งหมด. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | รวมรันที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าของรูปร่างที่ยอมรับทั้งหมด. |
| [createThemeEffective()](#createThemeEffective--) | คืนค่า theme ที่ใช้งานได้สำหรับสไลด์นี้. |
| [getCustomData()](#getCustomData--) | คืนค่าข้อมูลที่กำหนดเองของสไลด์. |
| [getTimeline()](#getTimeline--) | คืนค่าออบเจ็กต์ animation timeline. |
| [getSlideShowTransition()](#getSlideShowTransition--) | คืนค่าออบเจ็กต์ Transition ซึ่งบรรจุข้อมูลเกี่ยวกับวิธีที่สไลด์ที่ระบุก้าวหน้าระหว่างการแสดงสไลด์โชว์. |
| [getBackground()](#getBackground--) | คืนค่าพื้นหลังของสไลด์. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึงลิงก์ไฮเปอร์ลิงก์ที่มีอยู่ได้อย่างง่ายดาย. |
| [getShowMasterShapes()](#getShowMasterShapes--) | ระบุว่ารูปร่างบนมาสเตอร์สไลด์จะต้องแสดงบนสไลด์หรือไม่. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | ระบุว่ารูปร่างบนมาสเตอร์สไลด์จะต้องแสดงบนสไลด์หรือไม่. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | ค้นหาการปรากฏครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | คืนค่าอินเทอร์เฟซ IPresentation. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

คืนค่ารูปร่างของสไลด์หนึ่ง. อ่านอย่างเดียว [IShapeCollection](../../com.aspose.slides/ishapecollection).

**คืนค่า:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)

### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

คืนค่าชุดของคอนโทรล ActiveX บนสไลด์หนึ่ง. อ่านอย่างเดียว [IControlCollection](../../com.aspose.slides/icontrolcollection).

**คืนค่า:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)

### getName() {#getName--}
```
public String getName()
```

คืนค่า หรือ ตั้งค่าชื่อของสไลด์. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

คืนค่า หรือ ตั้งค่าชื่อของสไลด์. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

คืนค่า ID ของสไลด์. อ่านอย่างเดียว long.

**คืนค่า:**
long

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่. ค่าที่ส่งคืนถูกคำนวณจากโครงสร้างและเนื้อหาคงที่ของสไลด์. สไลด์สองสไลด์เท่ากันหากรูปทรง, สไตล์, ข้อความ, การเคลื่อนไหวและการตั้งค่าอื่น ๆ เป็นต้นเท่ากัน. การเปรียบเทียบไม่พิจารณาค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่า วันที่ปัจจุบันใน Placeholder วันที่.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide ที่ต้องการเปรียบเทียบกับ IBaseSlide ปัจจุบัน. |

**คืนค่า:**
boolean - **true** หาก IBaseSlide ที่ระบุเท่ากับ IBaseSlide ปัจจุบัน; มิฉะนั้น **false** .

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

รวมรันที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าของรูปร่างที่ยอมรับทั้งหมด.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

รวมรันที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าของรูปร่างที่ยอมรับทั้งหมด.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

คืนค่า theme ที่ใช้งานได้สำหรับสไลด์นี้.

**คืนค่า:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)

### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

คืนค่าข้อมูลที่กำหนดเองของสไลด์. อ่านอย่างเดียว [ICustomData](../../com.aspose.slides/icustomdata).

**คืนค่า:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

คืนค่าออบเจ็กต์ animation timeline. อ่านอย่างเดียว [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**คืนค่า:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)

### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

คืนค่าออบเจ็กต์ Transition ซึ่งบรรจุข้อมูลเกี่ยวกับวิธีที่สไลด์ที่ระบุก้าวหน้าระหว่างการแสดงสไลด์โชว์. อ่านอย่างเดียว [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**คืนค่า:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)

### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

คืนค่าพื้นหลังของสไลด์. อ่านอย่างเดียว [IBackground](../../com.aspose.slides/ibackground).

**คืนค่า:**
[IBackground](../../com.aspose.slides/ibackground)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

ให้การเข้าถึงลิงก์ไฮเปอร์ลิงก์ที่มีอยู่ได้อย่างง่ายดาย. อ่านอย่างเดียว [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**คืนค่า:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

ระบุว่ารูปร่างบนมาสเตอร์สไลด์จะต้องแสดงบนสไลด์หรือไม่. สำหรับมาสเตอร์สไลด์เองคุณสมบัตินี้จะคืนค่า false เสมอ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

ระบุว่ารูปร่างบนมาสเตอร์สไลด์จะต้องแสดงบนสไลด์หรือไม่. สำหรับมาสเตอร์สไลด์เองคุณสมบัตินี้จะคืนค่า false เสมอ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

ค้นหาการปรากฏครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| altText | java.lang.String | ข้อความแทนที่. |

**คืนค่า:**
[IShape](../../com.aspose.slides/ishape) - Shape object หรือ null.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าออบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่าอินเทอร์เฟซ IPresentation. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนค่าฐานสไลด์. อ่านอย่างเดียว [IBaseSlide](../../com.aspose.slides/ibaseslide).

**คืนค่า:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)