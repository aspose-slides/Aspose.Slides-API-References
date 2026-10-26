---
title: ITemplateEngine
second_title: Aspose.Slides for Java API Reference
description: แสดงถึงเครื่องมือเทมเพลตที่แปลงคู่เทมเพลตและข้อมูลให้เป็นผลลัพธ์ซึ่งโดยปกติจะเป็น HTML.
type: docs
url: /th/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

แสดงถึงเครื่องมือเทมเพลตที่แปลงคู่เทมเพลตและข้อมูลให้เป็นผลลัพธ์ (โดยปกติคือ HTML).

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | เพิ่มเทมเพลตไปยังคอลเลกชันของเทมเพลต. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | แปลงเทมเพลตด้วยคีย์ที่ให้และอ็อบเจ็กต์โมเดลให้เป็นผลลัพธ์. |
### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```


เพิ่มเทมเพลตไปยังคอลเลกชันของเทมเพลต.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| key | java.lang.String | คีย์สำหรับเทมเพลตในคอลเลกชันของเทมเพลต. |
| template | java.lang.String | เนื้อหาเทมเพลต. |
| modelType | com.aspose.ms.System.Type | ประเภทของอ็อบเจ็กต์โมเดลสำหรับเทมเพลต. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```


แปลงเทมเพลตด้วยคีย์ที่ให้และอ็อบเจ็กต์โมเดลให้เป็นผลลัพธ์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| key | java.lang.String | คีย์สำหรับเทมเพลตในคอลเลกชันของเทมเพลต. |
| model | java.lang.Object | อ็อบเจ็กต์โมเดลที่มีข้อมูลสำหรับการแปลง. |

**ผลลัพธ์:**
java.lang.String - ผลลัพธ์ที่ได้เป็น String.