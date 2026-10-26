---
title: SvgImage
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل صورة SVG.
type: docs
url: /ar/com.aspose.slides/svgimage/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

يمثّل صورة SVG.
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | ينشئ كائن SvgImage جديد. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | ينشئ كائن SvgImage جديد. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | ينشئ كائن SvgImage جديد. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ كائن SvgImage جديد. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ كائن SvgImage جديد. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | ينشئ كائن SvgImage جديد. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSvgData()](#getSvgData--) | يرجع بيانات SVG. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | يعيد واجهة رد النداء المستخدمة لحل الموارد الخارجية أثناء استيراد مستندات Svg. |
| [getBaseUri()](#getBaseUri--) | يرجع URI الأساسي للـ Svg المحدد. |
| [getSvgContent()](#getSvgContent--) | يرجع محتوى SVG. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | يحفظ صورة SVG كملف EMF. |
### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

ينشئ كائن SvgImage جديد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | byte[] | بيانات Svg. |
### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

ينشئ كائن SvgImage جديد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| svgContent | java.lang.String | محتوى Svg. |
### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

ينشئ كائن SvgImage جديد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تيار Svg. |
### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

ينشئ كائن SvgImage جديد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| data | byte[] | بيانات Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد النداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فسيتم تجاهل جميع الكائنات الخارجية. |
| baseUri | java.lang.String | URI الأساسي للـ Svg المحدد. يُستخدم لحل الروابط النسبية. |
### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

ينشئ كائن SvgImage جديد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| svgContent | java.lang.String | محتوى Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد النداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فسيتم تجاهل جميع الكائنات الخارجية. |
| baseUri | java.lang.String | URI الأساسي للـ Svg المحدد. يُستخدم لحل الروابط النسبية. |
### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

ينشئ كائن SvgImage جديد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.InputStream | تيار Svg. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | كائن رد النداء يُستخدم لجلب الكائنات الخارجية. إذا كان هذا المعامل null فسيتم تجاهل جميع الكائنات الخارجية. |
| baseUri | java.lang.String | URI الأساسي للـ Svg المحدد. يُستخدم لحل الروابط النسبية. |
### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

يرجع بيانات SVG. للقراءة فقط byte[].

**القيمة المرجعة:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

يعيد واجهة رد النداء المستخدمة لحل الموارد الخارجية أثناء استيراد مستندات Svg. للقراءة فقط [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**القيمة المرجعة:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

يرجع URI الأساسي للـ Svg المحدد. يُستخدم لحل الروابط النسبية. للقراءة فقط String.

**القيمة المرجعة:**
java.lang.String
### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

يرجع محتوى SVG. للقراءة فقط String.

**القيمة المرجعة:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

يحفظ صورة SVG كملف EMF.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
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
>      // Saves the SVG image as a metafille
>      svgImage.writeAsEmf(byteStream);
>      // Adds metafile to the image collection
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | java.io.OutputStream | تيار الهدف |