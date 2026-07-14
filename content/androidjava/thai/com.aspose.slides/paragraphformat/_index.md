---
title: ParagraphFormat
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: คลาสนี้ประกอบด้วยคุณสมบัติการจัดรูปแบบย่อหน้า.
type: docs
url: /th/com.aspose.slides/paragraphformat/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่ทำการนำไปใช้ทั้งหมด:**  
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)  
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

คลาสนี้มีคุณสมบัติการจัดรูปแบบย่อหน้า. แตกต่างจาก [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) คุณสมบัติทั้งหมดของคลาสนี้สามารถเขียนได้.

--------------------

คลาสนี้ใช้เพื่อคืนค่าและจัดการคุณสมบัติการจัดรูปแบบย่อหน้าที่กำหนดสำหรับย่อหน้าเฉพาะ. ความหมายคือการสืบทอดจะไม่ถูกนำมาใช้เมื่อดึงค่าจึงในกรณีส่วนใหญ่คุณจะได้ค่าที่หมายถึง "undefined".

เพื่อให้ได้ค่าพารามิเตอร์การจัดรูปแบบที่มีผลรวมถึงการสืบทอด คุณจำเป็นต้องใช้วิธี [getEffective](../../com.aspose.slides/paragraphformat\#getEffective) ซึ่งจะคืนค่าอินสแตนซ์ของ [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | สร้างอินสแตนซ์ใหม่ของ [ParagraphFormat](../../com.aspose.slides/paragraphformat) class. |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBullet()](#getBullet--) | คืนรูปแบบหัวข้อของย่อหน้า. |
| [getDepth()](#getDepth--) | คืนหรือกำหนดความลึกของย่อหน้า. |
| [setDepth(short value)](#setDepth-short-) | คืนหรือกำหนดความลึกของย่อหน้า. |
| [getAlignment()](#getAlignment--) | คืนหรือกำหนดการจัดตำแหน่งข้อความในย่อหน้าโดยไม่มีการสืบทอด. |
| [setAlignment(int value)](#setAlignment-int-) | คืนหรือกำหนดการจัดตำแหน่งข้อความในย่อหน้าโดยไม่มีการสืบทอด. |
| [getSpaceWithin()](#getSpaceWithin--) | คืนหรือกำหนดจำนวนพื้นที่ระหว่างบรรทัดฐานในย่อหน้า. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | คืนหรือกำหนดจำนวนพื้นที่ระหว่างบรรทัดฐานในย่อหน้า. |
| [getSpaceBefore()](#getSpaceBefore--) | คืนหรือกำหนดจำนวนพื้นที่ก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | คืนหรือกำหนดจำนวนพื้นที่ก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด. |
| [getSpaceAfter()](#getSpaceAfter--) | คืนหรือกำหนดจำนวนพื้นที่หลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | คืนหรือกำหนดจำนวนพื้นที่หลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | กำหนดว่าการตัดบรรทัดเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | กำหนดว่าการตัดบรรทัดเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่. |
| [getRightToLeft()](#getRightToLeft--) | กำหนดว่าการเขียนจากขวาไปซ้ายถูกใช้ในย่อหน้าหรือไม่. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | กำหนดว่าการเขียนจากขวาไปซ้ายถูกใช้ในย่อหน้าหรือไม่. |
| [getLatinLineBreak()](#getLatinLineBreak--) | กำหนดว่าการตัดบรรทัดละตินถูกใช้ในย่อหน้าหรือไม่. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | กำหนดว่าการตัดบรรทัดละตินถูกใช้ในย่อหน้าหรือไม่. |
| [getHangingPunctuation()](#getHangingPunctuation--) | กำหนดว่าการใส่เครื่องหมายวรรคตอนห้อยถูกใช้ในย่อหน้าหรือไม่. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | กำหนดว่าการใส่เครื่องหมายวรรคตอนห้อยถูกใช้ในย่อหน้าหรือไม่. |
| [getMarginLeft()](#getMarginLeft--) | คืนหรือกำหนดระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | คืนหรือกำหนดระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด. |
| [getMarginRight()](#getMarginRight--) | คืนหรือกำหนดระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด. |
| [setMarginRight(float value)](#setMarginRight-float-) | คืนหรือกำหนดระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด. |
| [getIndent()](#getIndent--) | คืนหรือกำหนดการเยื้องบรรทัดแรก/เยื้องห้อยของย่อหน้าโดยไม่มีการสืบทอด. |
| [setIndent(float value)](#setIndent-float-) | คืนหรือกำหนดการเยื้องบรรทัดแรก/เยื้องห้อยของย่อหน้าโดยไม่มีการสืบทอด. |
| [getDefaultTabSize()](#getDefaultTabSize--) | คืนหรือกำหนดขนาดแท็บปริยายโดยไม่มีการสืบทอด. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | คืนหรือกำหนดขนาดแท็บปริยายโดยไม่มีการสืบทอด. |
| [getTabs()](#getTabs--) | คืนค่าแท็บของย่อหน้า. |
| [getFontAlignment()](#getFontAlignment--) | คืนหรือกำหนดการจัดแนวฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | คืนหรือกำหนดการจัดแนวฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | คืนรูปแบบส่วนเริ่มต้นของย่อหน้า. |
| [getEffective()](#getEffective--) | ดึงข้อมูลการจัดรูปแบบย่อหน้าที่มีผลรวมการสืบทอด. |
| [getVersion()](#getVersion--) |  |

### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

สร้างอินสแตนซ์ใหม่ของ [ParagraphFormat](../../com.aspose.slides/paragraphformat) class.

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

คืนรูปแบบหัวข้อของย่อหน้า. อ่านอย่างเดียว [IBulletFormat](../../com.aspose.slides/ibulletformat).

**คืนค่า:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public final short getDepth()
```

คืนหรือกำหนดความลึกของย่อหน้า. ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด. อ่าน/เขียน short .

**คืนค่า:**
short

### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

คืนหรือกำหนดความลึกของย่อหน้า. ค่า 0 หมายถึงค่าที่ไม่ได้กำหนด. อ่าน/เขียน short .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

คืนหรือกำหนดการจัดตำแหน่งข้อความในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // สร้างอ็อบเจ็กต์ Presentation ที่แสดงไฟล์ PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // เข้าถึงสไลด์แรก
>      ISlide slide = pres.getSlides().get_Item(0);
>      // เข้าถึง placeholder แรกและที่สองในสไลด์และแคสเป็น AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // เปลี่ยนข้อความใน placeholder ทั้งสอง
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // ดึงย่อหน้าที่แรกของ placeholder
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // จัดตำแหน่งย่อความข้อความให้อยู่กึ่งกลาง
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // บันทึกงานนำเสนอเป็นไฟล์ PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

คืนหรือกำหนดการจัดตำแหน่งข้อความในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // สร้างอ็อบเจ็กต์ Presentation ที่แสดงไฟล์ PPTX
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // เข้าถึงสไลด์แรก
>      ISlide slide = pres.getSlides().get_Item(0);
>      // เข้าถึง placeholder แรกและที่สองในสไลด์และแคสเป็น AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // เปลี่ยนข้อความใน placeholder ทั้งสอง
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // ดึงย่อหน้าที่แรกของ placeholder
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // จัดตำแหน่งย่อความข้อความให้อยู่กึ่งกลาง
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      //บันทึกงานนำเสนอเป็นไฟล์ PPTX
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

คืนหรือกำหนดจำนวนพื้นที่ระหว่างบรรทัดฐานในย่อหน้า. ค่าเป็นบวกหมายถึงเปอร์เซ็นต์, ค่าลบหมายถึงขนาดเป็นจุด. ไม่มีการสืบทอด. อ่าน/เขียน float .

**คืนค่า:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

คืนหรือกำหนดจำนวนพื้นที่ระหว่างบรรทัดฐานในย่อหน้า. ค่าเป็นบวกหมายถึงเปอร์เซ็นต์, ค่าลบหมายถึงขนาดเป็นจุด. ไม่มีการสืบทอด. อ่าน/เขียน float .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

คืนหรือกำหนดจำนวนพื้นที่ก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด. ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ต้องการช่องว่างสีขาว. ค่าเป็นลบระบุขนาดของช่องว่างสีขาวเป็นจุด. อ่าน/เขียน float .

**คืนค่า:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

คืนหรือกำหนดจำนวนพื้นที่ก่อนบรรทัดแรกในย่อหน้าโดยไม่มีการสืบทอด. ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ต้องการช่องว่างสีขาว. ค่าเป็นลบระบุขนาดของช่องว่างสีขาวเป็นจุด. อ่าน/เขียน float .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

คืนหรือกำหนดจำนวนพื้นที่หลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด. ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ต้องการช่องว่างสีขาว. ค่าเป็นลบระบุขนาดของช่องว่างสีขาวเป็นจุด. อ่าน/เขียน float .

**คืนค่า:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

คืนหรือกำหนดจำนวนพื้นที่หลังบรรทัดสุดท้ายในย่อหน้าโดยไม่มีการสืบทอด. ค่าเป็นบวกระบุเปอร์เซ็นต์ของขนาดฟอนต์ที่ต้องการช่องว่างสีขาว. ค่าเป็นลบระบุขนาดของช่องว่างสีขาวเป็นจุด. อ่าน/เขียน float .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

กำหนดว่าการตัดบรรทัดเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

กำหนดว่าการตัดบรรทัดเอเชียตะวันออกถูกใช้ในย่อหน้าหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

กำหนดว่าการเขียนจากขวาไปซ้ายถูกใช้ในย่อหน้าหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

กำหนดว่าการเขียนจากขวาไปซ้ายถูกใช้ในย่อหน้าหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

กำหนดว่าการตัดบรรทัดละตินถูกใช้ในย่อหน้าหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

กำหนดว่าการตัดบรรทัดละตินถูกใช้ในย่อหน้าหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

กำหนดว่าการใส่เครื่องหมายวรรคตอนห้อยถูกใช้ในย่อหน้าหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**คืนค่า:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

กำหนดว่าการใส่เครื่องหมายวรรคตอนห้อยถูกใช้ในย่อหน้าหรือไม่. ไม่มีการสืบทอด. อ่าน/เขียน [NullableBool](../../com.aspose.slides/nullablebool).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

คืนหรือกำหนดระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน float .

**คืนค่า:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

คืนหรือกำหนดระยะขอบซ้ายในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน float .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

คืนหรือกำหนดระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน float .

**คืนค่า:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

คืนหรือกำหนดระยะขอบขวาในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน float .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public final float getIndent()
```

คืนหรือกำหนดการเยื้องบรรทัดแรก/เยื้องห้อยของย่อหน้าโดยไม่มีการสืบทอด. การเยื้องห้อยสามารถกำหนดด้วยค่าติดลบ. อ่าน/เขียน float .

**คืนค่า:**
float

### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

คืนหรือกำหนดการเยื้องบรรทัดแรก/เยื้องห้อยของย่อหน้าโดยไม่มีการสืบทอด. การเยื้องห้อยสามารถกำหนดด้วยค่าติดลบ. อ่าน/เขียน float .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

คืนหรือกำหนดขนาดแท็บปริยายโดยไม่มีการสืบทอด. อ่าน/เขียน float .

**คืนค่า:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

คืนหรือกำหนดขนาดแท็บปริยายโดยไม่มีการสืบทอด. อ่าน/เขียน float .

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

คืนค่าแท็บของย่อหน้า. ไม่มีการสืบทอด. อ่านอย่างเดียว [ITabCollection](../../com.aspose.slides/itabcollection).

**คืนค่า:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

คืนหรือกำหนดการจัดแนวฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน [FontAlignment](../../com.aspose.slides/fontalignment).

**คืนค่า:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

คืนหรือกำหนดการจัดแนวฟอนต์ในย่อหน้าโดยไม่มีการสืบทอด. อ่าน/เขียน [FontAlignment](../../com.aspose.slides/fontalignment).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

คืนรูปแบบส่วนเริ่มต้นของย่อหน้า. ไม่มีการสืบทอด. อ่านอย่างเดียว [IPortionFormat](../../com.aspose.slides/iportionformat).

**คืนค่า:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

ดึงข้อมูลการจัดรูปแบบย่อหน้าที่มีผลรวมการสืบทอด.

--------------------

> ```
> This example demonstrates getting some effective paragraph format properties.
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

**คืนค่า:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long