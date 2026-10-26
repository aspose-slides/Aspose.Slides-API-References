---
title: SvgImage
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک تصویر SVG است.
type: docs
url: /fa/com.aspose.slides/svgimage/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)
```
public class SvgImage implements ISvgImage
```

نمایانگر یک تصویر SVG است.

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [SvgImage(byte[] data)](#SvgImage-byte---) | یک شیء SvgImage جدید ایجاد می‌کند. |
| [SvgImage(String svgContent)](#SvgImage-java.lang.String-) | یک شیء SvgImage جدید ایجاد می‌کند. |
| [SvgImage(InputStream stream)](#SvgImage-java.io.InputStream-) | یک شیء SvgImage جدید ایجاد می‌کند. |
| [SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-) | یک شیء SvgImage جدید ایجاد می‌کند. |
| [SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | یک شیء SvgImage جدید ایجاد می‌کند. |
| [SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)](#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | یک شیء SvgImage جدید ایجاد می‌کند. |

## متدها

| متد | توضیح |
| --- | --- |
| [getSvgData()](#getSvgData--) | داده‌های SVG را برمی‌گرداند. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | رابط بازگشتی که برای حل منابع خارجی در زمان وارد کردن اسناد Svg استفاده می‌شود. |
| [getBaseUri()](#getBaseUri--) | URI پایه‌ی SVG مشخص‌شده را برمی‌گرداند. |
| [getSvgContent()](#getSvgContent--) | محتویات SVG را برمی‌گرداند. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | تصویر SVG را به‌عنوان فایل EMF ذخیره می‌کند. |

### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

یک شیء SvgImage جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] | داده‌های SVG. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

یک شیء SvgImage جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgContent | java.lang.String | محتویات SVG. |

### SvgImage(InputStream stream) {#SvgImage-java.io.InputStream-}
```
public SvgImage(InputStream stream)
```

یک شیء SvgImage جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان SVG. |

### SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-byte---com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(byte[] data, IExternalResourceResolver externalResResolver, String baseUri)
```

یک شیء SvgImage جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] | داده‌های SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | یک شیء بازگشتی که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد، تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| baseUri | java.lang.String | URI پایه‌ی SVG مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

یک شیء SvgImage جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgContent | java.lang.String | محتویات SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | یک شیء بازگشتی که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد، تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| baseUri | java.lang.String | URI پایه‌ی SVG مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

یک شیء SvgImage جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | یک شیء بازگشتی که برای دریافت اشیاء خارجی استفاده می‌شود. اگر این پارامتر null باشد، تمام اشیاء خارجی نادیده گرفته می‌شوند. |
| baseUri | java.lang.String | URI پایه‌ی SVG مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

داده‌های SVG را برمی‌گرداند. فقط-خواندنی byte[].

**بازمی‌گرداند:**
byte[]

### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

رابط بازگشتی که برای حل منابع خارجی در زمان وارد کردن اسناد Svg استفاده می‌شود. فقط-خواندنی [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**بازمی‌گرداند:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)

### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

URI پایه‌ی SVG مشخص‌شده را برمی‌گرداند. برای حل پیوندهای نسبی استفاده می‌شود. فقط-خواندنی String.

**بازمی‌گرداند:**
java.lang.String

### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

محتویات SVG را برمی‌گرداند. فقط-خواندنی String.

**بازمی‌گرداند:**
java.lang.String

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

تصویر SVG را به‌عنوان فایل EMF ذخیره می‌کند.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // ایجاد تصویر SVG جدید
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // ذخیره تصویر SVG به‌صورت متافایل
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // ایجاد تصویر SVG جدید
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // ذخیره تصویر SVG به‌صورت متافایل
>      svgImage.writeAsEmf(byteStream);
>      // افزودن متافایل به مجموعه تصاویر
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |