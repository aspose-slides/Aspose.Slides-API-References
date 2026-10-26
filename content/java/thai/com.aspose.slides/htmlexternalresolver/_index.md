---
title: HtmlExternalResolver
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: อ็อบเจ็กต์ callback ที่ใช้โดยกระบวนการนำเข้า HTML เพื่อดึงอ็อบเจ็กต์ที่อ้างอิงเช่นรูปภาพ.
type: docs
url: /th/com.aspose.slides/htmlexternalresolver/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

อ็อบเจ็กต์ callback ที่ใช้โดยรหัสนำเข้า HTML เพื่อดึงอ็อบเจ็กต์ที่อ้างอิงเช่นรูปภาพ.

--------------------

การใช้ resolver นี้อาจทำให้เกิดช่องโหว่าเมื่อไฟล์ HTML ที่ลูกค้าให้มาทำให้ซอฟต์แวร์เซิร์ฟเวอร์ดึงไฟล์ในเครื่องหรือในเครือข่าย. ใช้งานด้วยความระมัดระวัง. แนะนำไม่ระบุ HtmlExternalResolver เลย (จะอ่านเฉพาะอ็อบเจ็กต์ที่ฝังอยู่) หรือสร้างคลาสย่อยที่ตรวจสอบว่าที่อยู่ uri ที่ระบุเป็นที่ถูกต้องหรือไม่.
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | Resolves the absolute URI from the base and relative URIs. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | Maps a URI to an object containing the actual resource. |
### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```


### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```


แก้ไข URI แบบเต็มจาก base URI และ relative URI.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseUri | java.lang.String | Base URI ของอ็อบเจ็กต์ที่เชื่อมโยง |
| relativeUri | java.lang.String | Relative URI ของอ็อบเจ็กต์ที่เชื่อมโยง. |

**คืนค่า:**
java.lang.String - URI แบบเต็มหรือ null หากไม่สามารถแก้ไข Relative URI ได้.
### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```


แมป URI ไปยังอ็อบเจ็กต์ที่มีทรัพยากรจริง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| absoluteUri | java.lang.String | Absolute URI ของอ็อบเจ็กต์. |

**คืนค่า:**
java.io.InputStream - อ็อบเจ็กต์ InputStream หรือ null หากไม่สามารถสตรีมทรัพยากรได้.