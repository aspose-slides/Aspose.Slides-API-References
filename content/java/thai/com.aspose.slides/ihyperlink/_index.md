---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: แสดงถึง hyperlink.
type: docs
url: /th/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

แสดงถึง hyperlink.

## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| [getActionType()](#getActionType--) | คืนค่าชนิดของการกระทำของ HyperLinkEx |
| [getExternalUrl()](#getExternalUrl--) | ระบุ URL ภายนอก หากคุณสมบัตินี้เป็นค่าไม่เป็น null แล้วคุณสมบัติ TargetSlide จะเป็น null |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | แสดงถึง hyperlink ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาจริงของส่วนนั้น |
| [getTargetSlide()](#getTargetSlide--) | หาก HyperlinkEx ชี้เป้าไปยังสไลด์เฉพาะ จะคืนค่าสไลด์นั้น |
| [getTargetFrame()](#getTargetFrame--) | คืนค่าเฟรมภายในชุดเฟรม HTML พาเรนท์สำหรับเป้าหมายของ hyperlink พาเรนท์เมื่อมีอยู่ |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | คืนค่าเฟรมภายในชุดเฟรม HTML พาเรนท์สำหรับเป้าหมายของ hyperlink พาเรนท์เมื่อมีอยู่ |
| [getTooltip()](#getTooltip--) | คืนค่า string ที่อาจแสดงในส่วนติดต่อผู้ใช้เป็นข้อมูลที่เชื่อมกับ hyperlink พาเรนท์ |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | คืนค่า string ที่อาจแสดงในส่วนติดต่อผู้ใช้เป็นข้อมูลที่เชื่อมกับ hyperlink พาเรนท์ |
| [getHistory()](#getHistory--) | กำหนดว่าตำแหน่งเป้าหมายของ hyperlink พาเรนท์จะถูกเพิ่มเข้าในรายการ hyperlink ที่ดูแล้วเมื่อถูกเรียกใช้หรือไม่ |
| [setHistory(boolean value)](#setHistory-boolean-) | กำหนดว่าตำแหน่งเป้าหมายของ hyperlink พาเรนท์จะถูกเพิ่มเข้าในรายการ hyperlink ที่ดูแล้วเมื่อถูกเรียกใช้หรือไม่ |
| [getHighlightClick()](#getHighlightClick--) | กำหนดว่า hyperlink ควรไฮไลท์เมื่อคลิกหรือไม่ |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | กำหนดว่า hyperlink ควรไฮไลท์เมื่อคลิกหรือไม่ |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | กำหนดว่าเสียงควรหยุดเมื่อคลิก hyperlink หรือไม่ |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | กำหนดว่าเสียงควรหยุดเมื่อคลิก hyperlink หรือไม่ |
| [getSound()](#getSound--) | แสดงถึงเสียงที่กำลังเล่นของ hyperlink |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | แสดงถึงเสียงที่กำลังเล่นของ hyperlink |
| [getColorSource()](#getColorSource--) | แสดงถึงแหล่งที่มาของสี hyperlink - ทั้งสไตล์หรือรูปแบบส่วน |
| [setColorSource(int value)](#setColorSource-int-) | แสดงถึงแหล่งที่มาของสี hyperlink - ทั้งสไตล์หรือรูปแบบส่วน |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | กำหนดว่าตัวอย่าง Hyperlink สองตัวเท่ากันหรือไม่ |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

คืนค่าชนิดของการกระทำของ HyperLinkEx. อ่านได้เท่านั้น [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**คืนค่า:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

ระบุ URL ภายนอก หากคุณสมบัตินี้เป็นค่าไม่เป็น null แล้วคุณสมบัติ TargetSlide จะเป็น null. อ่านได้เท่านั้น String.

**คืนค่า:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

แสดงถึง hyperlink ที่ตั้งค่าสำหรับส่วนนี้โดยไม่คำนึงถึงเนื้อหาจริงของส่วนนั้น.

--------------------

PowerPoint มีพฤติกรรมพิเศษสำหรับลิงก์และข้อความที่สอดคล้องกันในส่วนหนึ่ง มันอนุญาตให้สร้างข้อความสำหรับ hyperlink ในรูปแบบ URL ที่ถูกต้อง ซึ่งแตกต่างจากที่อยู่จริงของลิงก์ ในกรณีนี้เมื่อคุณดูลิงก์ในหน้าต่างแก้ไข จะถูกเปลี่ยนให้ตรงกับส่วนข้อความ คุณสมบัตินี้แสดงถึงค่าต้นฉบับของ hyperlink.

**คืนค่า:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

หาก HyperlinkEx ชี้เป้าไปยังสไลด์เฉพาะ จะคืนค่าสไลด์นั้น หากคุณสมบัตินี้เป็นค่าไม่เป็น null แล้วคุณสมบัติ ExternalUrl จะเป็น null. อ่านได้เท่านั้น [ISlide](../../com.aspose.slides/islide).

**คืนค่า:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

คืนค่าเฟรมภายในชุดเฟรม HTML พาเรนท์สำหรับเป้าหมายของ hyperlink พาเรนท์เมื่อมีอยู่. สามารถอ่าน/เขียนได้ String.

**คืนค่า:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

คืนค่าเฟรมภายในชุดเฟรม HTML พาเรนท์สำหรับเป้าหมายของ hyperlink พาเรนท์เมื่อมีอยู่. สามารถอ่าน/เขียนได้ String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

คืนค่า string ที่อาจแสดงในส่วนติดต่อผู้ใช้เป็นข้อมูลที่เชื่อมกับ hyperlink พาเรนท์. สามารถอ่าน/เขียนได้ String.

**คืนค่า:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

คืนค่า string ที่อาจแสดงในส่วนติดต่อผู้ใช้เป็นข้อมูลที่เชื่อมกับ hyperlink พาเรนท์. สามารถอ่าน/เขียนได้ String.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

กำหนดว่าตำแหน่งเป้าหมายของ hyperlink พาเรนท์จะถูกเพิ่มเข้าในรายการ hyperlink ที่ดูแล้วเมื่อถูกเรียกใช้หรือไม่. สามารถอ่าน/เขียนได้ boolean.

**คืนค่า:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

กำหนดว่าตำแหน่งเป้าหมายของ hyperlink พาเรนท์จะถูกเพิ่มเข้าในรายการ hyperlink ที่ดูแล้วเมื่อถูกเรียกใช้หรือไม่. สามารถอ่าน/เขียนได้ boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```

กำหนดว่า hyperlink ควรไฮไลท์เมื่อคลิกหรือไม่. สามารถอ่าน/เขียนได้ boolean.

**คืนค่า:**
boolean

### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```

กำหนดว่า hyperlink ควรไฮไลท์เมื่อคลิกหรือไม่. สามารถอ่าน/เขียนได้ boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```

กำหนดว่าเสียงควรหยุดเมื่อคลิก hyperlink หรือไม่. สามารถอ่าน/เขียนได้ boolean.

**คืนค่า:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

กำหนดว่าเสียงควรหยุดเมื่อคลิก hyperlink หรือไม่. สามารถอ่าน/เขียนได้ boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

แสดงถึงเสียงที่กำลังเล่นของ hyperlink. สามารถอ่าน/เขียนได้ [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // ดึง hyperlink ของรูปทรงแรก
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // ดึงเสียง hyperlink ออกเป็นอาร์เรย์ของไบต์
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

แสดงถึงเสียงที่กำลังเล่นของ hyperlink. สามารถอ่าน/เขียนได้ [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // ดึง hyperlink ของรูปทรงแรก
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // ดึงเสียง hyperlink ออกเป็นอาร์เรย์ของไบต์
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
public abstract int getColorSource()
```

แสดงถึงแหล่งที่มาของสี hyperlink - ทั้งสไตล์หรือรูปแบบส่วน. สามารถอ่าน/เขียนได้ [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**คืนค่า:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

แสดงถึงแหล่งที่มาของสี hyperlink - ทั้งสไตล์หรือรูปแบบส่วน. สามารถอ่าน/เขียนได้ [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```

กำหนดว่าตัวอย่าง Hyperlink สองตัวเท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink ที่ต้องการเปรียบเทียบกับ Hyperlink ปัจจุบัน |

**คืนค่า:**
boolean - **true** หาก Hyperlink ที่ระบุเท่ากับ Hyperlink ปัจจุบัน; มิฉะนั้น, **false**.