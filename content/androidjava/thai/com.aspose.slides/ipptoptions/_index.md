---
title: IPptOptions
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ให้ตัวเลือกที่ควบคุมวิธีการบันทึกงานนำเสนอในรูปแบบ PPT.
type: docs
url: /th/com.aspose.slides/ipptoptions/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptOptions extends ISaveOptions
```

ให้ตัวเลือกที่ควบคุมการบันทึกงานนำเสนอในรูปแบบ PPT.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getRootDirectoryClsid()](#getRootDirectoryClsid--) | แสดงคลาสอ็อบเจกต์ GUID (CLSID) ที่จัดเก็บในรายการไดเรกทอรีราก. |
| [setRootDirectoryClsid(UUID value)](#setRootDirectoryClsid-java.util.UUID-) | แสดงคลาสอ็อบเจกต์ GUID (CLSID) ที่จัดเก็บในรายการไดเรกทอรีราก. |
### getRootDirectoryClsid() {#getRootDirectoryClsid--}
```
public abstract UUID getRootDirectoryClsid()
```


แสดงคลาสอ็อบเจกต์ GUID (CLSID) ที่จัดเก็บในรายการไดเรกทอรีราก. สามารถใช้สำหรับการเปิดใช้งาน COM ของแอปพลิเคชันเอกสาร. ค่าปริยายคือ '64818D11-4F9B-11CF-86EA-00AA00B929E8' ซึ่งสอดคล้องกับ 'Microsoft Powerpoint.Slide.8'.

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
public abstract void setRootDirectoryClsid(UUID value)
```


แสดงคลาสอ็อบเจกต์ GUID (CLSID) ที่จัดเก็บในรายการไดเรกทอรีราก. สามารถใช้สำหรับการเปิดใช้งาน COM ของแอปพลิเคชันเอกสาร. ค่าปริยายคือ '64818D11-4F9B-11CF-86EA-00AA00B929E8' ซึ่งสอดคล้องกับ 'Microsoft Powerpoint.Slide.8'.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.util.UUID |  |