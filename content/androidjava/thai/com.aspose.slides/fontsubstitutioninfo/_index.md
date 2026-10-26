---
title: FontSubstitutionInfo
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: โครงสร้างนี้แสดงข้อมูลเกี่ยวกับการแทนที่ฟอนต์เมื่อจะถูกเรนเดอร์.
type: docs
url: /th/com.aspose.slides/fontsubstitutioninfo/
---
**Inheritance:**
java.lang.Object
```
public class FontSubstitutionInfo
```

โครงสร้างนี้แสดงข้อมูลเกี่ยวกับการแทนที่ฟอนต์เมื่อจะถูกเรนเดอร์.

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
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [FontSubstitutionInfo(String originFontName, String substFontName)](#FontSubstitutionInfo-java.lang.String-java.lang.String-) | สร้างอินสแตนซ์ของ [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) คลาส. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOriginalFontName()](#getOriginalFontName--) | ระบุชื่อฟอนต์ต้นฉบับในงานนำเสนอ. |
| [getSubstitutedFontName()](#getSubstitutedFontName--) | ระบุชื่อฟอนต์ที่แทนที่สำหรับฟอนต์ต้นฉบับ. |
### FontSubstitutionInfo(String originFontName, String substFontName) {#FontSubstitutionInfo-java.lang.String-java.lang.String-}
```
public FontSubstitutionInfo(String originFontName, String substFontName)
```


สร้างอินสแตนซ์ของ [FontSubstitutionInfo](../../com.aspose.slides/fontsubstitutioninfo) คลาส.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| originFontName | java.lang.String | ชื่อฟอนต์ต้นฉบับในงานนำเสนอ String |
| substFontName | java.lang.String | ชื่อฟอนต์ที่แทนที่สำหรับฟอนต์ต้นฉบับ String |

### getOriginalFontName() {#getOriginalFontName--}
```
public final String getOriginalFontName()
```


ระบุชื่อฟอนต์ต้นฉบับในงานนำเสนอ. อ่านอย่างเดียว String

**คืนค่า:**
java.lang.String
### getSubstitutedFontName() {#getSubstitutedFontName--}
```
public final String getSubstitutedFontName()
```


ระบุชื่อฟอนต์ที่แทนที่สำหรับฟอนต์ต้นฉบับ. อ่านอย่างเดียว String

**คืนค่า:**
java.lang.String