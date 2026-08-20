---
title: SvgImage
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงภาพ SVG.
type: docs
url: /th/com.aspose.slides/svgimage/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำการ Implement:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

แสดงภาพ SVG.
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | สร้างอ็อบเจกต์ SvgImage ใหม่. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | สร้างอ็อบเจกต์ SvgImage ใหม่. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | สร้างอ็อบเจกต์ SvgImage ใหม่. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างอ็อบเจกต์ SvgImage ใหม่. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างอ็อบเจกต์ SvgImage ใหม่. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างอ็อบเจกต์ SvgImage ใหม่. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSvgData()](#getSvgData--) | ส่งคืนข้อมูล SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | ส่งคืนอินเทอร์เฟซ callback ที่ใช้ในการแก้ไขทรัพยากรภายนอกขณะนำเข้าเอกสาร Svg. |
| [getBaseUri()](#getBaseUri--) | ส่งคืน URI พื้นฐานของ Svg ที่ระบุ. |
| [getSvgContent()](#getSvgContent--) | ส่งคืนเนื้อหา SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | บันทึกภาพ SVG เป็นไฟล์ EMF. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

สร้างอ็อบเจกต์ SvgImage ใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | byte[] | ข้อมูล Svg. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

สร้างอ็อบเจกต์ SvgImage ใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| svgContent | java.lang.String | เนื้อหา Svg. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

สร้างอ็อบเจกต์ SvgImage ใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีม Svg. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

สร้างอ็อบเจกต์ SvgImage ใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| data | byte[] | ข้อมูล Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจกต์ callback ที่ใช้ในการดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น. |
| baseUri | java.lang.String | URI พื้นฐานของ Svg ที่ระบุ ใช้เพื่อแก้ไขลิงค์สัมพัทธ์. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

สร้างอ็อบเจกต์ SvgImage ใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| svgContent | java.lang.String | เนื้อหา Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจกต์ callback ที่ใช้ในการดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น. |
| baseUri | java.lang.String | URI พื้นฐานของ Svg ที่ระบุ ใช้เพื่อแก้ไขลิงค์สัมพัทธ์. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

สร้างอ็อบเจกต์ SvgImage ใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีม Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจกต์ callback ที่ใช้ในการดึงวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น. |
| baseUri | java.lang.String | URI พื้นฐานของ Svg ที่ระบุ ใช้เพื่อแก้ไขลิงค์สัมพัทธ์. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

ส่งคืนข้อมูล SVG. อ่านอย่างเดียว byte[].

**ส่งคืน:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

ส่งคืนอินเทอร์เฟซ callback ที่ใช้ในการแก้ไขทรัพยากรภายนอกขณะนำเข้าเอกสาร Svg. อ่านอย่างเดียว [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**ส่งคืน:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

ส่งคืน URI พื้นฐานของ Svg ที่ระบุ ใช้เพื่อแก้ไขลิงค์สัมพัทธ์. อ่านอย่างเดียว String.

**ส่งคืน:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

ส่งคืนเนื้อหา SVG. อ่านอย่างเดียว String.

**ส่งคืน:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

บันทึกภาพ SVG เป็นไฟล์ EMF.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // สร้างภาพ SVG ใหม่
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // บันทึกภาพ SVG เป็นไฟล์เมตาฟิล
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // สร้างภาพ SVG ใหม่
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // บันทึกภาพ SVG เป็นไฟล์เมตาฟิล
>      svgImage.writeAsEmf(byteStream);
>      // เพิ่มไฟล์เมตาไปยังคอลเลกชันภาพ
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |