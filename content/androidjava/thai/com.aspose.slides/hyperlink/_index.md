---
title: Hyperlink
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงไฮเปอร์ลิงก์.
type: docs
url: /th/com.aspose.slides/hyperlink/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject  
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

แสดงถึงไฮเปอร์ลิงก์.

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์ |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์ที่ชี้ไปยังสไลด์เฉพาะ |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | สร้างอินสแตนซ์ของไฮเปอร์ลิงก์โดยใช้ไฮเปอร์ลิงก์อื่นเป็นแหล่งข้อมูล, แทนที่คุณสมบัติรอง |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | ส่งกลับไฮเปอร์ลิงก์พิเศษ "do nothing" |
| [getMedia()](#getMedia--) | ส่งกลับไฮเปอร์ลิงก์พิเศษ "play mediafile" |
| [getNextSlide()](#getNextSlide--) | ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์ถัดไป |
| [getPreviousSlide()](#getPreviousSlide--) | ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์ก่อนหน้า |
| [getFirstSlide()](#getFirstSlide--) | ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์แรกของการนำเสนอ |
| [getLastSlide()](#getLastSlide--) | ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์สุดท้ายของการนำเสนอ |
| [getLastVievedSlide()](#getLastVievedSlide--) | ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์ที่ดูล่าสุด |
| [getEndShow()](#getEndShow--) | ส่งกลับไฮเปอร์ลิงก์ที่จบการแสดง |
| [getActionType()](#getActionType--) | ส่งกลับประเภทของการกระทำของ Hyperlink |
| [getExternalUrl()](#getExternalUrl--) | ระบุ URL ภายนอก |
| [getTargetSlide()](#getTargetSlide--) | หาก Hyperlink ชี้ไปยังสไลด์เฉพาะ จะส่งกลับสไลด์นั้น |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | แสดงถึงไฮเปอร์ลิงก์ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาจริงของส่วน |
| [getTargetFrame()](#getTargetFrame--) | ส่งกลับเฟรมภายในชุดเฟรม HTML ของพาเรนต์สำหรับเป้าหมายของไฮเปอร์ลิงก์พาเรนต์เมื่อมีอยู่ |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | ส่งกลับเฟรมภายในชุดเฟรม HTML ของพาเรนต์สำหรับเป้าหมายของไฮเปอร์ลิงก์พาเรนต์เมื่อมีอยู่ |
| [getTooltip()](#getTooltip--) | ส่งกลับสตริงที่อาจแสดงในส่วนติดต่อผู้ใช้ที่เชื่อมโยงกับไฮเปอร์ลิงก์พาเรนต์ |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | ส่งกลับสตริงที่อาจแสดงในส่วนติดต่อผู้ใช้ที่เชื่อมโยงกับไฮเปอร์ลิงก์พาเรนต์ |
| [getHistory()](#getHistory--) | กำหนดว่าต้องเพิ่มเป้าหมายของไฮเปอร์ลิงก์พาเรนต์ไปยังรายการไฮเปอร์ลิงก์ที่ดูเมื่อเรียกใช้หรือไม่ |
| [setHistory(boolean value)](#setHistory-boolean-) | กำหนดว่าต้องเพิ่มเป้าหมายของไฮเปอร์ลิงก์พาเรนต์ไปยังรายการไฮเปอร์ลิงก์ที่ดูเมื่อเรียกใช้หรือไม่ |
| [getHighlightClick()](#getHighlightClick--) | กำหนดว่าฮัยเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่ |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | กำหนดว่าฮัยเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่ |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | กำหนดว่าควรหยุดเสียงเมื่อคลิกไฮเปอร์ลิงก์หรือไม่ |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | กำหนดว่าควรหยุดเสียงเมื่อคลิกไฮเปอร์ลิงก์หรือไม่ |
| [getSound()](#getSound--) | แสดงถึงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์ |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | แสดงถึงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์ |
| [getColorSource()](#getColorSource--) | แสดงถึงแหล่งของสีไฮเปอร์ลิงก์ - ทั้งสไตล์หรือรูปแบบส่วน |
| [setColorSource(int value)](#setColorSource-int-) | แสดงถึงแหล่งของสีไฮเปอร์ลิงก์ - ทั้งสไตล์หรือรูปแบบส่วน |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าตัวอย่าง Hyperlink สองอันเท่ากันหรือไม่ |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | กำหนดว่าตัวอย่าง Hyperlink สองอันเท่ากันหรือไม่ |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | ทดสอบสองไฮเปอร์ลิงก์เพื่อความเท่ากัน |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | ทดสอบสองไฮเปอร์ลิงก์เพื่อความไม่เท่ากัน |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทที่กำหนด, เหมาะสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่นตารางแฮช |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

สร้างอินสแตนซ์ของไฮเปอร์ลิงก์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของ Hyperlink |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

สร้างอินสแตนซ์ของไฮเปอร์ลิงก์ที่ชี้ไปยังสไลด์เฉพาะ หมายเหตุ: ไฮเปอร์ลิงก์ที่สร้างควรถูกกำหนดให้กับอ็อบเจ็กต์บางอย่างจากการนำเสนอเดียวกัน, มิฉะนั้นลิงก์จะถูกบันทึกเป็น NoAction.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์เป้าหมาย |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

สร้างอินสแตนซ์ของไฮเปอร์ลิงก์โดยใช้ไฮเปอร์ลิงก์อื่นเป็นแหล่ง, แทนที่คุณสมบัติรอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | ไฮเปอร์ลิงก์ต้นทาง |
| targetFrame | java.lang.String | เฟรมเป้าหมาย |
| tooltip | java.lang.String | ข้อความ Tooltip |
| history | boolean | กำหนดว่าต้องเพิ่มเป้าหมายของไฮเปอร์ลิงก์พาเรนต์ไปยังรายการไฮเปอร์ลิงก์ที่ดูเมื่อเรียกใช้หรือไม่ |
| stopSoundsOnClick | boolean | กำหนดว่าควรหยุดเสียงเมื่อคลิกไฮเปอร์ลิงก์หรือไม่ |
| highlightClick | boolean | กำหนดว่าฮัยเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่ |

### getVersion() {#getVersion--}
```
public long getVersion()
```

เวอร์ชัน. อ่านอย่างเดียว long.

**คืนค่า:**
long

### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

ส่งกลับไฮเปอร์ลิงก์พิเศษ "do nothing". อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

ส่งกลับไฮเปอร์ลิงก์พิเศษ "play mediafile". ใช้ใน AudioFrame และ VideoFrame. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์ถัดไป. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์ก่อนหน้า. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์แรกของการนำเสนอ. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์สุดท้ายของการนำเสนอ. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

ส่งกลับไฮเปอร์ลิงก์ไปยังสไลด์ที่ดูล่าสุด. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

ส่งกลับไฮเปอร์ลิงก์ที่จบการแสดง. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)

### getActionType() {#getActionType--}
```
public final int getActionType()
```

ส่งกลับประเภทของการกระทำของ Hyperlink. อ่านอย่างเดียว [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**คืนค่า:**
int

### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

ระบุ URL ภายนอก. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

หาก Hyperlink ชี้ไปยังสไลด์เฉพาะ จะส่งกลับสไลด์นั้น. อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide)

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

แสดงถึงไฮเปอร์ลิงก์ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาจริงของส่วน

--------------------

PowerPoint มีพฤติกรรมเฉพาะสำหรับลิงก์และข้อความที่สอดคล้องกันในแต่ละส่วน มันอนุญาตให้สร้างข้อความสำหรับไฮเปอร์ลิงก์ในรูปแบบของ URL ที่ถูกต้อง ซึ่งแตกต่างจากที่อยู่จริงของลิงก์ ในกรณีนี้เมื่อคุณดูลิงก์ในหน้าต่างแก้ไข มันจะถูกเปลี่ยนให้ตรงกับส่วนของข้อความ คุณสมบัตินี้แสดงถึงค่าต้นฉบับของไฮเปอร์ลิงก์.

**คืนค่า:**
java.lang.String

### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

ส่งกลับเฟรมภายในชุดเฟรม HTML ของพาเรนต์สำหรับเป้าหมายของไฮเปอร์ลิงก์พาเรนต์เมื่อมีอยู่. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

ส่งกลับเฟรมภายในชุดเฟรม HTML ของพาเรนต์สำหรับเป้าหมายของไฮเปอร์ลิงก์พาเรนต์เมื่อมีอยู่. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

ส่งกลับสตริงที่อาจแสดงในส่วนติดต่อผู้ใช้ที่เชื่อมโยงกับไฮเปอร์ลิงก์พาเรนต์. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

ส่งกลับสตริงที่อาจแสดงในส่วนติดต่อผู้ใช้ที่เชื่อมโยงกับไฮเปอร์ลิงก์พาเรนต์. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

กำหนดว่าตำแหน่งเป้าหมายของไฮเปอร์ลิงก์พาเรนต์จะถูกเพิ่มไปยังรายการไฮเปอร์ลิงก์ที่ดูเมื่อเรียกใช้หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

กำหนดว่าตำแหน่งเป้าหมายของไฮเปอร์ลิงก์พาเรนต์จะถูกเพิ่มไปยังรายการไฮเปอร์ลิงก์ที่ดูเมื่อเรียกใช้หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

กำหนดว่าฮัยเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

กำหนดว่าฮัยเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

กำหนดว่าควรหยุดเสียงเมื่อคลิกไฮเปอร์ลิงก์หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

กำหนดว่าควรหยุดเสียงเมื่อคลิกไฮเปอร์ลิงก์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

แสดงถึงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // รับไฮเปอร์ลิงก์ของรูปทรงแรก
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // แยกเสียงไฮเปอร์ลิงก์เป็นอาร์เรย์ของไบต์
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**คืนค่า:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

แสดงถึงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // รับไฮเปอร์ลิงก์ของรูปทรงแรก
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // แยกเสียงไฮเปอร์ลิงก์เป็นอาร์เรย์ของไบต์
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

แสดงถึงแหล่งของสีไฮเปอร์ลิงก์ - ทั้งสไตล์หรือรูปแบบส่วน. อ่าน/เขียน [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**คืนค่า:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

แสดงถึงแหล่งของสีไฮเปอร์ลิงก์ - ทั้งสไตล์หรือรูปแบบส่วน. อ่าน/เขียน [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าตัวอย่าง Hyperlink สองอันเท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | Hyperlink ที่จะเปรียบเทียบกับ Hyperlink ปัจจุบัน |

**คืนค่า:**
boolean - **true** หาก Hyperlink ที่ระบุเท่ากับ Hyperlink ปัจจุบัน; มิฉะนั้น **false**.

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

กำหนดว่าตัวอย่าง Hyperlink สองอันเท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink ที่จะเปรียบเทียบกับ Hyperlink ปัจจุบัน |

**คืนค่า:**
boolean - **true** หาก Hyperlink ที่ระบุเท่ากับ Hyperlink ปัจจุบัน; มิฉะนั้น **false**.

### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

ทดสอบสองไฮเปอร์ลิงก์เพื่อความเท่ากัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | ไฮเปอร์ลิงก์แรกที่ต้องทดสอบ |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | ไฮเปอร์ลิงก์ที่สองที่ต้องทดสอบ |

**คืนค่า:**
boolean - **true** หากไฮเปอร์ลิงก์เท่ากัน

### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

ทดสอบสองไฮเปอร์ลิงก์เพื่อความไม่เท่ากัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | ไฮเปอร์ลิงก์แรกที่ต้องทดสอบ |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | ไฮเปอร์ลิงก์ที่สองที่ต้องทดสอบ |

**คืนค่า:**
boolean - **false** หากไฮเปอร์ลิงก์เท่ากัน

### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทที่กำหนด, เหมาะสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่นตารางแฮช.

**คืนค่า:**
int - โฮชโค้ดสำหรับ URL

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งกลับอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject