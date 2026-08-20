---
title: IFonts
second_title: Aspose.Slides for Java API Reference
description: แสดงคอลเลกชันของแบบอักษร
type: docs
url: /th/com.aspose.slides/ifonts/
---```
public interface IFonts
```

แสดงคอลเลกชันของแบบอักษร
## Methods

| Method | Description |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | คืนหรือกำหนดฟอนต์ Latin |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | คืนหรือกำหนดฟอนต์ Latin |
| [getEastAsianFont()](#getEastAsianFont--) | คืนหรือกำหนดฟอนต์ East Asian |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | คืนหรือกำหนดฟอนต์ East Asian |
| [getComplexScriptFont()](#getComplexScriptFont--) | คืนหรือกำหนดฟอนต์ complex script |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | คืนหรือกำหนดฟอนต์ complex script |
| [getScriptFontMap()](#getScriptFontMap--) | คืนพจนานุกรมของการกำหนดฟอนต์สคริปต์ทั้งหมดในงานนำเสนอ |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | รับชื่อฟอนต์ที่เชื่อมโยงกับแท็กสคริปต์เฉพาะจากธีมของงานนำเสนอ |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | กำหนดชื่อฟอนต์ให้กับแท็กสคริปต์เฉพาะ เพื่อกำหนดวิธีการแสดงข้อความของสคริปต์นั้นในงานนำเสนอ |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | ลบการตั้งค่าฟอนต์ที่เชื่อมโยงกับแท็กสคริปต์เฉพาะจากคอลเลกชันฟอนต์ของธีม |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

คืนหรือกำหนดฟอนต์ Latin. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

คืนหรือกำหนดฟอนต์ Latin. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

คืนหรือกำหนดฟอนต์ East Asian. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

คืนหรือกำหนดฟอนต์ East Asian. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

คืนหรือกำหนดฟอนต์ complex script. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

คืนหรือกำหนดฟอนต์ complex script. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
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


**คืนค่า:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - พจนานุกรมที่แมปโค้ดสคริปต์กับชื่อฟอนต์
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

รับชื่อฟอนต์ที่เชื่อมโยงกับแท็กสคริปต์เฉพาะจากธีมของงานนำเสนอ.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | รหัสสคริปต์ BCP-47 (เช่น "Latn", "Cyrl", "Jpan") ที่ใช้ระบุระบบการเขียน |

**คืนค่า:**
java.lang.String - ชื่อฟอนต์ที่ใช้สำหรับสคริปต์ที่ระบุ, หรือ null หากสคริปต์ไม่ได้กำหนด
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```

กำหนดชื่อฟอนต์ให้กับแท็กสคริปต์เฉพาะ เพื่อกำหนดวิธีการแสดงข้อความของสคริปต์นั้นในงานนำเสนอ.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | รหัสสคริปต์ BCP-47 (เช่น "Arab", "Hebr", "Hans") ที่ระบุระบบการเขียน |
| fontName | java.lang.String | ชื่อฟอนต์ที่จะกำหนดให้กับสคริปต์ที่ระบุ |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

ลบการตั้งค่าฟอนต์ที่เชื่อมโยงกับแท็กสคริปต์เฉพาะจากคอลเลกชันฟอนต์ของธีม.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| script | java.lang.String | รหัสสคริปต์ BCP-47 ที่ต้องการลบการตั้งค่าฟอนต์ออกจากธีม |