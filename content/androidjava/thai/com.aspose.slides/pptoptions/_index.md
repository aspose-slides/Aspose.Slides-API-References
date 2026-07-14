---
title: PptOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ PPT.
type: docs
url: /th/com.aspose.slides/pptoptions/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IPptOptions](../../com.aspose.slides/ipptoptions), java.lang.Cloneable
```
public class PptOptions extends SaveOptions implements IPptOptions, Cloneable
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ PPT

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [PptOptions()](#PptOptions--) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | แสดงถึง GUID (CLSID) ของคลาสวัตถุที่จัดเก็บไว้ในรายการไดเรกทอรีราก |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | แสดงถึง GUID (CLSID) ของคลาสวัตถุที่จัดเก็บไว้ในรายการไดเรกทอรีราก |

### PptOptions() {#PptOptions--}
```
public PptOptions()
```

### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public final UUID getRootDirectoryClsid()
```

แสดงถึง GUID (CLSID) ของคลาสวัตถุที่จัดเก็บไว้ในรายการไดเรกทอรีราก ใช้สำหรับการเปิดใช้งาน COM ของแอปพลิเคชันเอกสาร ค่าเริ่มต้นคือ '64818D11-4F9B-11CF-86EA-00AA00B929E8' ซึ่งสอดคล้องกับ 'Microsoft Powerpoint.Slide.8'

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// ตั้งค่า CLSID เป็น 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**คืนค่า:**
java.util.UUID

### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public final void setRootDirectoryClsid(UUID value)
```

แสดงถึง GUID (CLSID) ของคลาสวัตถุที่จัดเก็บไว้ในรายการไดเรกทอรีราก ใช้สำหรับการเปิดใช้งาน COM ของแอปพลิเคชันเอกสาร ค่าเริ่มต้นคือ '64818D11-4F9B-11CF-86EA-00AA00B929E8' ซึ่งสอดคล้องกับ 'Microsoft Powerpoint.Slide.8'

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      PptOptions pptOptions = new PptOptions();
> 
>      /// ตั้งค่า CLSID เป็น 'Microsoft Powerpoint.Show.8'
>      pptOptions.setRootDirectoryClsid(UUID.fromString("64818D10-4F9B-11CF-86EA-00AA00B929E8"));
> 
>      pres.save("pres.ppt", SaveFormat.Ppt, pptOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | java.util.UUID |  |