---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: แสดงถึงไฮเปอร์ลิงก์.
type: docs
url: /th/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

แสดงถึงไฮเปอร์ลิงก์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getActionType()](#getActionType--) | ส่งคืนประเภทของการทำงานของ HyperLinkEx |
| [getExternalUrl()](#getExternalUrl--) | ระบุ URL ภายนอก หากคุณสมบัตินี้ไม่เป็น null แล้วคุณสมบัติ TargetSlide จะเป็น null |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | แสดงไฮเปอร์ลิงก์ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาจริงของส่วนนั้น |
| [getTargetSlide()](#getTargetSlide--) | หาก HyperlinkEx ชี้เป้าไปยังสไลด์เฉพาะจะส่งคืนสไลด์นั้น |
| [getTargetFrame()](#getTargetFrame--) | ส่งคืนเฟรมภายในชุดเฟรม HTML พาเรนท์สำหรับเป้าหมายของไฮเปอร์ลิงก์พาเรนท์เมื่อมีอยู่ |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | ส่งคืนเฟรมภายในชุดเฟรม HTML พาเรนท์สำหรับเป้าหมายของไฮเปอร์ลิงก์พาเรนท์เมื่อมีอยู่ |
| [getTooltip()](#getTooltip--) | ส่งคืนสตริงที่อาจแสดงในส่วนติดต่อผู้ใช้ที่เชื่อมโยงกับไฮเปอร์ลิงก์พาเรนท์ |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | ส่งคืนสตริงที่อาจแสดงในส่วนติดต่อผู้ใช้ที่เชื่อมโยงกับไฮเปอร์ลิงก์พาเรนท์ |
| [getHistory()](#getHistory--) | กำหนดว่าเป้าหมายของไฮเปอร์ลิงก์พาเรนท์จะถูกเพิ่มในรายการไฮเปอร์ลิงก์ที่ดูแล้วเมื่อถูกเรียกใช้หรือไม่ |
| [setHistory(boolean value)](#setHistory-boolean-) | กำหนดว่าเป้าหมายของไฮเปอร์ลิงก์พาเรนท์จะถูกเพิ่มในรายการไฮเปอร์ลิงก์ที่ดูแล้วเมื่อถูกเรียกใช้หรือไม่ |
| [getHighlightClick()](#getHighlightClick--) | กำหนดว่าไฮเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่ |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | กำหนดว่าไฮเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่ |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | กำหนดว่าเสียงควรหยุดเมื่อคลิกไฮเปอร์ลิงก์หรือไม่ |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | กำหนดว่าเสียงควรหยุดเมื่อคลิกไฮเปอร์ลิงก์หรือไม่ |
| [getSound()](#getSound--) | แสดงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์ |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | แสดงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์ |
| [getColorSource()](#getColorSource--) | แสดงแหล่งที่มาของสีไฮเปอร์ลิงก์ - ทั้งสไตล์หรือรูปแบบส่วน |
| [setColorSource(int value)](#setColorSource-int-) | แสดงแหล่งที่มาของสีไฮเปอร์ลิงก์ - ทั้งสไตล์หรือรูปแบบส่วน |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | กำหนดว่าอินสแตนซ์ Hyperlink สองตัวเท่ากันหรือไม่ |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```


ส่งคืนประเภทของการทำงานของ HyperLinkEx. อ่านอย่างเดียว [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**คืนค่า:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```


ระบุ URL ภายนอก หากคุณสมบัตินี้ไม่เป็น null แล้วคุณสมบัติ TargetSlide จะเป็น null. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```


แสดงไฮเปอร์ลิงก์ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาจริงของส่วนนั้น.

--------------------

PowerPoint มีพฤติกรรมเฉพาะสำหรับลิงก์และข้อความที่สอดคล้องในส่วนหนึ่ง มันอนุญาตให้สร้างข้อความสำหรับไฮเปอร์ลิงก์ในรูปแบบของ URL ที่ถูกต้อง ซึ่งแตกต่างจากที่อยู่จริงของลิงก์ ในกรณีนี้เมื่อคุณดูลิงก์ในหน้าต่างแก้ไข จะถูกเปลี่ยนให้ตรงกับข้อความส่วนนั้น คุณสมบัตินี้แสดงถึงค่าต้นฉบับของไฮเปอร์ลิงก์.

**คืนค่า:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


หาก HyperlinkEx ชี้เป้าไปยังสไลด์เฉพาะจะส่งคืนสไลด์นั้น หากคุณสมบัตินี้ไม่เป็น null แล้วคุณสมบัติ ExternalUrl จะเป็น null. อ่านอย่างเดียว [ISlide](../../com.aspose.slides/islide).

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```


ส่งคืนเฟรมภายในชุดเฟรม HTML พาเรนท์สำหรับเป้าหมายของไฮเปอร์ลิงก์พาเรนท์เมื่อมีอยู่. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```


ส่งคืนเฟรมภายในชุดเฟรม HTML พาเรนท์สำหรับเป้าหมายของไฮเปอร์ลิงก์พาเรนท์เมื่อมีอยู่. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```


ส่งคืนสตริงที่อาจแสดงในส่วนติดต่อผู้ใช้ที่เชื่อมโยงกับไฮเปอร์ลิงก์พาเรนท์. อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```


ส่งคืนสตริงที่อาจแสดงในส่วนติดต่อผู้ใช้ที่เชื่อมโยงกับไฮเปอร์ลิงก์พาเรนท์. อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```


กำหนดว่าเป้าหมายของไฮเปอร์ลิงก์พาเรนท์จะถูกเพิ่มในรายการไฮเปอร์ลิงก์ที่ดูแล้วเมื่อถูกเรียกใช้หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```


กำหนดว่าเป้าหมายของไฮเปอร์ลิงก์พาเรนท์จะถูกเพิ่มในรายการไฮเปอร์ลิงก์ที่ดูแล้วเมื่อถูกเรียกใช้หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```


กำหนดว่าไฮเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```


กำหนดว่าไฮเปอร์ลิงก์ควรไฮไลท์เมื่อคลิกหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```


กำหนดว่าเสียงควรหยุดเมื่อคลิกไฮเปอร์ลิงก์หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```


กำหนดว่าเสียงควรหยุดเมื่อคลิกไฮเปอร์ลิงก์หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


แสดงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // ดึงไฮเปอร์ลิงก์ของรูปทรงแรก
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
public abstract void setSound(IAudio value)
```


แสดงเสียงที่กำลังเล่นของไฮเปอร์ลิงก์. อ่าน/เขียน [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // ดึงไฮเปอร์ลิงก์ของรูปทรงแรก
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
public abstract int getColorSource()
```


แสดงแหล่งที่มาของสีไฮเปอร์ลิงก์ - ทั้งสไตล์หรือรูปแบบส่วน. อ่าน/เขียน [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**คืนค่า:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```


แสดงแหล่งที่มาของสีไฮเปอร์ลิงก์ - ทั้งสไตล์หรือรูปแบบส่วน. อ่าน/เขียน [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```


กำหนดว่าอินสแตนซ์ Hyperlink สองตัวเท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink ที่จะเปรียบเทียบกับ Hyperlink ปัจจุบัน |

**คืนค่า:**
boolean - **true** หาก Hyperlink ที่ระบุเท่ากับ Hyperlink ปัจจุบัน; มิฉะนั้น **false**.