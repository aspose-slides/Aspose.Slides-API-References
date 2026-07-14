---
title: PortionFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Android ผ่าน Java
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความ
type: docs
url: /th/com.aspose.slides/portionformat/
---
**สืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

คลาสนี้มีคุณสมบัติการจัดรูปแบบส่วนข้อความ. ไม่เหมือนกับ [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //สร้างออบเจ็กต์ Presentation ที่เป็นตัวแทนไฟล์พรีเซนเทชัน
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides ใช้ตัวระบุพิเศษเหล่านี้ (คล้ายกับที่ใช้ใน PowerPoint):
>      // +mn-lt - ฟอนต์ลาตินของบอดี้ (ฟอนต์ลาตินรอง)
>      // +mj-lt -ฟอนต์ลาตินของหัวเรื่อง (ฟอนต์ลาตินหลัก)
>      // +mn-ea - ฟอนต์เอเชียตะวันออกของบอดี้ (ฟอนต์เอเชียตะวันออกรอง)
>      // +mj-ea - ฟอนต์เอเชียตะวันออกของบอดี้ (ฟอนต์เอเชียตะวันออกรอง)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนข้อความที่กำหนดสำหรับส่วนเฉพาะ. ซึ่งหมายความว่าไม่มีการสืบทอดเมื่อดึงค่า ดังนั้นในส่วนใหญ่คุณจะได้รับค่าที่หมายถึง “ไม่กำหนด”.

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอด คุณจำเป็นต้องใช้เมธอด [getEffective](../../com.aspose.slides/portionformat\#getEffective) ซึ่งคืนค่าเป็นอินสแตนซ์ของ [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [PortionFormat](../../com.aspose.slides/portionformat). |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | ส่งคืนหรือกำหนดตัวระบุของบุ๊กมาร์ค. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | ส่งคืนหรือกำหนดตัวระบุของบุ๊กมาร์ค. |
| [getSmartTagClean()](#getSmartTagClean--) | กำหนดว่าควรทำความสะอาด Smart Tag หรือไม่. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | กำหนดว่าควรทำความสะอาด Smart Tag หรือไม่. |
| [getHyperlinkClick()](#getHyperlinkClick--) | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์. |
| [getHyperlinkManager()](#getHyperlinkManager--) | ตัวจัดการไฮเปอร์ลิงก์. |
| [getEffective()](#getEffective--) | ดึงข้อมูลการจัดรูปแบบส่วนที่มีผลรวมกับการสืบทอดที่ใช้. |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

ส่งคืนหรือกำหนดตัวระบุของบุ๊กมาร์ค. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

ส่งคืนหรือกำหนดตัวระบุของบุ๊กมาร์ค. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

กำหนดว่าควรทำความสะอาด Smart Tag หรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

กำหนดว่าควรทำความสะอาด Smart Tag หรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**คืนค่า:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

ส่งฟรีหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**คืนค่า:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

ส่งคืนหรือกำหนดไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

ตัวจัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**คืนค่า:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

ดึงข้อมูลการจัดรูปแบบส่วนที่มีผลรวมกับการสืบทอดที่ใช้.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).