---
title: BaseSlide
second_title: Aspose.Slides สำหรับ Java: เอกสารอ้างอิง API
description: เป็นข้อมูลทั่วไปสำหรับทุกประเภทสไลด์.
type: docs
url: /th/com.aspose.slides/baseslide/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

เป็นข้อมูลทั่วไปสำหรับทุกประเภทสไลด์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShapes()](#getShapes--) | ส่งคืนรูปร่างของสไลด์. |
| [getControls()](#getControls--) | ส่งคืนคอลเลกชันของคอนโทรล ActiveX บนสไลด์. |
| [getName()](#getName--) | ส่งคืนหรือกำหนดชื่อของสไลด์. |
| [setName(String value)](#setName-java.lang.String-) | ส่งคืนหรือกำหนดชื่อของสไลด์. |
| [getSlideId()](#getSlideId--) | ส่งคืน ID ของสไลด์. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | รวมช่วงข้อความที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมดในรูปร่างที่ยอมรับได้ทั้งหมด. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | รวมช่วงข้อความที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมดในรูปร่างที่ยอมรับได้ทั้งหมด. |
| [createThemeEffective()](#createThemeEffective--) | ส่งคืนธีมที่ใช้ได้สำหรับสไลด์นี้. |
| [getCustomData()](#getCustomData--) | ส่งคืนข้อมูลกำหนดเองของสไลด์. |
| [getTimeline()](#getTimeline--) | ส่งคืนอ็อบเจ็กต์ไทม์ไลน์การเคลื่อนไหว. |
| [getSlideShowTransition()](#getSlideShowTransition--) | ส่งคืนอ็อบเจ็กต์ Transition ซึ่งมีข้อมูลว่าการแสดงสไลด์ที่ระบุดำเนินการอย่างไรในระหว่างการนำเสนอ. |
| [getBackground()](#getBackground--) | ส่งคืนพื้นหลังของสไลด์. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุอยู่ได้อย่างง่ายดาย. |
| [getShowMasterShapes()](#getShowMasterShapes--) | ระบุว่ารูปร่างบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | ระบุว่ารูปร่างบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | ค้นหาการปรากฏครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | ส่งคืนอินเทอร์เฟซ IPresentation. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

ส่งคืนรูปร่างของสไลด์ อ่านอย่างเดียว [IShapeCollection](../../com.aspose.slides/ishapecollection).

**ส่งคืน:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

ส่งคืนคอลเลกชันของคอนโทรล ActiveX บนสไลด์ อ่านอย่างเดียว [IControlCollection](../../com.aspose.slides/icontrolcollection).

**ส่งคืน:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

ส่งคืนหรือกำหนดชื่อของสไลด์ อ่าน/เขียน String.

**ส่งคืน:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

ส่งคืนหรือกำหนดชื่อของสไลด์ อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

ส่งคืน ID ของสไลด์ อ่านอย่างเดียว long.

**ส่งคืน:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

กำหนดว่าตัวอย่าง IBaseSlide สองตัวเท่ากันหรือไม่ ค่าที่ส่งกลับจะคำนวณจากโครงสร้างและเนื้อหาคงที่ของสไลด์ สองสไลด์จะเท่ากันถ้ารูปร่าง, สไตล์, ข้อความ, การเคลื่อนไหวและการตั้งค่าอื่น ๆ ฯลฯ เท่ากัน การเปรียบเทียบจะไม่พิจารณาค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าระยะวันที่ในตัวจับตำแหน่งวันที่.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide ที่จะเปรียบเทียบกับ IBaseSlide ปัจจุบัน. |

**ส่งคืน:**
boolean -  **true**  หาก IBaseSlide ที่ระบุเท่ากับ IBaseSlide ปัจจุบัน; มิฉะนั้น,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

รวมช่วงข้อความที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมดในรูปร่างที่ยอมรับได้ทั้งหมด.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

รวมช่วงข้อความที่มีการจัดรูปแบบเดียวกันในย่อหน้าทั้งหมดในรูปร่างที่ยอมรับได้ทั้งหมด.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

ส่งคืนธีมที่ใช้ได้สำหรับสไลด์นี้.

**ส่งคืน:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

ส่งคืนข้อมูลกำหนดเองของสไลด์ อ่านอย่างเดียว [ICustomData](../../com.aspose.slides/icustomdata).

**ส่งคืน:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

ส่งคืนอ็อบเจ็กต์ไทม์ไลน์การเคลื่อนไหว อ่านอย่างเดียว [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**ส่งคืน:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

ส่งคืนอ็อบเจ็กต์ Transition ซึ่งมีข้อมูลว่าการแสดงสไลด์ที่ระบุดำเนินการอย่างไรในระหว่างการนำเสนอ อ่านอย่างเดียว [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**ส่งคืน:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

ส่งคืนพื้นหลังของสไลด์ อ่านอย่างเดียว [IBackground](../../com.aspose.slides/ibackground).

**ส่งคืน:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุอยู่ได้อย่างง่ายดาย อ่านอย่างเดียว [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**ส่งคืน:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

ระบุว่ารูปร่างบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์แม่เองคุณสมบัตินี้จะส่งค่ากลับเป็น false เสมอ อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

ระบุว่ารูปร่างบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์แม่เองคุณสมบัตินี้จะส่งค่ากลับเป็น false เสมอ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

ค้นหาการปรากฏครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| altText | java.lang.String | ข้อความแทนที่. |

**ส่งคืน:**
[IShape](../../com.aspose.slides/ishape) - Shape object หรือ null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจ็กต์ Parent_Immediate อ่านอย่างเดียว IDOMObject.

**ส่งคืน:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ส่งคืนอินเทอร์เฟซ IPresentation อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**ส่งคืน:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

ส่งคืนสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../../com.aspose.slides/ibaseslide).

**ส่งคืน:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)