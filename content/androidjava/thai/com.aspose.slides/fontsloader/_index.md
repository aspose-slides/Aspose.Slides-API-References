---
title: FontsLoader
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: คลาสสำหรับโหลดแบบอักษรที่กำหนดโดยผู้ใช้.
type: docs
url: /th/com.aspose.slides/fontsloader/
---
**การสืบทอด:**
java.lang.Object

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

คลาสสำหรับโหลดแบบอักษรที่กำหนดโดยผู้ใช้ ควรใช้ก่อนสร้างอ็อบเจ็กต์การนำเสนอใดๆ
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | เพิ่มโฟลเดอร์เพิ่มเติมเพื่อค้นหาแบบอักษร |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | เพิ่มแบบอักษรจากข้อมูลไบต์ |
| [getFontFolders()](#getFontFolders--) | รับโฟลเดอร์แบบอักษร |
| [clearCache()](#clearCache--) | ปลดปล่อยแบบอักษรที่กำหนดโดยผู้ใช้ทั้งหมด |
### loadExternalFonts(String[] directories) {#loadExternalFonts-java.lang.String---}
```
public static void loadExternalFonts(String[] directories)
```


เพิ่มโฟลเดอร์เพิ่มเติมเพื่อค้นหาแบบอักษร

--------------------

> ```
> The follow examples shows how to load custom fonts from .TTF
>  
>  String dataDir = "C:/Fonts";
>  // โฟลเดอร์เพื่อค้นหาแบบอักษร
>  String[] folders = new String[] { dataDir };
>  // โหลดแบบอักษรจากโฟลเดอร์ที่กำหนด
>  FontsLoader.loadExternalFonts(folders);
>  // ทำงานบางอย่างและเรนเดอร์การนำเสนอ/สไลด์
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // ลบแคชแบบอักษร
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| directories | java.lang.String[] | ไดเรกทอรีเพื่ออ่านแบบอักษรเพิ่มเติม |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```


เพิ่มแบบอักษรจากข้อมูลไบต์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | byte[] | ข้อมูลแบบอักษร |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```


รับโฟลเดอร์แบบอักษร

**ผลลัพธ์:**
java.lang.String[] - array containing folder names
### clearCache() {#clearCache--}
```
public static void clearCache()
```


ปลดปล่อยแบบอักษรที่กำหนดโดยผู้ใช้ทั้งหมด

--------------------

เมธอดนี้ต้องล้างแคชของแบบอักษรที่กำหนดโดยผู้ใช้.