---
title: IFonts
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API อ้างอิง
description: แสดงคอลเลกชันแบบอักษร.
type: docs
url: /th/com.aspose.slides/ifonts/
---```
public interface IFonts
```

แสดงคอลเลกชันแบบอักษร.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | คืนค่า หรือกำหนดแบบอักษรละติน. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดแบบอักษรละติน. |
| [getEastAsianFont()](#getEastAsianFont--) | คืนค่า หรือกำหนดแบบอักษรเอเชียตะวันออก. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดแบบอักษรเอเชียตะวันออก. |
| [getComplexScriptFont()](#getComplexScriptFont--) | คืนค่า หรือกำหนดแบบอักษรสคริปต์ซับซ้อน. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดแบบอักษรสคริปต์ซับซ้อน. |
| [getScriptFontMap()](#getScriptFontMap--) | คืนค่าพจนานุกรมของการกำหนดแบบอักษรสคริปต์ทั้งหมดในงานนำเสนอ. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | ดึงชื่อแบบอักษรที่เชื่อมโยงกับแท็กสคริปต์เฉพาะจากธีมงานนำเสนอ. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | กำหนดชื่อแบบอักษรให้กับแท็กสคริปต์เฉพาะ ซึ่งกำหนดวิธีการแสดงข้อความของสคริปต์นั้นในงานนำเสนอ. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | ลบการตั้งค่าแบบอักษรที่เชื่อมโยงกับแท็กสคริปต์เฉพาะออกจากคอลเลกชันแบบอักษรของธีม. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

คืนค่า หรือกำหนดแบบอักษรละติน. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

คืนค่า หรือกำหนดแบบอักษรละติน. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

คืนค่า หรือกำหนดแบบอักษรเอเชียตะวันออก. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

คืนค่า หรือกำหนดแบบอักษรเอเชียตะวันออก. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

คืนค่า หรือกำหนดแบบอักษรสคริปต์ซับซ้อน. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

คืนค่า หรือกำหนดแบบอักษรสคริปต์ซับซ้อน. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |
### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

คืนค่าพจนานุกรมของการกำหนดแบบอักษรสคริปต์ทั้งหมดในงานนำเสนอ.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**คืนค่า:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - พจนานุกรมที่แมปโค้ดสคริปต์ไปยังชื่อแบบอักษร.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

ดึงชื่อแบบอักษรที่เชื่อมโยงกับแท็กสคริปต์เฉพาะจากธีมงานนำเสนอ.

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
| script | java.lang.String | โค้ดสคริปต์ตามมาตรฐาน BCP-47 (เช่น "Latn", "Cyrl", "Jpan") ใช้ระบุระบบการเขียน. |

**คืนค่า:**
java.lang.String - ชื่อแบบอักษรที่ใช้สำหรับสคริปต์ที่ระบุ, หรือ  null  หากสคริปต์นั้นไม่ได้กำหนด.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

กำหนดชื่อแบบอักษรให้กับแท็กสคริปต์เฉพาะ ซึ่งกำหนดวิธีการแสดงข้อความของสคริปต์นั้นในงานนำเสนอ.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| script | java.lang.String | โค้ดสคริปต์ตามมาตรฐาน BCP-47 (เช่น "Arab", "Hebr", "Hans") ระบุระบบการเขียน. |
| fontName | java.lang.String | ชื่อแบบอักษรที่จะกำหนดให้สคริปต์ที่ระบุ. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

ลบการตั้งค่าแบบอักษรที่เชื่อมโยงกับแท็กสคริปต์เฉพาะออกจากคอลเลกชันแบบอักษรของธีม.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| script | java.lang.String | โค้ดสคริปต์ตามมาตรฐาน BCP-47 ที่ต้องการลบการตั้งค่าแบบอักษร. |