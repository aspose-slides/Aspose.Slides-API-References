---
title: ISvgImage
second_title: Aspose.Slides for Java API Reference
description: แสดงภาพ SVG.
type: docs
url: /th/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

แสดงภาพ SVG.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | คืนเนื้อหา SVG. |
| [getSvgData()](#getSvgData--) | คืนข้อมูล SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | คืนอินเทอร์เฟซ callback ที่ใช้เพื่อแก้ไขทรัพยากรภายนอกระหว่างการนำเข้าเอกสาร SVG. |
| [getBaseUri()](#getBaseUri--) | คืน URI พื้นฐานของ SVG ที่ระบุ. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | บันทึกภาพ SVG เป็นไฟล์ EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


คืนเนื้อหา SVG. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


คืนข้อมูล SVG. อ่านอย่างเดียว byte[].

**คืนค่า:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


คืนอินเทอร์เฟซ callback ที่ใช้เพื่อแก้ไขทรัพยากรภายนอกระหว่างการนำเข้าเอกสาร SVG. อ่านอย่างเดียว [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**คืนค่า:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


คืน URI พื้นฐานของ SVG ที่ระบุ. ใช้สำหรับแก้ไขลิงก์แบบสัมพัทธ์. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


บันทึกภาพ SVG เป็นไฟล์ EMF.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // สร้างภาพ SVG ใหม่
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // บันทึกภาพ SVG เป็น metafille
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
>      // บันทึกภาพ SVG เป็น metafile
>      svgImage.writeAsEmf(byteStream);
>      // เพิ่ม metafile ลงในคอลเลกชันภาพ
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |