---
title: IExternalResourceResolver
second_title: Aspose.Slides for Java API Reference
description: อินเทอร์เฟซ callback ที่ใช้ในการแก้ไขทรัพยากรภายนอกระหว่างการนำเข้าเอกสาร Html และ Svg.
type: docs
url: /th/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

อินเทอร์เฟซ callback ที่ใช้ในการแก้ไขทรัพยากรภายนอกระหว่างการนำเข้า Html, Svg documents import.
## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | แก้ไข URI แบบเต็มจาก base URI และ relative URI |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | แม็พ URI ไปยังวัตถุที่มีทรัพยากรจริง |

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

แก้ไข URI แบบเต็มจาก base URI และ relative URI

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| baseUri | java.lang.String | Base URI ของวัตถุที่เชื่อมโยง |
| relativeUri | java.lang.String | Relative URI ไปยังวัตถุที่เชื่อมโยง |

**ค่าที่คืนกลับ:**
java.lang.String - URI แบบเต็มหรือค่า null หากไม่สามารถแก้ไข URI เชิงสัมพันธ์ได้

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

แม็พ URI ไปยังวัตถุที่มีทรัพยากรจริง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | รายละเอียด |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI ไปยังวัตถุ |

**ค่าที่คืนกลับ:**
java.io.InputStream - วัตถุ InputStream หรือค่า null หากไม่สามารถสตรีมทรัพยากรได้