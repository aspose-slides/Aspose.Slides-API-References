---
title: ISvgImage
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นการแสดงภาพ SVG.
type: docs
url: /th/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

เป็นการแสดงภาพ SVG.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | คืนค่าเนื้อหา SVG. |
| [getSvgData()](#getSvgData--) | คืนค่าข้อมูล SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | คืนค่าอินเทอร์เฟซ callback ที่ใช้ในการแก้ไขทรัพยากรภายนอกระหว่างการนำเข้าเอกสาร SVG. |
| [getBaseUri()](#getBaseUri--) | คืนค่า base URI ของ SVG ที่ระบุ. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | บันทึกภาพ SVG เป็นไฟล์ EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```

คืนค่าเนื้อหา SVG. อ่านอย่างเดียว String.

**คืนค่า:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```

คืนค่าข้อมูล SVG. อ่านอย่างเดียว byte[].

**คืนค่า:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```

คืนค่าอินเทอร์เฟซ callback ที่ใช้ในการแก้ไขทรัพยากรภายนอกระหว่างการนำเข้าเอกสาร SVG. อ่านอย่างเดียว [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**คืนค่า:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```

คืนค่า base URI ของ SVG ที่ระบุ. ใช้เพื่อแก้ไขลิงก์สัมพันธ์. อ่านอย่างเดียว String.

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
>  // Creates the new SVG image
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // Saves the SVG image as a metafille
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Creates the new SVG image
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // Saves the SVG image as a metafile
>      svgImage.writeAsEmf(byteStream);
>      // Adds metafile to the image collection
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| stream | java.io.OutputStream | สตรีมเป้าหมาย |