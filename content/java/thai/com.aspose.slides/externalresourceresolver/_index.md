---
title: ExternalResourceResolver
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: คลาส Callback ที่ใช้เพื่อแก้ไขทรัพยากรภายนอกระหว่างการนำเข้าเอกสาร Html และ Svg.
type: docs
url: /th/com.aspose.slides/externalresourceresolver/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซทั้งหมดที่นำไปใช้:**  
[com.aspose.slides.IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)  
```
public class ExternalResourceResolver implements IExternalResourceResolver
```

คลาส Callback ที่ใช้เพื่อแก้ไขทรัพยากรภายนอกระหว่างการนำเข้าเอกสาร Html, Svg

--------------------

การใช้ตัวแก้ไขนี้อาจทำให้เกิดช่องโหว่เมื่อไฟล์ HTML หรือ SVG ที่ผู้ใช้จัดหาให้ทำให้ซอฟต์แวร์เซิร์ฟเวอร์เข้าถึงไฟล์ในเครื่องหรือเครือข่ายได้ ใช้งานด้วยความระมัดระวัง แนะนำไม่ให้กำหนด ExternalResourceResolver เลย (จะอ่านเฉพาะออบเจ็กต์ที่ฝังไว้) หรือสร้างซับคลาสที่ตรวจสอบว่าที่อยู uri ที่ระบุนั้นถูกต้องหรือไม่
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [ExternalResourceResolver()](#ExternalResourceResolver--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [resolveUri(String baseUri, String relativeUri)](#resolveUri-java.lang.String-java.lang.String-) | แก้ไขที่อยู่ URI แบบสมบูรณ์จาก URI พื้นฐานและ URI สัมพันธ์ |
| [getEntity(String absoluteUri)](#getEntity-java.lang.String-) | แมปที่อยู่ URI ไปยังออบเจ็กต์ที่มีทรัพยากรจริง |

### ExternalResourceResolver() {#ExternalResourceResolver--}
```
public ExternalResourceResolver()
```

### resolveUri(String baseUri, String relativeUri) {#resolveUri-java.lang.String-java.lang.String-}
```
public String resolveUri(String baseUri, String relativeUri)
```

แก้ไขที่อยู่ URI แบบสมบูรณ์จาก URI พื้นฐานและ URI สัมพันธ์

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| baseUri | java.lang.String | URI พื้นฐานของออบเจ็กต์ที่เชื่อมโยง |
| relativeUri | java.lang.String | URI สัมพันธ์ไปยังออบเจ็กต์ที่เชื่อมโยง |

**ผลลัพธ์:**  
java.lang.String - URI แบบสมบูรณ์หรือ null หากไม่สามารถแก้ไข URI สัมพันธ์ได้

### getEntity(String absoluteUri) {#getEntity-java.lang.String-}
```
public InputStream getEntity(String absoluteUri)
```

แมปที่อยู่ URI ไปยังออบเจ็กต์ที่มีทรัพยากรจริง

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| absoluteUri | java.lang.String | URI แบบสมบูรณ์ของออบเจ็กต์ |

**ผลลัพธ์:**  
java.io.InputStream - ออบเจ็กต์ InputStream หรือ null หากไม่สามารถสตรีมทรัพยากรได้