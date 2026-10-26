---
title: SwfOptions
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ Swf
type: docs
url: /th/com.aspose.slides/swfoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอเป็นรูปแบบ Swf

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // สร้างออบเจ็กต์ Presentation ที่แทนไฟล์การนำเสนอ
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // บันทึกการนำเสนอและหน้าบันทึกย่อ
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | ตัวสร้างเริ่มต้น |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ |
| [getCompressed()](#getCompressed--) | ระบุว่าเอกสาร SWF ที่สร้างควรบีบอัดหรือไม่ |
| [setCompressed(boolean value)](#setCompressed-boolean-) | ระบุว่าเอกสาร SWF ที่สร้างควรบีบอัดหรือไม่ |
| [getViewerIncluded()](#getViewerIncluded--) | ระบุว่าเอกสาร SWF ที่สร้างควรมีตัวแสดงเอกสารแบบบูรณาการหรือไม่ |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | ระบุว่าเอกสาร SWF ที่สร้างควรมีตัวแสดงเอกสารแบบบูรณาการหรือไม่ |
| [getShowPageBorder()](#getShowPageBorder--) | ระบุว่าควรแสดงขอบรอบหน้าหรือไม่ |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | ระบุว่าควรแสดงขอบรอบหน้า או לא |
| [getShowFullScreen()](#getShowFullScreen--) | แสดง/ซ่อนปุ่มเต็มหน้าจอ |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | แสดง/ซ่อนปุ่มเต็มหน้าจอ |
| [getShowPageStepper()](#getShowPageStepper--) | แสดง/ซ่อนตัวเปลี่ยนหน้ากระดาษ |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | แสดง/ซ่อนตัวเปลี่ยนหน้ากระดาษ |
| [getShowSearch()](#getShowSearch--) | แสดง/ซ่อนส่วนค้นหา |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | แสดง/ซ่อนส่วนค้นหา |
| [getShowTopPane()](#getShowTopPane--) | แสดง/ซ่อนแถบด้านบนทั้งหมด |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | แสดง/ซ่อนแถบด้านบนทั้งหมด |
| [getShowBottomPane()](#getShowBottomPane--) | แสดง/ซ่อนแถบด้านล่าง |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | แสดง/ซ่อนแถบด้านล่าง |
| [getShowLeftPane()](#getShowLeftPane--) | แสดง/ซ่อนแถบด้านซ้าย |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | แสดง/ซ่อนแถบด้านซ้าย |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | เริ่มต้นด้วยแถบด้านซ้ายที่เปิดอยู่ |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | เริ่มต้นด้วยแถบด้านซ้ายที่เปิดอยู่ |
| [getEnableContextMenu()](#getEnableContextMenu--) | เปิด/ปิดเมนูบริบท |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | เปิด/ปิดเมนูบริบท |
| [getLogoImageBytes()](#getLogoImageBytes--) | รูปภาพที่จะใช้เป็นโลโก้ที่มุมขวาบนของตัวดู |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | รูปภาพที่จะใช้เป็นโลโก้ที่มุมขวาบนของตัวดู |
| [getLogoLink()](#getLogoLink--) | รับหรือกำหนดที่อยู่ URL เต็มของโลโก้ |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | รับหรือกำหนดที่อยู่ URL เต็มของโลโก้ |
| [getJpegQuality()](#getJpegQuality--) | ระบุคุณภาพของภาพ JPEG |
| [setJpegQuality(int value)](#setJpegQuality-int-) | ระบุคุณภาพของภาพ JPEG |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์วางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์วางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |

### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

ตัวสร้างเริ่มต้น

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ ค่าเริ่มต้นคือ false

**ค่าที่ส่งคืน:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่ ค่าเริ่มต้นคือ false

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

ระบุว่าเอกสาร SWF ที่สร้างควรบีบอัดหรือไม่ ค่าเริ่มต้นคือ true

**ค่าที่ส่งคืน:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

ระบุว่าเอกสาร SWF ที่สร้างควรบีบอัดหรือไม่ ค่าเริ่มต้นคือ true

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

ระบุว่าเอกสาร SWF ที่สร้างควรมีตัวแสดงเอกสารแบบบูรณาการหรือไม่ ค่าเริ่มต้นคือ true

**ค่าที่ส่งคืน:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

ระบุว่าเอกสาร SWF ที่สร้างควรมีตัวแสดงเอกสารแบบบูรณาการหรือไม่ ค่าเริ่มต้นคือ true

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

ระบุว่าควรแสดงขอบรอบหน้าไหม ค่าเริ่มต้นคือ true

**ค่าที่ส่งคืน:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

ระบุว่าควรแสดงขอบรอบหน้าไหม ค่าเริ่มต้นคือ true

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

แสดง/ซ่อนปุ่มเต็มหน้าจอ สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ true

**ค่าที่ส่งคืน:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

แสดง/ซ่อนปุ่มเต็มหน้าจอ สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ true

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

แสดง/ซ่อนตัวเปลี่ยนหน้ากระดาษ สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ true

**ค่าที่ส่งคืน:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

แสดง/ซ่อนตัวเปลี่ยนหน้ากระดาษ สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ true

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

แสดง/ซ่อนส่วนค้นหา สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ true

**ค่าที่ส่งคืน:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

แสดง/ซ่อนส่วนค้นหา สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ true

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

แสดง/ซ่อนแถบด้านบนทั้งหมด สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ true

**ค่าที่ส่งคืน:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

แสดง/ซ่อนแถบด้านบนทั้งหมด สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ true

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

แสดง/ซ่อนแถบด้านล่าง สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ true

**ค่าที่ส่งคืน:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

แสดง/ซ่อนแถบด้านล่าง สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ true

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

แสดง/ซ่อนแถบด้านซ้าย สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ true

**ค่าที่ส่งคืน:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

แสดง/ซ่อนแถบด้านซ้าย สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ true

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

เริ่มต้นด้วยแถบด้านซ้ายที่เปิดอยู่ สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ false

**ค่าที่ส่งคืน:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

เริ่มต้นด้วยแถบด้านซ้ายที่เปิดอยู่ สามารถเขียนทับใน flashvars ได้ ค่าเริ่มต้นคือ false

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

เปิด/ปิดเมนูบริบท ค่าเริ่มต้นคือ true

**ค่าที่ส่งคืน:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

เปิด/ปิดเมนูบริบท ค่าเริ่มต้นคือ true

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

รูปภาพที่จะใช้เป็นโลโก้ที่มุมขวาบนของตัวดู ควรเป็นภาพ PNG ขนาด 32x64 พิกเซล หากไม่เป็นอาจทำให้โลโก้แสดงไม่ถูกต้อง

**ค่าที่ส่งคืน:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

รูปภาพที่จะใช้เป็นโลโก้ที่มุมขวาบนของตัวดู ควรเป็นภาพ PNG ขนาด 32x64 พิกเซล หากไม่เป็นอาจทำให้โลโก้แสดงไม่ถูกต้อง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

รับหรือกำหนดที่อยู่ URL เต็มของโลโก้ มีผลก็ต่อเมื่อมี (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) ระบุ

**ค่าที่ส่งคืน:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

รับหรือกำหนดที่อยู่ URL เต็มของโลโก้ มีผลก็ต่อเมื่อมี (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) ระบุ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

ระบุคุณภาพของภาพ JPEG ค่าเริ่มต้นคือ 95

**ค่าที่ส่งคืน:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

ระบุคุณภาพของภาพ JPEG ค่าเริ่มต้นคือ 95

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดที่สไลด์วางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) คุณสมบัตินี้ไม่รองรับการกำหนดออบเจ็กต์ประเภท [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ค่าที่ส่งคืน:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

รับหรือกำหนดโหมดที่สไลด์วางบนหน้าเมื่อส่งออกการนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) คุณสมบัตินี้ไม่รองรับการกำหนดออบเจ็กต์ประเภท [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |