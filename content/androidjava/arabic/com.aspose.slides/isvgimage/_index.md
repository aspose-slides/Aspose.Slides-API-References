---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an SVG image.
type: docs
url: /ar/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

Represents an SVG image.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | يرجع محتوى SVG. |
| [getSvgData()](#getSvgData--) | يرجع بيانات SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | يرجع واجهة رد نداء تُستخدم لحل الموارد الخارجية أثناء استيراد مستندات SVG. |
| [getBaseUri()](#getBaseUri--) | يرجع URI الأساسي لـ SVG المحدد. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | يحفظ صورة SVG كملف EMF. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


يرجع محتوى SVG. قراءة فقط String.

**الإرجاع:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


يرجع بيانات SVG. قراءة فقط byte[].

**الإرجاع:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


يرجع واجهة رد نداء تُستخدم لحل الموارد الخارجية أثناء استيراد مستندات SVG. قراءة فقط [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**الإرجاع:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


يرجع URI الأساسي لـ SVG المحدد. يُستخدم لحل الروابط النسبية. قراءة فقط String.

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
>  // ينشئ صورة SVG جديدة
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // يحفظ صورة SVG كملف ميتافيل
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // ينشئ صورة SVG ثانية
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // يحفظ صورة SVG كملف ميتافيل
>      svgImage.writeAsEmf(byteStream);
>      // يضيف ملف الميتافيل إلى مجموعة الصور
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تيار الهدف |