---
title: IExternalResourceResolver
second_title: Aspose.Slides for Android via Java API Reference
description: อินเทอร์เฟซการเรียกกลับที่ใช้ในการแก้ไขทรัพยากรภายนอกระหว่างการนำเข้าเอกสาร Html, Svg
type: docs
url: /th/com.aspose.slides/iexternalresourceresolver/
---```
public interface IExternalResourceResolver
```

อินเทอร์เฟซการเรียกกลับที่ใช้ในการแก้ไขทรัพยากรภายนอกระหว่างการนำเข้า Html, Svg เอกสาร
## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | แก้ไข URI แบบเต็มจาก URI ฐานและ URI สัมพัทธ์ |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | แมพ URI ไปยังออบเจ็กต์ที่มีทรัพยากรจริง |
### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public abstract String resolveUri(String baseUri, String relativeUri)
```

แก้ไข URI แบบเต็มจาก URI ฐานและ URI สัมพัทธ์

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseUri | java.lang.String | URI ฐานของวัตถุที่เชื่อมโยง |
| relativeUri | java.lang.String | URI สัมพัทธ์ไปยังวัตถุที่เชื่อมโยง |

**คืนค่า:**
java.lang.String - URI แบบเต็มหรือ null หากไม่สามารถแก้ไข URI สัมพัทธ์ได้
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public abstract InputStream getEntity(String absoluteUri)
```

แมพ URI ไปยังออบเจ็กต์ที่มีทรัพยากรจริง

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI แบบเต็มของวัตถุ |

**คืนค่า:**
java.io.InputStream - อ็อบเจกต์ InputStream หรือ null หากไม่สามารถสตรีมทรัพยากรได้