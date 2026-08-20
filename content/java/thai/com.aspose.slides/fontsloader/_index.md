---
title: FontsLoader
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: คลาสสำหรับโหลดฟอนต์ที่กำหนดโดยผู้ใช้.
type: docs
url: /th/com.aspose.slides/fontsloader/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IFontsLoader](../../com.aspose.slides/ifontsloader)
```
public final class FontsLoader implements IFontsLoader
```

คลาสสำหรับโหลดฟอนต์ที่กำหนดโดยผู้ใช้ ควรใช้ก่อนการสร้างออบเจ็กต์การนำเสนอใด ๆ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [loadExternalFonts(String[] directories)](#loadExternalFonts-java.lang.String---) | Adds additional folders to seek fonts. |
| [loadExternalFont(byte[] data)](#loadExternalFont-byte---) | Adds font from the binary data |
| [getFontFolders()](#getFontFolders--) | Gets font folders. |
| [clearCache()](#clearCache--) | Releases all custom fonts defined by user |
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
>  // โฟลเดอร์สำหรับค้นหาแบบอักษร
>  String[] folders = new String[] { dataDir };
>  // โหลดโฟลเดอร์แบบอักษรที่กำหนดเอง
>  FontsLoader.loadExternalFonts(folders);
>  // ทำงานบางส่วนและทำการเรนเดอร์การนำเสนอ/สไลด์
>  Presentation pres = new Presentation("DefaultFonts.pptx");
>  try {
>      pres.save("NewFonts_out.pptx", SaveFormat.Pptx);
>      // ล้างแคชแบบอักษร
>      FontsLoader.clearCache();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| directories | java.lang.String[] | ไดเรกทอรีสำหรับอ่านฟอนต์เพิ่มเติม |

### loadExternalFont(byte[] data) {#loadExternalFont-byte---}
```
public static void loadExternalFont(byte[] data)
```

เพิ่มฟอนต์จากข้อมูลไบนารี

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | byte[] | ข้อมูลฟอนต์ |

### getFontFolders() {#getFontFolders--}
```
public static String[] getFontFolders()
```

รับโฟลเดอร์ฟอนต์ คืนค่าโฟลเดอร์ที่ถูกเพิ่มด้วยเมธอด LoadExternalFonts รวมถึงโฟลเดอร์ฟอนต์ของระบบ

**ค่าที่ส่งคืน:**
java.lang.String[] - อาร์เรย์ที่บรรจุชื่อโฟลเดอร์
### clearCache() {#clearCache--}
```
public static void clearCache()
```

ปล่อยฟอนต์ที่กำหนดโดยผู้ใช้ทั้งหมด

--------------------

เมธอดนี้ต้องล้างแคชของฟอนต์ที่กำหนดโดยผู้ใช้.