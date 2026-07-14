---
title: Fonts
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: คอลเลกชันฟอนต์.
type: docs
url: /th/com.aspose.slides/fonts/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

คอลเลกชันฟอนต์.
## วิธีการ

| Method | Description |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | คืนพจนานุกรมของการกำหนดฟอนต์สคริปต์ทั้งหมดในงานนำเสนอ. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | ดึงชื่อฟอนต์ที่เกี่ยวข้องกับแท็กสคริปต์เฉพาะจากธีมของงานนำเสนอ. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | กำหนดชื่อฟอนต์ให้กับแท็กสคริปต์เฉพาะ ซึ่งกำหนดวิธีการแสดงข้อความของสคริปต์นั้นในงานนำเสนอ. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | ลบการตั้งค่าฟอนต์ที่เกี่ยวข้องกับแท็กสคริปต์เฉพาะออกจากคอลเลกชันฟอนต์ของธีม. |
| [getLatinFont()](#getLatinFont--) | คืนหรือกำหนดฟอนต์แบบละติน. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | คืนหรือกำหนดฟอนต์แบบละติน. |
| [getEastAsianFont()](#getEastAsianFont--) | คืนหรือกำหนดฟอนต์เอเชียตะวันออก. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | คืนหรือกำหนดฟอนต์เอเชียตะวันออก. |
| [getComplexScriptFont()](#getComplexScriptFont--) | คืนหรือกำหนดฟอนต์สคริปต์ซับซ้อน. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | คืนหรือกำหนดฟอนต์สคริปต์ซับซ้อน. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

คืนพจนานุกรมของการกำหนดฟอนต์สคริปต์ทั้งหมดในงานนำเสนอ.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**ผลลัพธ์:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - พจนานุกรมที่แมพโค้ดสคริปต์ไปยังชื่อฟอนต์.

### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

ดึงชื่อฟอนต์ที่เกี่ยวข้องกับแท็กสคริปต์เฉพาะจากธีมของงานนำเสนอ.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| script | java.lang.String | โค้ดสคริปต์ BCP-47 (เช่น "Latn", "Cyrl", "Jpan") ที่ใช้ระบุระบบการเขียน. |

**ผลลัพธ์:**
java.lang.String - ชื่อฟอนต์ที่ใช้สำหรับสคริปต์ที่ระบุ, หรือ  null  หากสคริปต์ไม่ได้กำหนดไว้.

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

กำหนดชื่อฟอนต์ให้กับแท็กสคริปต์เฉพาะ ซึ่งกำหนดวิธีการแสดงข้อความของสคริปต์นั้นในงานนำเสนอ.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| script | java.lang.String | โค้ดสคริปต์ BCP-47 (เช่น "Arab", "Hebr", "Hans") ระบุระบบการเขียน. |
| fontName | java.lang.String | ชื่อฟอนต์ที่จะกำหนดให้สคริปต์ที่ระบุ. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

ลบการตั้งค่าฟอนต์ที่เกี่ยวข้องกับแท็กสคริปต์เฉพาะออกจากคอลเลกชันฟอนต์ของธีม.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| script | java.lang.String | โค้ดสคริปต์ BCP-47 ที่ต้องการลบการตั้งค่าฟอนต์. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

คืนหรือกำหนดฟอนต์แบบละติน. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**ผลลัพธ์:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

คืนหรือกำหนดฟอนต์แบบละติน. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

คืนหรือกำหนดฟอนต์เอเชียตะวันออก. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**ผลลัพธ์:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

คืนหรือกำหนดฟอนต์เอเชียตะวันออก. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

คืนหรือกำหนดฟอนต์สคริปต์ซับซ้อน. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**ผลลัพธ์:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

คืนหรือกำหนดฟอนต์สคริปต์ซับซ้อน. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |