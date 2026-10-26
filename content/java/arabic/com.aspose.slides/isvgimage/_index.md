---
title: ISvgImage
second_title: Aspose.Slides for Java API Reference
description: Represents an SVG image.
type: docs
url: /ar/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

يمثل صورة SVG.
## الطرق

| Method | Description |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | يعيد محتوى SVG. |
| [getSvgData()](#getSvgData--) | يعيد بيانات SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | إرجاع واجهة رد النداء المستخدمة لحل الموارد الخارجية أثناء استيراد مستندات SVG. |
| [getBaseUri()](#getBaseUri--) | يعيد URI الأساسي لـ SVG المحدد. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | يحفظ صورة SVG كملف EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


يعيد محتوى SVG. قراءة فقط String.

**الإرجاع:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


يعيد بيانات SVG. قراءة فقط byte[].

**الإرجاع:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


إرجاع واجهة رد النداء المستخدمة لحل الموارد الخارجية أثناء استيراد مستندات SVG. قراءة فقط [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**الإرجاع:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


يعيد URI الأساسي لـ SVG المحدد. يُستخدم لحل الروابط النسبية. قراءة فقط String.

**الإرجاع:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


يحفظ صورة SVG كملف EMF.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // إنشاء صورة SVG جديدة
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // حفظ صورة SVG كملف ميتا
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // إنشاء صورة SVG جديدة
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // حفظ صورة SVG كملف ميتا
>      svgImage.writeAsEmf(byteStream);
>      // إضافة ملف ميتا إلى مجموعة الصور
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تدفق الهدف |