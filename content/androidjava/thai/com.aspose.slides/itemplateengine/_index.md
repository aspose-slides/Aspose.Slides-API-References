---
title: ITemplateEngine
second_title: Aspose.Slides for Android via Java API Reference
description: เป็นเอนจินเทมเพลตที่แปลงเทมเพลตและข้อมูลเป็นผลลัพธ์ซึ่งมักเป็น HTML.
type: docs
url: /th/com.aspose.slides/itemplateengine/
---```
public interface ITemplateEngine
```

เป็นเอนจินเทมเพลตที่แปลงเทมเพลตและข้อมูลเป็นผลลัพธ์ (มักเป็น HTML).

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [addTemplate(String key, String template, System.Type modelType)](#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-) | Adds the template to the template collection. |
| [compile(String key, Object model)](#compile-java.lang.String-java.lang.Object-) | Transforms the template with the given key and model object to output. |

### addTemplate(String key, String template, System.Type modelType) {#addTemplate-java.lang.String-java.lang.String-com.aspose.ms.System.Type-}
```
public abstract void addTemplate(String key, String template, System.Type modelType)
```

เพิ่มเทมเพลตเข้าคอลเลกชันเทมเพลต

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| key | java.lang.String | Key for the template in the template collection. |
| template | java.lang.String | Template content. |
| modelType | com.aspose.ms.System.Type | Type of a model object for the template. |

### compile(String key, Object model) {#compile-java.lang.String-java.lang.Object-}
```
public abstract String compile(String key, Object model)
```

แปลงเทมเพลตด้วยคีย์ที่ให้และอ็อบเจ็กต์โมเดลเป็นผลลัพธ์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| key | java.lang.String | Key for the template in the template collection. |
| model | java.lang.Object | Model object with data for transformation. |

**คืนค่า:**
java.lang.String - Resulting output as a String.