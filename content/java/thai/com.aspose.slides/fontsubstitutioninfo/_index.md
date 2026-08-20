---
title: FontSubstitutionInfo
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: โครงสร้างนี้แสดงข้อมูลเกี่ยวกับการแทนที่แบบอักษรเมื่อจะทำการแสดงผล
type: docs
url: /th/com.aspose.slides/fontsubstitutioninfo/
---
**Inheritance:**
java.lang.Object
```
public class FontSubstitutionInfo
```

โครงสร้างนี้แสดงข้อมูลเกี่ยวกับการแทนที่แบบอักษรเมื่อจะทำการแสดงผล

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (FontSubstitutionInfo fontSubstitution : pres.getFontsManager().getSubstitutions())
>      {
>          System.out.println(fontSubstitution.getOriginalFontName() + " -> " + fontSubstitution.getSubstitutedFontName());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## คอนสตรักเตอร์

| คอนสตรักเตอร์ | คำอธิบาย |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | สร้างอินสแตนซ์ของคลาส [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | บ่งชี้ชื่อแบบอักษรต้นทางในงานนำเสนอ |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | บ่งชี้ชื่อแบบอักษรที่ใช้แทนสำหรับแบบอักษรต้นฉบับ |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


สร้างอินสแตนซ์ของคลาส [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| originFontName | java.lang.String | ชื่อแบบอักษรต้นทางในงานนำเสนอ String |
| substFontName | java.lang.String | ชื่อแบบอักษรที่ใช้แทนสำหรับแบบอักษรต้นฉบับ String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


บ่งชี้ชื่อแบบอักษรต้นทางในงานนำเสนอ อ่านอย่างเดียว String

**คืนค่า:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


บ่งชี้ชื่อแบบอักษรที่ใช้แทนสำหรับแบบอักษรต้นฉบับ อ่านอย่างเดียว String

**คืนค่า:**
java.lang.String