---
title: ISvgImage
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an SVG image.
type: docs
url: /fa/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

نمایانگر یک تصویر SVG است.
## متدها

| Method | Description |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | محتوأ SVG را برمی‌گرداند. |
| [getSvgData()](#getSvgData--) | داده‌های SVG را برمی‌گرداند. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | رابط callback بازگشتی که برای حل منابع خارجی در هنگام وارد کردن اسناد SVG استفاده می‌شود. |
| [getBaseUri()](#getBaseUri--) | آدرس پایه URI تصویر SVG مشخص‌شده را برمی‌گرداند. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | تصویر SVG را به‌عنوان فایل EMF ذخیره می‌کند. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


محتوأ SVG را برمی‌گرداند. رشته فقط‌خواندنی.

**بازمی‌گرداند:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


داده‌های SVG را برمی‌گرداند. byte[] فقط‌خواندنی.

**بازمی‌گرداند:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


رابط callback بازگشتی که برای حل منابع خارجی در هنگام وارد کردن اسناد SVG استفاده می‌شود. فقط‌خواندنی [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**بازمی‌گرداند:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


آدرس پایه URI SVG مشخص‌شده را برمی‌گرداند. برای حل پیوندهای نسبی استفاده می‌شود. رشته فقط‌خواندنی.

**بازمی‌گرداند:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


تصویر SVG را به‌عنوان فایل EMF ذخیره می‌کند.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // تصویر SVG جدید را می‌سازد
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // تصویر SVG را به عنوان یک متافایل ذخیره می‌کند
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // تصویر SVG جدید را می‌سازد
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // تصویر SVG را به عنوان یک متافایل ذخیره می‌کند
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