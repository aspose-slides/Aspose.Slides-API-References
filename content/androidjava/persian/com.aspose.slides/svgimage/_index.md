---
title: SvgImage
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک تصویر SVG را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/svgimage/
---
**وراثت:**  
java.lang.Object  

**تمام واسط‌های پیاده‌سازی شده:**  
[com.aspose.slides.ISvgImage](../../com.aspose.slides/isvgimage)  
```
public class SvgImage implements ISvgImage
```

یک تصویر SVG را نمایش می‌دهد.

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
| [getExternalResourceResolver()](#getExternalResourceResolver--) | رابط بازخوردی را که برای حل منابع خارجی هنگام واردات اسناد Svg استفاده می‌شود، برمی‌گرداند. |
| [getBaseUri()](#getBaseUri--) | URI پایه‌ی Svg مشخص‌شده را برمی‌گرداند. |
| [getSvgContent()](#getSvgContent--) | محتوای SVG را برمی‌گرداند. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | تصویر SVG را به عنوان یک فایل EMF ذخیره می‌کند. |

### SvgImage(byte[] data) {#SvgImage-byte---}
```
public SvgImage(byte[] data)
```

یک شیء SvgImage جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | byte[] | داده SVG. |

### SvgImage(String svgContent) {#SvgImage-java.lang.String-}
```
public SvgImage(String svgContent)
```

یک شیء SvgImage جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgContent | java.lang.String | محتوای SVG. |

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
| data | byte[] | داده SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | یک شیء بازخوردی برای دریافت اشیای خارجی. در صورت null بودن، تمام اشیای خارجی نادیده گرفته می‌شوند. |
| baseUri | java.lang.String | URI پایه‌ی Svg مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(String svgContent, IExternalResourceResolver externalResResolver, String baseUri)
```

یک شیء SvgImage جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgContent | java.lang.String | محتوای SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | یک شیء بازخوردی برای دریافت اشیای خارجی. در صورت null بودن، تمام اشیای خارجی نادیده گرفته می‌شوند. |
| baseUri | java.lang.String | URI پایه‌ی Svg مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri) {#SvgImage-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public SvgImage(InputStream stream, IExternalResourceResolver externalResResolver, String baseUri)
```

یک شیء SvgImage جدید ایجاد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان SVG. |
| externalResResolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | یک شیء بازخوردی برای دریافت اشیای خارجی. در صورت null بودن، تمام اشیای خارجی نادیده گرفته می‌شوند. |
| baseUri | java.lang.String | URI پایه‌ی Svg مشخص‌شده. برای حل پیوندهای نسبی استفاده می‌شود. |

### getSvgData() {#getSvgData--}
```
public final byte[] getSvgData()
```

داده‌های SVG را برمی‌گرداند. فقط خواندنی byte[].

**بازگشت‌ها:**
byte[]

### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public final IExternalResourceResolver getExternalResourceResolver()
```

رابط بازخوردی را که برای حل منابع خارجی هنگام واردات اسناد Svg استفاده می‌شود، برمی‌گرداند. فقط خواندنی [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**بازگشت‌ها:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)

### getBaseUri() {#getBaseUri--}
```
public final String getBaseUri()
```

URI پایه‌ی Svg مشخص‌شده را برمی‌گرداند. برای حل پیوندهای نسبی استفاده می‌شود. فقط خواندنی String.

**بازگشت‌ها:**
java.lang.String

### getSvgContent() {#getSvgContent--}
```
public final String getSvgContent()
```

محتوای SVG را برمی‌گرداند. فقط خواندنی String.

**بازگشت‌ها:**
java.lang.String

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

تصویر SVG را به صورت فایل EMF ذخیره می‌کند.

--------------------

> ```
> The following example shows how to save the SVG image to the metafile.
>  
>  // ایجاد تصویر SVG جدید
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // تصویر SVG را به صورت متافایل ذخیره می‌کند
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
>      // تصویر SVG را به صورت متافایل ذخیره می‌کند
>      svgImage.writeAsEmf(byteStream);
>      // متافایل را به مجموعه تصاویر اضافه می‌کند
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |