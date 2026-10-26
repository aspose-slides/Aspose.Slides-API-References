---
title: ExternalResourceResolver
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: คลาส Callback ที่ใช้ในการแก้ไขทรัพยากรภายนอกระหว่างการนำเข้าเอกสาร Html และ Svg.
type: docs
url: /th/com.aspose.slides/externalresourceresolver/
---
**Inheritance:**  
การสืบทอด:

java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)  
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

Callback class used to resolve external resources during Html, Svg documents import.  
คลาส Callback ใช้ในการแก้ไขทรัพยากรภายนอกระหว่างการนำเข้าเอกสาร Html, Svg.

--------------------

Using this resolver could create a vulnerability when client provided HTML or SVG file will make server software to obtain local or network file. Use with caution. It is recommended not to specify ExternalResourceResolver at all (only embedded objects will be read) or create some subclass which checks if specified uri is valid.  
การใช้ตัวแก้ไขนี้อาจทำให้เกิดช่องโหว่เมื่อไฟล์ HTML หรือ SVG ที่ลูกค้าให้มาทำให้ซอฟต์แวร์เซิร์ฟเวอร์เข้าถึงไฟล์ในเครื่องหรือบนเครือข่าย ใช้อย่างระมัดระวัง แนะนำให้ไม่ระบุ ExternalResourceResolver เลย (จะอ่านเฉพาะวัตถุที่ฝังไว้) หรือสร้างคลาสย่อยที่ตรวจสอบว่า uri ที่ระบุเป็นค่าที่ถูกต้องหรือไม่.

## Constructors

| Constructor | Description |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |

## Methods

| Method | Description |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |

### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

Resolves the absolute URI from the base and relative URIs.  
แก้ไข URI เต็มจาก base URI และ relative URI.

**Parameters:**  
พารามิเตอร์:
| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | java.lang.String | Base URI of linking objects |
| relativeUri | java.lang.String | Relative URI to the linked object. |

**Returns:**  
คืนค่า:
java.lang.String - Absolute URI or null if the relative URI cannot be resolved.  
java.lang.String - URI เต็มหรือ null หากไม่สามารถแก้ไข relative URI ได้.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

Maps a URI to an object containing the actual resource.  
แมป URI ไปยังออบเจ็กต์ที่มีทรัพยากรจริง.

**Parameters:**  
พารามิเตอร์:
| Parameter | Type | Description |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI to the object. |

**Returns:**  
คืนค่า:
java.io.InputStream - A InputStream object or null if resource cannot be streamed.  
java.io.InputStream - ออบเจ็กต์ InputStream หรือ null หากไม่สามารถสตรีมทรัพยากรได้.