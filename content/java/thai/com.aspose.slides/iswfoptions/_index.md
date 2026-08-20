---
title: ISwfOptions
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ SWF.
type: docs
url: /th/com.aspose.slides/iswfoptions/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ SWF.

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getCompressed()](#getCompressed--) | ระบุว่าควรบีบอัดเอกสาร SWF ที่สร้างขึ้นหรือไม่. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | ระบุว่าควรบีบอัดเอกสาร SWF ที่สร้างขึ้นหรือไม่. |
| [getViewerIncluded()](#getViewerIncluded--) | ระบุว่าควรใส่ตัวดูเอกสารที่รวมไว้ในเอกสาร SWF ที่สร้างขึ้นหรือไม่. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | ระบุว่าควรใส่ตัวดูเอกสารที่รวมไว้ในเอกสาร SWF ที่สร้างขึ้นหรือไม่. |
| [getShowPageBorder()](#getShowPageBorder--) | ระบุว่าควรแสดงขอบรอบหน้าเอกสารหรือไม่. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | ระบุว่าควรแสดงขอบรอบหน้าเอกสารหรือไม่. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. |
| [getShowFullScreen()](#getShowFullScreen--) | แสดง/ซ่อนปุ่มเต็มหน้าจอ. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | แสดง/ซ่อนปุ่มเต็มหน้าจอ. |
| [getShowPageStepper()](#getShowPageStepper--) | แสดง/ซ่อนตัวควบคุมเดินหน้าหน้า. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | แสดง/ซ่อนตัวควบคุมเดินหน้าหน้า. |
| [getShowSearch()](#getShowSearch--) | แสดง/ซ่อนส่วนค้นหา. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | แสดง/ซ่อนส่วนค้นหา. |
| [getShowTopPane()](#getShowTopPane--) | แสดง/ซ่อนแถบบนทั้งหมด. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | แสดง/ซ่อนแถบบนทั้งหมด. |
| [getShowBottomPane()](#getShowBottomPane--) | แสดง/ซ่อนแถบล่าง. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | แสดง/ซ่อนแถบล่าง. |
| [getShowLeftPane()](#getShowLeftPane--) | แสดง/ซ่อนแถบด้านซ้าย. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | แสดง/ซ่อนแถบด้านซ้าย. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | เริ่มต้นด้วยแถบด้านซ้ายที่เปิดอยู่. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | เริ่มต้นด้วยแถบด้านซ้ายที่เปิดอยู่. |
| [getEnableContextMenu()](#getEnableContextMenu--) | เปิด/ปิดเมนูบริบท. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | เปิด/ปิดเมนูบริบท. |
| [getLogoImageBytes()](#getLogoImageBytes--) | รูปภาพที่จะแสดงเป็นโลโก้ที่มุมขวาบนของตัวดู. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | รูปภาพที่จะแสดงเป็นโลโก้ที่มุมขวาบนของตัวดู. |
| [getLogoLink()](#getLogoLink--) | รับหรือกำหนดที่อยู่ไฮเปอร์ลิงก์เต็มสำหรับโลโก้. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | รับหรือกำหนดที่อยู่ไฮเปอร์ลิงก์เต็มสำหรับโลโก้. |
| [getJpegQuality()](#getJpegQuality--) | ระบุคุณภาพของภาพ JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | ระบุคุณภาพของภาพ JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

ระบุว่าควรบีบอัดเอกสาร SWF ที่สร้างขึ้นหรือไม่. ค่าเริ่มต้นคือ true.

**คืนค่า:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

ระบุว่าควรบีบอัดเอกสาร SWF ที่สร้างขึ้นหรือไม่. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

ระบุว่าควรใส่ตัวดูเอกสารที่รวมไว้ในเอกสาร SWF ที่สร้างขึ้นหรือไม่. ค่าเริ่มต้นคือ true.

**คืนค่า:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

ระบุว่าควรใส่ตัวดูเอกสารที่รวมไว้ในเอกสาร SWF ที่สร้างขึ้นหรือไม่. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

ระบุว่าควรแสดงขอบรอบหน้าเอกสารหรือไม่. ค่าเริ่มต้นคือ true.

**คืนค่า:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

ระบุว่าควรแสดงขอบรอบหน้าเอกสารหรือไม่. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

ระบุว่าควรรวมสไลด์ที่ซ่อนอยู่ในเอกสารที่สร้างหรือไม่. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

แสดง/ซ่อนปุ่มเต็มหน้าจอ. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true.

**คืนค่า:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

แสดง/ซ่อนปุ่มเต็มหน้าจอ. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

แสดง/ซ่อนตัวควบคุมเดินหน้าหน้า. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true.

**คืนค่า:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

แสดง/ซ่อนตัวควบคุมเดินหน้าหน้า. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

แสดง/ซ่อนส่วนค้นหา. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true.

**คืนค่า:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

แสดง/ซ่อนส่วนค้นหา. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

แสดง/ซ่อนแถบบนทั้งหมด. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true.

**คืนค่า:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

แสดง/ซ่อนแถบบนทั้งหมด. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

แสดง/ซ่อนแถบล่าง. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true.

**คืนค่า:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

แสดง/ซ่อนแถบล่าง. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

แสดง/ซ่อนแถบด้านซ้าย. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true.

**คืนค่า:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

แสดง/ซ่อนแถบด้านซ้าย. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

เริ่มต้นด้วยแถบด้านซ้ายที่เปิดอยู่. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ false.

**คืนค่า:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

เริ่มต้นด้วยแถบด้านซ้ายที่เปิดอยู่. สามารถแทนที่ได้ใน flashvars. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

เปิด/ปิดเมนูบริบท. ค่าเริ่มต้นคือ true.

**คืนค่า:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

เปิด/ปิดเมนูบริบท. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

รูปภาพที่จะแสดงเป็นโลโก้ที่มุมขวาบนของตัวดู. ควรเป็นภาพ PNG ขนาด 32x64 พิกเซล มิฉะนั้นโลโก้อาจแสดงไม่ถูกต้อง.

**คืนค่า:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

รูปภาพที่จะแสดงเป็นโลโก้ที่มุมขวาบนของตัวดู. ควรเป็นภาพ PNG ขนาด 32x64 พิกเซล มิฉะนั้นโลโก้อาจแสดงไม่ถูกต้อง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

รับหรือกำหนดที่อยู่ไฮเปอร์ลิงก์เต็มสำหรับโลโก้. มีผลเฉพาะเมื่อกำหนด (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**คืนค่า:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

รับหรือกำหนดที่อยู่ไฮเปอร์ลิงก์เต็มสำหรับโลโก้. มีผลเฉพาะเมื่อกำหนด (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

ระบุคุณภาพของภาพ JPEG. ค่าเริ่มต้นคือ 95.

**คืนค่า:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

ระบุคุณภาพของภาพ JPEG. ค่าเริ่มต้นคือ 95.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). คุณสมบัตินี้ไม่รองรับการกำหนดอ็อบเจกต์ประเภท [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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

**คืนค่า:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)

### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

รับหรือกำหนดโหมดที่สไลด์ถูกจัดวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). คุณสมบัตินี้ไม่รองรับการกำหนดอ็อบเจกต์ประเภท [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |