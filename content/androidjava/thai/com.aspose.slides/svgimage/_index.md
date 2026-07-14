---
title: SvgImage
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงภาพ SVG.
type: docs
url: /th/com.aspose.slides/svgimage/
---
**การสืบทอด:**  
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)  
```
public class SvgImage implements ISvgImage
```

แสดงภาพ SVG.

## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | สร้างอ็อบเจ็กต์ SvgImage ใหม่ |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | สร้างอ็อบเจ็กต์ SvgImage ใหม่ |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | สร้างอ็อบเจ็กต์ SvgImage ใหม่ |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างอ็อบเจ็กต์ SvgImage ใหม่ |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างอ็อบเจ็กต์ SvgImage ใหม่ |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | สร้างอ็อบเจ็กต์ SvgImage ใหม่ |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSvgData()](#getSvgData--) | คืนค่า SVG data |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | คืนค่าอินเทอร์เฟซ callback ที่ใช้เพื่อแก้ไขทรัพยากรภายนอกระหว่างการนำเข้าเอกสาร Svg |
| [getBaseUri()](#getBaseUri--) | คืนค่า URI ฐานของ Svg ที่ระบุ |
| [getSvgContent()](#getSvgContent--) | คืนค่าเนื้อหา SVG |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | บันทึกรูปภาพ SVG เป็นไฟล์ EMF |

### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

สร้างอ็อบเจ็กต์ SvgImage ใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | byte[] | ข้อมูล Svg |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

สร้างอ็อบเจ็กต์ SvgImage ใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| svgContent | java.lang.String | เนื้อหา Svg |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

สร้างอ็อบเจ็กต์ SvgImage ใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีม Svg |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

สร้างอ็อบเจ็กต์ SvgImage ใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| data | byte[] | ข้อมูล Svg |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจ็กต์ callback ที่ใช้เพื่อดึงข้อมูลวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| baseUri | java.lang.String | URI ฐานของ Svg ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบสัมพันธ์ |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

สร้างอ็อบเจ็กต์ SvgImage ใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| svgContent | java.lang.String | เนื้อหา Svg |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจ็กต์ callback ที่ใช้เพื่อดึงข้อมูลวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| baseUri | java.lang.String | URI ฐานของ Svg ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบสัมพันธ์ |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

สร้างอ็อบเจ็กต์ SvgImage ใหม่

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.InputStream | สตรีม Svg |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | อ็อบเจ็กต์ callback ที่ใช้เพื่อดึงข้อมูลวัตถุภายนอก หากพารามิเตอร์นี้เป็น null วัตถุภายนอกทั้งหมดจะถูกละเว้น |
| baseUri | java.lang.String | URI ฐานของ Svg ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบสัมพันธ์ |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

คืนค่า SVG data. อ่านอย่างเดียว byte[].

**คืนค่า:**
byte[]

### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

คืนค่าอินเทอร์เฟซ callback ที่ใช้เพื่อแก้ไขทรัพยากรภายนอกระหว่างการนำเข้าเอกสาร Svg. อ่านอย่างเดียว [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**คืนค่า:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)

### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

คืนค่า URI ฐานของ Svg ที่ระบุ ใช้เพื่อแก้ไขลิงก์แบบสัมพันธ์. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String

### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

คืนค่าเนื้อหา SVG. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

บันทึกรูปภาพ SVG เป็นไฟล์ EMF

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // สร้างภาพ SVG ใหม่
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // บันทึกรูปภาพ SVG เป็น metafille
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
>      // บันทึกรูปภาพ SVG เป็น metafille
>      svgImage.writeAsEmf(byteStream);
>      // เพิ่ม metafile ไปยังคอลเลกชันภาพ
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |