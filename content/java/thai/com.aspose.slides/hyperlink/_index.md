---
title: Hyperlink
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงไฮเปอร์ลิงก์.
type: docs
url: /th/com.aspose.slides/hyperlink/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**ทุกอินเทอร์เฟซที่ทำการใช้งาน:**
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
| [getNoAction()](#getNoAction--) | ส่งคืนไฮเปอร์ลิงก์พิเศษ “ทำอะไรไม่ได้”. |
| [getMedia()](#getMedia--) | ส่งคืนไฮเปอร์ลิงก์พิเศษ “เล่นไฟล์สื่อ”. |
| [getNextSlide()](#getNextSlide--) | ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์ถัดไป. |
| [getPreviousSlide()](#getPreviousSlide--) | ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์ก่อนหน้า. |
| [getFirstSlide()](#getFirstSlide--) | ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์แรกของงานนำเสนอ. |
| [getLastSlide()](#getLastSlide--) | ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์สุดท้ายของงานนำเสนอ. |
| [getLastVievedSlide()](#getLastVievedSlide--) | ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์ที่ดูล่าสุด. |
| [getEndShow()](#getEndShow--) | ส่งคืนไฮเปอร์ลิงก์ที่สิ้นสุดการแสดง. |
| [getActionType()](#getActionType--) | ส่งคืนประเภทของการกระทำของ Hyperlink. |
| [getExternalUrl()](#getExternalUrl--) | ระบุ URL ภายนอก. |
| [getTargetSlide()](#getTargetSlide--) | ถ้า Hyperlink ชี้ไปยังสไลด์เฉพาะจะส่งคืนสไลด์นั้น. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | แสดงถึงไฮเปอร์ลิงก์ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาจริงของส่วน. |
| [getTargetFrame()](#getTargetFrame--) | ส่งคืนเฟรมภายในชุดเฟรม HTML ของพาเรนต์สำหรับเป้าหมายของ Hyperlink พาเรนต์เมื่อมีอยู่. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | ส่งคืนเฟรมภายในชุดเฟรม HTML ของพาเรนต์สำหรับเป้าหมายของ Hyperlink พาเรนต์เมื่อมีอยู่. |
| [getTooltip()](#getTooltip--) | ส่งคืนสตริงที่อาจแสดงใน UI ที่เชื่อมโยงกับ Hyperlink พาเรนต์. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | ส่งคืนสตริงที่อาจแสดงใน UI ที่เชื่อมโยงกับ Hyperlink พาเรนต์. |
| [getHistory()](#getHistory--) | กำหนดว่าเป้าหมายของ Hyperlink พาเรนต์จะถูกเพิ่มในรายการของ Hyperlink ที่ดูแล้วเมื่อถูกเรียกหรือไม่. |
| [setHistory(boolean value)](#setHistory-boolean-) | กำหนดว่าเป้าหมายของ Hyperlink พาเรนต์จะถูกเพิ่มในรายการของ Hyperlink ที่ดูแล้วเมื่อถูกเรียกหรือไม่. |
| [getHighlightClick()](#getHighlightClick--) | กำหนดว่าไฮเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | กำหนดว่าไฮเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | กำหนดว่าเสียงควรหยุดเมื่อคลิกไฮเปอร์ลิงก์หรือไม่. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | กำหนดว่าเสียงควรหยุดเมื่อคลิกไฮเปอร์ลิงก์หรือไม่. |
| [getSound()](#getSound--) | แสดงถึงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | แสดงถึงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์. |
| [getColorSource()](#getColorSource--) | แสดงถึงแหล่งที่มาของสีไฮเปอร์ลิงก์ - สไตล์หรือรูปแบบส่วน. |
| [setColorSource(int value)](#setColorSource-int-) | แสดงถึงแหล่งที่มาของสีไฮเปอร์ลิงก์ - สไตล์หรือรูปแบบส่วน. |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าสองอินสแตนซ์ Hyperlink เท่ากันหรือไม่. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | กำหนดว่าสองอินสแตนซ์ Hyperlink เท่ากันหรือไม่. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | ทดสอบสองไฮเปอร์ลิงก์เพื่อความเท่ากัน. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | ทดสอบสองไฮเปอร์ลิงก์เพื่อความไม่เท่ากัน. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ, เหมาะสำหรับการใช้งานในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

สร้างอินสแตนซ์ของไฮเปอร์ลิงก์.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| url | java.lang.String | URL ของไฮเปอร์ลิงก์. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

สร้างอินสแตนซ์ของไฮเปอร์ลิงก์ที่ชี้ไปยังสไลด์เฉพาะ. หมายเหตุ: ไฮเปอร์ลิงก์ที่สร้างควรถูกกำหนดให้กับออบเจกต์จากงานนำเสนอเดียวกัน, ไม่เช่นนั้นลิงก์จะถูกบันทึกเป็น NoAction.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | สไลด์เป้าหมาย. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

สร้างอินสแตนซ์ของไฮเปอร์ลิงก์โดยใช้ไฮเปอร์ลิงก์อื่นเป็นแหล่งข้อมูล, แทนที่คุณสมบัติรอง.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | ไฮเปอร์ลิงก์ต้นฉบับ |
| targetFrame | java.lang.String | เฟรมเป้าหมาย |
| tooltip | java.lang.String | ข้อความคำแนะนำ |
| history | boolean | กำหนดว่าเป้าหมายของ Hyperlink พาเรนต์จะถูกเพิ่มในรายการของ Hyperlink ที่ดูแล้วเมื่อถูกเรียกหรือไม่. |
| stopSoundsOnClick | boolean | กำหนดว่าเสียงควรหยุดเมื่อคลิกไฮเปอร์ลิงก์หรือไม่. |
| highlightClick | boolean | กำหนดว่าไฮเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่. |

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

ส่งคืนไฮเปอร์ลิงก์พิเศษ “ทำอะไรไม่ได้”. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

ส่งคืนไฮเปอร์ลิงก์พิเศษ “เล่นไฟล์สื่อ”. ใช้ใน AudioFrame และ VideoFrame. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์ถัดไป. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์ก่อนหน้า. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์แรกของงานนำเสนอ. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์สุดท้ายของงานนำเสนอ. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

ส่งคืนไฮเปอร์ลิงก์ไปยังสไลด์ที่ดูล่าสุด. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

ส่งคืนไฮเปอร์ลิงก์ที่สิ้นสุดการแสดง. อ่านอย่างเดียว [Hyperlink](../../com.aspose.slides/hyperlink).

**คืนค่า:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

ส่งคืนประเภทของการกระทำของ Hyperlink. อ่านอย่างเดียว [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

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

ถ้า Hyperlink ชี้ไปยังสไลด์เฉพาะจะส่งคืนสไลด์นั้น. อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

แสดงถึงไฮเปอร์ลิงก์ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาจริงของส่วน.

--------------------

PowerPoint ทำงานอย่างพิเศษกับลิงก์และข้อความที่สอดคล้องในส่วน. มันอนุญาตให้สร้างข้อความสำหรับไฮเปอร์ลิงก์ในรูปของ URL ที่ถูกต้อง, ซึ่งแตกต่างจากที่อยู่จริงของลิงก์. ในกรณีนี้, เมื่อคุณดูลิงก์ในหน้าต่างแก้ไข, มันจะถูกเปลี่ยนให้ตรงกับข้อความส่วน. คุณสมบัตินี้แสดงถึงค่าต้นฉบับของไฮเปอร์ลิงก์.

**คืนค่า:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

ส่งคืนเฟรมภายในชุดเฟรม HTML ของพาเรนต์สำหรับเป้าหมายของ Hyperlink พาเรนต์เมื่อมีอยู่. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

ส่งคืนเฟรมภายในชุดเฟรม HTML ของพาเรนต์สำหรับเป้าหมายของ Hyperlink พาเรนต์เมื่อมีอยู่. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

ส่งคืนสตริงที่อาจแสดงใน UI ที่เชื่อมโยงกับ Hyperlink พาเรนต์. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

ส่งคืนสตริงที่อาจแสดงใน UI ที่เชื่อมโยงกับ Hyperlink พาเรนต์. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

กำหนดว่าเป้าหมายของ Hyperlink พาเรนต์จะถูกเพิ่มในรายการของ Hyperlink ที่ดูแล้วเมื่อถูกเรียกหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

กำหนดว่าเป้าหมายของ Hyperlink พาเรนต์จะถูกเพิ่มในรายการของ Hyperlink ที่ดูแล้วเมื่อถูกเรียกหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

กำหนดว่าไฮเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

กำหนดว่าไฮเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

กำหนดว่าเสียงควรหยุดเมื่อคลิกไฮเปอร์ลิงก์หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

กำหนดว่าเสียงควรหยุดเมื่อคลิกไฮเปอร์ลิงก์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
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
>      // รับไฮเปอร์ลิงก์ของรูปร่างแรก
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // ดึงเสียงของไฮเปอร์ลิงก์เป็นอาร์เรย์ของไบต์
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
>      // ดึงไฮเปอร์ลิงก์ของรูปร่างแรก
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // ดึงเสียงของไฮเปอร์ลิงก์เป็นอาร์เรย์ของไบต์
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

แสดงถึงแหล่งที่มาของสีไฮเปอร์ลิงก์ - สไตล์หรือรูปแบบส่วน. อ่าน/เขียน [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**คืนค่า:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

แสดงถึงแหล่งที่มาของสีไฮเปอร์ลิงก์ - สไตล์หรือรูปแบบส่วน. อ่าน/เขียน [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าสองอินสแตนซ์ Hyperlink เท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | Hyperlink ที่จะเปรียบเทียบกับ Hyperlink ปัจจุบัน. |

**คืนค่า:**
boolean - **true** หาก Hyperlink ที่ระบุเท่ากับ Hyperlink ปัจจุบัน; มิฉะนั้น **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

กำหนดว่าสองอินสแตนซ์ Hyperlink เท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink ที่จะเปรียบเทียบกับ Hyperlink ปัจจุบัน. |

**คืนค่า:**
boolean - **true** หาก Hyperlink ที่ระบุเท่ากับ Hyperlink ปัจจุบัน; มิฉะนั้น **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

ทดสอบสองไฮเปอร์ลิงก์เพื่อความเท่ากัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | ไฮเปอร์ลิงก์แรกที่ต้องทดสอบ. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | ไฮเปอร์ลิงก์ที่สองที่ต้องทดสอบ. |

**คืนค่า:**
boolean - **true** หากไฮเปอร์ลิงก์เท่ากัน.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

ทดสอบสองไฮเปอร์ลิงก์เพื่อความไม่เท่ากัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | ไฮเปอร์ลิงก์แรกที่ต้องทดสอบ. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | ไฮเปอร์ลิงก์ที่สองที่ต้องทดสอบ. |

**คืนค่า:**
boolean - **false** หากไฮเปอร์ลิงก์เท่ากัน.
### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะ, เหมาะสำหรับการใช้งานในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช.

**คืนค่า:**
int - โค้ดแฮชสำหรับ URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนอ็อบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject