---
title: ParagraphFormat
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: คลาสนี้มีคุณสมบัติการจัดรูปแบบย่อหน้า.
type: docs
url: /th/com.aspose.slides/paragraphformat/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่ใช้งานทั้งหมด:**  
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)  
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

คลาสนี้มีคุณสมบัติการจัดรูปแบบย่อหน้า ต่างจาก [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้

--------------------

คลาสนี้ใช้เพื่อดึงและจัดการคุณสมบัติการจัดรูปแบบย่อหน้าที่กำหนดสำหรับย่อหน้าเฉพาะ ซึ่งหมายความว่าไม่มีการสืบทอดใด ๆ ถูกนำมาใช้เมื่อดึงค่าจึงในส่วนใหญ่คุณจะได้รับค่า “ไม่กำหนด”

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงการสืบทอด คุณต้องใช้เมธอด [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) ซึ่งจะคืนค่าอินสแตนซ์ของ [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [ParagraphFormat](../../com.aspose.slides/paragraphformat) |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBullet()](#getBullet--) | ส่งคืนรูปแบบหัวข้อของย่อหน้า |
| [getDepth()](#getDepth--) | ส่งคืนหรือกำหนดความลึกของย่อหน้า |
| [setDepth(short value)](#setDepth-short-) | ส่งคืนหรือกำหนดความลึกของย่อหน้า |
| [getAlignment()](#getAlignment--) | ส่งคืนหรือกำหนดการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด |
| [setAlignment(int value)](#setAlignment-int-) | ส่งคืนหรือกำหนดการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด |
| [getSpaceWithin()](#getSpaceWithin--) | ส่งคืนหรือกำหนดระยะห่างระหว่างเส้นฐานในย่อหน้า |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | ส่งคืนหรือกำหนดระยะห่างระหว่างเส้นฐานในย่อหน้า |
| [getSpaceBefore()](#getSpaceBefore--) | ส่งคืนหรือกำหนดระยะห่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | ส่งคืนหรือกำหนดระยะห่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด |
| [getSpaceAfter()](#getSpaceAfter--) | ส่งคืนหรือกำหนดระยะห่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | ส่งคืนหรือกำหนดระยะห่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | ตรวจสอบว่าการตัดบรรทัดแบบเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่ |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | ตรวจสอบว่าการตัดบรรทัดแบบเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่ |
| [getRightToLeft()](#getRightToLeft--) | ตรวจสอบว่ามีการเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่ |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | ตรวจสอบว่ามีการเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่ |
| [getLatinLineBreak()](#getLatinLineBreak--) | ตรวจสอบว่าการตัดบรรทัดแบบละตินถูกใช้ในย่อหน้าหรือไม่ |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | ตรวจสอบว่าการตัดบรรทัดแบบละตินถูกใช้ในย่อหน้าหรือไม่ |
| [getHangingPunctuation()](#getHangingPunctuation--) | ตรวจสอบว่ามีการใช้การเว้นเครื่องหมายวรรคตอนแบบห้อยในย่อหน้าหรือไม่ |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | ตรวจสอบว่ามีการใช้การเว้นเครื่องหมายวรรคตอนแบบห้อยในย่อหน้าหรือไม่ |
| [getMarginLeft()](#getMarginLeft--) | ส่งคืนหรือกำหนดระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด |
| [setMarginLeft(float value)](#setMarginLeft-float-) | ส่งคืนหรือกำหนดระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด |
| [getMarginRight()](#getMarginRight--) | ส่งคืนหรือกำหนดระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด |
| [setMarginRight(float value)](#setMarginRight-float-) | ส่งคืนหรือกำหนดระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด |
| [getIndent()](#getIndent--) | ส่งคืนหรือกำหนดการย่อหน้าแรก/การย่อห้อยของย่อหน้าโดยไม่มีการสืบทอด |
| [setIndent(float value)](#setIndent-float-) | ส่งคืนหรือกำหนดการย่อหน้าแรก/การย่อห้อยของย่อหน้าโดยไม่มีการสืบทอด |
| [getDefaultTabSize()](#getDefaultTabSize--) | ส่งคืนหรือกำหนดขนาดแท็บเริ่มต้นโดยไม่มีการสืบทอด |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | ส่งคืนหรือกำหนดขนาดแท็บเริ่มต้นโดยไม่มีการสืบทอด |
| [getTabs()](#getTabs--) | ส่งคืนแท็บของย่อหน้า |
| [getFontAlignment()](#getFontAlignment--) | ส่งคืนหรือกำหนดการจัดแนวฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด |
| [setFontAlignment(int value)](#setFontAlignment-int-) | ส่งคืนหรือกำหนดการจัดแนวฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | ส่งคืนรูปแบบส่วนเริ่มต้นของย่อหน้า |
| [getEffective()](#getEffective--) | ดึงข้อมูลการจัดรูปแบบย่อหน้าที่มีผลรวมกับการสืบทอด |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```


เริ่มต้นอินสแตนซ์ใหม่ของคลาส [ParagraphFormat](../../com.aspose.slides/paragraphformat)

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```


ส่งคืนรูปแบบหัวข้อของย่อหน้า อ่านอย่างเดียว [IBulletFormat](../../com.aspose.slides/ibulletformat)

**ผลลัพธ์:**  
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```


ส่งคืนหรือกำหนดความลึกของย่อหน้า ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด อ่าน/เขียน  short .

**ผลลัพธ์:**  
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```


ส่งคืนหรือกำหนดความลึกของย่อหน้า ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด อ่าน/เขียน  short .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


ส่งคืนหรือกำหนดการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน [TextAlignment](../../com.aspose.slides/textalignment)

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // สร้างออบเจ็กต์ Presentation ที่แสดงไฟล์ PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // เข้าถึงสไลด์แรก
>      ISlide slide = pres.getSlides().get_Item(0);
>      // เข้าถึง placeholder ที่หนึ่งและที่สองในสไลด์และแปลงชนิดเป็น AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // เปลี่ยนข้อความใน placeholder ทั้งสอง
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // ดึงย่อหน้าแรกของ placeholder
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // จัดแนวย่อข้อความให้ศูนย์กลาง
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //บันทึกพรีเซนเทชันเป็นไฟล์ PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ผลลัพธ์:**  
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


ส่งคืนหรือกำหนดการจัดแนวข้อความในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน [TextAlignment](../../com.aspose.slides/textalignment)

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // สร้างออบเจ็กต์ Presentation ที่แสดงไฟล์ PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // เข้าถึงสไลด์แรก
>      ISlide slide = pres.getSlides().get_Item(0);
>      // เข้าถึง placeholder ที่หนึ่งและที่สองในสไลด์และแปลงชนิดเป็น AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // เปลี่ยนข้อความใน placeholder ทั้งสอง
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // ดึงย่อหน้าแรกของ placeholder
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // จัดแนวย่อข้อความให้ศูนย์กลาง
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //บันทึกพรีเซนเทชันเป็นไฟล์ PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```


ส่งคืนหรือกำหนดระยะห่างระหว่างเส้นฐานในย่อหน้า ค่าเป็นบวกหมายถึงเปอร์เซ็นต์ ค่าเป็นลบหมายถึงขนาดเป็นพอยต์ ไม่ได้ใช้การสืบทอด อ่าน/เขียน  float .

**ผลลัพธ์:**  
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```


ส่งคืนหรือกำหนดระยะห่างระหว่างเส้นฐานในย่อหน้า ค่าเป็นบวกหมายถึงเปอร์เซ็นต์ ค่าเป็นลบหมายถึงขนาดเป็นพอยต์ ไม่ได้ใช้การสืบทอด อ่าน/เขียน  float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```


ส่งคืนหรือกำหนดระยะห่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ต้องการให้เป็นช่องว่าง ค่าเป็นลบระบุขนาดของช่องว่างเป็นพอยต์ อ่าน/เขียน  float .

**ผลลัพธ์:**  
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```


ส่งคืนหรือกำหนดระยะห่างก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ต้องการให้เป็นช่องว่าง ค่าเป็นลบระบุขนาดของช่องว่างเป็นพอยต์ อ่าน/เขียน  float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```


ส่งคืนหรือกำหนดระยะห่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ต้องการให้เป็นช่องว่าง ค่าเป็นลบระบุขนาดของช่องว่างเป็นพอยต์ อ่าน/เขียน  float .

**ผลลัพธ์:**  
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```


ส่งคืนหรือกำหนดระยะห่างหลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ต้องการให้เป็นช่องว่าง ค่าเป็นลบระบุขนาดของช่องว่างเป็นพอยต์ อ่าน/เขียน  float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```


ตรวจสอบว่าการตัดบรรทัดแบบเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool)

**ผลลัพธ์:**  
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```


ตรวจสอบว่าการตัดบรรทัดแบบเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool)

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```


ตรวจสอบว่ามีการเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool)

**ผลลัพธ์:**  
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```


ตรวจสอบว่ามีการเขียนจากขวาไปซ้ายในย่อหน้าหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool)

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```


ตรวจสอบว่าการตัดบรรทัดแบบละตินถูกใช้ในย่อหน้าหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool)

**ผลลัพธ์:**  
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```


ตรวจสอบว่าการตัดบรรทัดแบบละตินถูกใช้ในย่อหน้าหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool)

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```


ตรวจสอบว่าการเว้นเครื่องหมายวรรคตอนแบบห้อยถูกใช้ในย่อหน้าหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool)

**ผลลัพธ์:**  
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```


ตรวจสอบว่าการเว้นเครื่องหมายวรรคตอนแบบห้อยถูกใช้ในย่อหน้าหรือไม่ ไม่ได้ใช้การสืบทอด อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool)

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```


ส่งคืนหรือกำหนดระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน  float .

**ผลลัพธ์:**  
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```


ส่งคืนหรือกำหนดระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน  float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```


ส่งคืนหรือกำหนดระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน  float .

**ผลลัพธ์:**  
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```


ส่งคืนหรือกำหนดระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน  float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```


ส่งคืนหรือกำหนดการย่อหน้าแรก/การย่อห้อยของย่อหน้าโดยไม่มีการสืบทอด การย่อห้อยสามารถกำหนดด้วยค่าลบอ่าน/เขียน  float .

**ผลลัพธ์:**  
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```


ส่งคืนหรือกำหนดการย่อหน้าแรก/การย่อห้อยของย่อหน้าโดยไม่มีการสืบทอด การย่อห้อยสามารถกำหนดด้วยค่าลบอ่าน/เขียน  float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```


ส่งคืนหรือกำหนดขนาดแท็บเริ่มต้นโดยไม่มีการสืบทอด อ่าน/เขียน  float .

**ผลลัพธ์:**  
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```


ส่งคืนหรือกำหนดขนาดแท็บเริ่มต้นโดยไม่มีการสืบทอด อ่าน/เขียน  float .

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```


ส่งคืนแท็บของย่อหน้า ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [ITabCollection](../../com.aspose.slides/itabcollection)

**ผลลัพธ์:**  
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```


ส่งคืนหรือกำหนดการจัดแนวฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน [FontAlignment](../../com.aspose.slides/fontalignment)

**ผลลัพธ์:**  
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```


ส่งคืนหรือกำหนดการจัดแนวฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด อ่าน/เขียน [FontAlignment](../../com.aspose.slides/fontalignment)

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```


ส่งคืนรูปแบบส่วนเริ่มต้นของย่อหน้า ไม่ได้ใช้การสืบทอด อ่านอย่างเดียว [IPortionFormat](../../com.aspose.slides/iportionformat)

**ผลลัพธ์:**  
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```


ดึงข้อมูลการจัดรูปแบบย่อหน้าที่มีผลรวมกับการสืบทอด

--------------------

> ```
> ตัวอย่างนี้แสดงการดึงคุณสมบัติบางอย่างของรูปแบบย่อหน้าที่มีผล
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**ผลลัพธ์:**  
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


เวอร์ชัน อ่านอย่างเดียว long.

**ผลลัพธ์:**  
long