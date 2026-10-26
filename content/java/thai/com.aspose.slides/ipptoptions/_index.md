---
title: IPptOptions
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ PPT.
type: docs
url: /th/com.aspose.slides/ipptoptions/
---
**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

ให้ตัวเลือกที่ควบคุมวิธีการบันทึกการนำเสนอในรูปแบบ PPT
## Methods

| Method | Description |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | แสดงถึง GUID ของคลาสอ็อบเจกต์ (CLSID) ที่เก็บไว้ในรายการไดเรกทอรีราก |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | แสดงถึง GUID ของคลาสอ็อบเจกต์ (CLSID) ที่เก็บไว้ในรายการไดเรกทอรีราก |

### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```

แสดงถึง GUID ของคลาสอ็อบเจกต์ (CLSID) ที่เก็บไว้ในรายการไดเรกทอรีราก สามารถใช้สำหรับการเปิดใช้งาน COM ของแอปพลิเคชันเอกสาร ค่าเริ่มต้นคือ '64818D11-4F9B-11CF-86EA-00AA00B929E8' ซึ่งสอดคล้องกับ 'Microsoft Powerpoint.Slide.8'

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

**ส่งคืน:**
java.util.UUID

### setRootDirectoryClsid(UUID value) {#setRootDirectoryClsid-java.util.UUID-}
```
public abstract void setRootDirectoryClsid(UUID value)
```

แสดงถึง GUID ของคลาสอ็อบเจกต์ (CLSID) ที่เก็บไว้ในรายการไดเรกทอรีราก สามารถใช้สำหรับการเปิดใช้งาน COM ของแอปพลิเคชันเอกสาร ค่าเริ่มต้นคือ '64818D11-4F9B-11CF-86EA-00AA00B929E8' ซึ่งสอดคล้องกับ 'Microsoft Powerpoint.Slide.8'

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |