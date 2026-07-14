---
title: SwfOptions
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ Swf
type: docs
url: /th/com.aspose.slides/swfoptions/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ Swf

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // สร้างอ็อบเจกต์ Presentation ที่แทนไฟล์งานนำเสนอ
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // บันทึกงานนำเสนอและหน้าบันทึกหมายเหตุ
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | คอนสตรัคเตอร์เริ่มต้น. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. |
| [getCompressed()](#getCompressed--) | ระบุว่าเอกสาร SWF ที่สร้างควรถูกบีบอัดหรือไม่. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | ระบุว่าเอกสาร SWF ที่สร้างควรถูกบีบอัดหรือไม่. |
| [getViewerIncluded()](#getViewerIncluded--) | ระบุว่าเอกสาร SWF ที่สร้างควรรวมผู้ดูเอกสารแบบบูรณาการหรือไม่. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | ระบุว่าเอกสาร SWF ที่สร้างควรรวมผู้ดูเอกสารแบบบูรณาการหรือไม่. |
| [getShowPageBorder()](#getShowPageBorder--) | ระบุว่าขอบรอบหน้าควรแสดงหรือไม่. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | ระบุว่าขอบรอบหน้าควรแสดงหรือไม่. |
| [getShowFullScreen()](#getShowFullScreen--) | แสดง/ซ่อนปุ่มเต็มจอ. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | แสดง/ซ่อนปุ่มเต็มจอ. |
| [getShowPageStepper()](#getShowPageStepper--) | แสดง/ซ่อนตัวควบคุมหน้าของสไลด์. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | แสดง/ซ่อนตัวควบคุมหน้าของสไลด์. |
| [getShowSearch()](#getShowSearch--) | แสดง/ซ่อนส่วนการค้นหา. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | แสดง/ซ่อนส่วนการค้นหา. |
| [getShowTopPane()](#getShowTopPane--) | แสดง/ซ่อนแผงบนทั้งหมด. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | แสดง/ซ่อนแผงบนทั้งหมด. |
| [getShowBottomPane()](#getShowBottomPane--) | แสดง/ซ่อนแผงล่าง. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | แสดง/ซ่อนแผงล่าง. |
| [getShowLeftPane()](#getShowLeftPane--) | แสดง/ซ่อนแผงซ้าย. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | แสดง/ซ่อนแผงซ้าย. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | เริ่มต้นด้วยแผงซ้ายที่เปิดอยู่. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | เริ่มต้นด้วยแผงซ้ายที่เปิดอยู่. |
| [getEnableContextMenu()](#getEnableContextMenu--) | เปิด/ปิดเมนูบริบท. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | เปิด/ปิดเมนูบริบท. |
| [getLogoImageBytes()](#getLogoImageBytes--) | รูปภาพที่จะถูกแสดงเป็นโลโก้ที่มุมบนขวาของผู้ดู. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | รูปภาพที่จะถูกแสดงเป็นโลโก้ที่มุมบนขวาของผู้ดู. |
| [getLogoLink()](#getLogoLink--) | รับหรือกำหนดที่อยู่การเชื่อมโยงเต็มสำหรับโลโก้. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | รับหรือกำหนดที่อยู่การเชื่อมโยงเต็มสำหรับโลโก้. |
| [getJpegQuality()](#getJpegQuality--) | ระบุคุณภาพของภาพ JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | ระบุคุณภาพของภาพ JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```


คอนสตรัคเตอร์เริ่มต้น.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. ค่าเริ่มต้นคือ false.

**ผลลัพธ์:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


ระบุว่าเอกสารที่สร้างควรรวมสไลด์ที่ซ่อนอยู่หรือไม่. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```


ระบุว่าเอกสาร SWF ที่สร้างควรถูกบีบอัดหรือไม่. ค่าเริ่มต้นคือ true.

**ผลลัพธ์:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```


ระบุว่าเอกสาร SWF ที่สร้างควรถูกบีบอัดหรือไม่. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```


ระบุว่าเอกสาร SWF ที่สร้างควรรวมผู้ดูเอกสารแบบบูรณาการหรือไม่. ค่าเริ่มต้นคือ true.

**ผลลัพธ์:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```


ระบุว่าเอกสาร SWF ที่สร้างควรรวมผู้ดูเอกสารแบบบูรณาการหรือไม่. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```


ระบุว่าขอบรอบหน้าควรแสดงหรือไม่. ค่าเริ่มต้นคือ true.

**ผลลัพธ์:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```


ระบุว่าขอบรอบหน้าควรแสดงหรือไม่. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```


แสดง/ซ่อนปุ่มเต็มจอ. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ true.

**ผลลัพธ์:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```


แสดง/ซ่อนปุ่มเต็มจอ. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```


แสดง/ซ่อนตัวควบคุมหน้าของสไลด์. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ true.

**ผลลัพธ์:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```


แสดง/ซ่อนตัวควบคุมหน้าของสไลด์. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```


แสดง/ซ่อนส่วนการค้นหา. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ true.

**ผลลัพธ์:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```


แสดง/ซ่อนส่วนการค้นหา. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```


แสดง/ซ่อนแผงบนทั้งหมด. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ true.

**ผลลัพธ์:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```


แสดง/ซ่อนแผงบนทั้งหมด. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```


แสดง/ซ่อนแผงล่าง. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ true.

**ผลลัพธ์:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```


แสดง/ซ่อนแผงล่าง. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```


แสดง/ซ่อนแผงซ้าย. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ true.

**ผลลัพธ์:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```


แสดง/ซ่อนแผงซ้าย. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```


เริ่มต้นด้วยแผงซ้ายที่เปิดอยู่. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ false.

**ผลลัพธ์:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```


เริ่มต้นด้วยแผงซ้ายที่เปิดอยู่. สามารถกำหนดทับด้วย flashvars. ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```


เปิด/ปิดเมนูบริบท. ค่าเริ่มต้นคือ true.

**ผลลัพธ์:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```


เปิด/ปิดเมนูบริบท. ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```


รูปภาพที่จะถูกแสดงเป็นโลโก้ที่มุมบนขวาของผู้ดู. ควรเป็นภาพ PNG ขนาด 32x64 พิกเซล, มิฉะนั้นโลโก้อาจแสดงไม่ถูกต้อง.

**ผลลัพธ์:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```


รูปภาพที่จะถูกแสดงเป็นโลโก้ที่มุมบนขวาของผู้ดู. ควรเป็นภาพ PNG ขนาด 32x64 พิกเซล, มิฉะนั้นโลโก้อาจแสดงไม่ถูกต้อง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```


รับหรือกำหนดที่อยู่การเชื่อมโยงเต็มสำหรับโลโก้. มีผลก็ต่อเมื่อมีการระบุ (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**ผลลัพธ์:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```


รับหรือกำหนดที่อยู่การเชื่อมโยงเต็มสำหรับโลโก้. มีผลก็ต่อเมื่อมีการระบุ (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```


ระบุคุณภาพของภาพ JPEG. ค่าเริ่มต้นคือ 95.

**ผลลัพธ์:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```


ระบุคุณภาพของภาพ JPEG. ค่าเริ่มต้นคือ 95.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). คุณสมบัตินี้ไม่รองรับการกำหนดอ็อบเจกต์ของประเภท [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> ตัวอย่าง:
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

**ผลลัพธ์:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


รับหรือกำหนดโหมดที่สไลด์ถูกวางบนหน้าเมื่อส่งออกงานนำเสนอ [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). คุณสมบัตินี้ไม่รองรับการกำหนดอ็อบเจกต์ของประเภท [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

--------------------

> ```
> ตัวอย่าง:
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