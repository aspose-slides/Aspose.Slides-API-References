---
title: PortionFormat
second_title: Aspose.Slides สำหรับ Java เอกสารอ้างอิง API
description: คลาสนี้ประกอบด้วยคุณสมบัติการจัดรูปแบบส่วนข้อความ.
type: docs
url: /th/com.aspose.slides/portionformat/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

คลาสนี้ประกอบด้วยคุณสมบัติการจัดรูปแบบส่วนข้อความ. แตกต่างจาก [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata), คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //สร้างอ็อบเจ็กต์ Presentation ที่เป็นตัวแทนไฟล์งานนำเสนอ
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides ใช้ตัวระบุพิเศษเหล่านี้ (คล้ายกับที่ใช้ใน PowerPoint):
>      // +mn-lt - Body Font Latin (Minor Latin Font)
>      // +mj-lt -Heading Font Latin (Major Latin Font)
>      // +mn-ea - Body Font East Asian (Minor East Asian Font)
>      // +mj-ea - Body Font East Asian (Minor East Asian Font)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติการจัดรูปแบบส่วนข้อความที่กำหนดสำหรับส่วนที่เฉพาะเจาะจง. นี่หมายความว่าไม่มีการสืบทอดใด ๆ ถูกใช้เมื่อดึงค่าจึงในกรณีส่วนใหญ่คุณจะได้รับค่าที่มีความหมายว่า "undefined".

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงที่สืบทอดคุณต้องใช้เมธอด [getEffective](../../com.aspose.slides/portionformat\#getEffective) ซึ่งจะคืนค่าอินสแตนซ์ของ [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Initializes a new instance of [PortionFormat](../../com.aspose.slides/portionformat) class. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Returns or sets bookmark identifier. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Returns or sets bookmark identifier. |
| [getSmartTagClean()](#getSmartTagClean--) | Determines whether the smart tag should be cleaned. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Determines whether the smart tag should be cleaned. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Returns or sets the hyperlink defined for mouse click. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Returns or sets the hyperlink defined for mouse click. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Returns or sets the hyperlink defined for mouse over. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Returns or sets the hyperlink defined for mouse over. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Hyperlinks manager. |
| [getEffective()](#getEffective--) | Gets effective portion formatting data with the inheritance applied. |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

คืนค่าหรือกำหนดตัวระบุ bookmark. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

คืนค่าหรือกำหนดตัวระบุ bookmark. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

กำหนดว่า smart tag ควรถูกทำความสะอาดหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน boolean .

**คืนค่า:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

กำหนดว่า smart tag ควรถูกทำความสะอาดหรือไม่. ไม่ได้ใช้การสืบทอด. อ่าน/เขียน boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

คืนค่า หรือ กำหนด hyperlink ที่กำหนดสำหรับคลิกเม้าส์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**คืนค่า:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

คืนค่า หรือ กำหนด hyperlink ที่กำหนดสำหรับคลิกเม้าส์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

คืนค่า หรือ กำหนด hyperlink ที่กำหนดสำหรับเม้าส์โอเวอร์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**คืนค่า:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

คืนค่า หรือ กำหนด hyperlink ที่กำหนดสำหรับเม้าส์โอเวอร์. อ่าน/เขียน [IHyperlink](../../com.aspose.slides/ihyperlink).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```

Hyperlinks manager. อ่านอย่างเดียว [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**คืนค่า:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)

### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```

ดึงข้อมูลการจัดรูปแบบส่วนที่มีผลรวมการสืบทอด.

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