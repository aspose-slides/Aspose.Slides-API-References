---
title: Fonts
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: คอลเลกชันแบบอักษร.
type: docs
url: /th/com.aspose.slides/fonts/
---
**Inheritance:**  
การสืบทอด:  
java.lang.Object

**All Implemented Interfaces:**  
ทุกอินเทอร์เฟสที่ทำการ Implement ทั้งหมด:  
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)  
```
public class Fonts implements IFonts
```

คอลเลกชันแบบอักษร.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | คืนค่า dictionary ของการกำหนดฟอนต์สคริปต์ทั้งหมดในงานนำเสนอ. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | ดึงชื่อฟอนต์ที่เชื่อมโยงกับแท็กสคริปต์เฉพาะจากธีมของงานนำเสนอ. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | กำหนดชื่อฟอนต์ให้กับแท็กสคริปต์เฉพาะ ซึ่งจะกำหนดวิธีการแสดงผลข้อความของสคริปต์นั้นในงานนำเสนอ. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | ลบการตั้งค่าฟอนต์ที่เชื่อมโยงกับแท็กสคริปต์เฉพาะออกจากคอลเลกชันฟอนต์ของธีม. |
| [getLatinFont()](#getLatinFont--) | คืนค่า หรือกำหนดฟอนต์ Latin. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดฟอนต์ Latin. |
| [getEastAsianFont()](#getEastAsianFont--) | คืนค่า หรือกำหนดฟอนต์ East Asian. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดฟอนต์ East Asian. |
| [getComplexScriptFont()](#getComplexScriptFont--) | คืนค่า หรือกำหนดฟอนต์ complex script. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | คืนค่า หรือกำหนดฟอนต์ complex script. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

คืนค่า dictionary ของการกำหนดฟอนต์สคริปต์ทั้งหมดในงานนำเสนอ.

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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - dictionary ที่แมพโค้ดสคริปต์ไปยังชื่อฟอนต์.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

ดึงชื่อฟอนต์ที่เชื่อมโยงกับแท็กสคริปต์เฉพาะจากธีมของงานนำเสนอ.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| script | java.lang.String | โค้ดสคริปต์ตามมาตรฐาน BCP-47 (เช่น "Latn", "Cyrl", "Jpan") ที่ใช้ระบุตระกูลการเขียน. |

**คืนค่า:**  
java.lang.String - ชื่อฟอนต์ที่ใช้สำหรับสคริปต์ที่ระบุ, หรือ  null  หากสคริปต์ไม่ได้ถูกกำหนด.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

กำหนดชื่อฟอนต์ให้กับแท็กสคริปต์เฉพาะ ซึ่งจะกำหนดวิธีการแสดงผลข้อความของสคริปต์นั้นในงานนำเสนอ.

--------------------

> ```
> ตัวอย่างนี้แสดงวิธีตั้งค่าแบบอักษรสำหรับสคริปต์อาหรับเป็น "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segue UI");
> ```

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| script | java.lang.String | โค้ดสคริปต์ตามมาตรฐาน BCP-47 (เช่น "Arab", "Hebr", "Hans") ที่ระบุตระกูลการเขียน. |
| fontName | java.lang.String | ชื่อฟอนต์ที่ต้องการกำหนดให้กับสคริปต์ที่ระบุ. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

ลบการตั้งค่าฟอนต์ที่เชื่อมโยงกับแท็กสคริปต์เฉพาะออกจากคอลเลกชันฟอนต์ของธีม.

--------------------

> ```
> ตัวอย่างนี้แสดงวิธีการลบการแมพฟอนต์สำหรับสคริปต์ฮิบรู:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| script | java.lang.String | โค้ดสคริปต์ตามมาตรฐาน BCP-47 ที่ต้องการลบการตั้งค่าฟอนต์. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

คืนค่า หรือกำหนดฟอนต์ Latin. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**  
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

คืนค่า หรือกำหนดฟอนต์ Latin. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

คืนค่า หรือกำหนดฟอนต์ East Asian. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**  
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

คืนค่า หรือกำหนดฟอนต์ East Asian. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

คืนค่า หรือกำหนดฟอนต์ complex script. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**คืนค่า:**  
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

คืนค่า หรือกำหนดฟอนต์ complex script. อ่าน/เขียน [IFontData](../../com.aspose.slides/ifontdata).

**พารามิเตอร์:**  
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |