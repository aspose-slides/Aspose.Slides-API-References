---
title: HtmlExternalResolver
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: อ็อบเจกต์คอลแบ็คที่ใช้โดยรูทีนการนำเข้า HTML เพื่อดึงอ็อบเจกต์ที่อ้างอิงเช่นรูปภาพ.
type: docs
url: /th/com.aspose.slides/htmlexternalresolver/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IHtmlExternalResolver](../../com.aspose.slides/ihtmlexternalresolver)
```
public class HtmlExternalResolver implements IHtmlExternalResolver
```

อ็อบเจกต์คอลแบ็คที่ใช้โดยรูทีนการนำเข้า HTML เพื่อดึงอ็อบเจกต์ที่อ้างอิงเช่นรูปภาพ.

--------------------

การใช้รีโซลเวอร์นี้อาจทำให้เกิดช่องโหว่เมื่อไฟล์ HTML ที่ลูกค้าให้มาทำให้ซอฟต์แวร์เซิร์ฟเวอร์เข้าถึงไฟล์ในระบบหรือเครือข่าย ใช้ด้วยความระมัดระวัง แนะนำไม่ให้ระบุ HtmlExternalResolver เลย (จะอ่านเฉพาะอ็อบเจกต์ที่ฝังอยู่) หรือสร้างซับคลาสที่ตรวจสอบว่าที่อยู่ URI ที่ระบุนั้นเป็นค่าที่ถูกต้องหรือไม่.

## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [HtmlExternalResolver()](#HtmlExternalResolver--) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | แก้ไขที่อยู่ URI เต็มรูปแบบจาก URI ฐานและ URI สัมพัทธ์. |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | แมปที่อยู่ URI ไปยังอ็อบเจกต์ที่มีทรัพยากรจริง. |

### HtmlExternalResolver() {#HtmlExternalResolver--}
```
public HtmlExternalResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

แก้ไขที่อยู่ URI เต็มรูปแบบจาก URI ฐานและ URI สัมพัทธ์.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| baseUri | java.lang.String | URI ฐานของอ็อบเจกต์ที่เชื่อมโยง |
| relativeUri | java.lang.String | URI สัมพัทธ์ไปยังอ็อบเจกต์ที่เชื่อมโยง. |

**ค่าที่คืนกลับ:**
java.lang.String - URI เต็มรูปแบบหรือ null หากไม่สามารถแก้ไข URI สัมพัทธ์ได้.

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

แมปที่อยู่ URI ไปยังอ็อบเจกต์ที่มีทรัพยากรจริง.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI เต็มรูปแบบของอ็อบเจกต์. |

**ค่าที่คืนกลับ:**
java.io.InputStream - อ็อบเจกต์ InputStream หรือ null หากไม่สามารถสตรีมทรัพยากรได้.