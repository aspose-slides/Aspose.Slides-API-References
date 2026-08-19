---
title: ISvgImage
second_title: Aspose.Slides for Java مرجع API
description: یک تصویر SVG را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/isvgimage/
---```
public interface ISvgImage
```

یک تصویر SVG را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getSvgContent()](#getSvgContent--) | محتوای SVG را برمی‌گرداند. |
| [getSvgData()](#getSvgData--) | داده‌های SVG را برمی‌گرداند. |
| [getExternalResourceResolver()](#getExternalResourceResolver--) | رابط فراخوانی بازگشتی که برای حل منابع خارجی هنگام وارد کردن اسناد SVG استفاده می‌شود. |
| [getBaseUri()](#getBaseUri--) | آدرس پایه (URI) SVG مشخص شده را برمی‌گرداند. |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | تصویر SVG را به عنوان یک فایل EMF ذخیره می‌کند. |
### getSvgContent() {#getSvgContent--}
```
public abstract String getSvgContent()
```


محتوای SVG را برمی‌گرداند. رشته فقط خواندنی.

**بازگشت:**
java.lang.String
### getSvgData() {#getSvgData--}
```
public abstract byte[] getSvgData()
```


داده‌های SVG را برمی‌گرداند. آرایه بایت فقط خواندنی.

**بازگشت:**
byte[]
### getExternalResourceResolver() {#getExternalResourceResolver--}
```
public abstract IExternalResourceResolver getExternalResourceResolver()
```


رابط فراخوانی بازگشتی که برای حل منابع خارجی هنگام وارد کردن اسناد SVG استفاده می‌شود. فقط خواندنی [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver).

**بازگشت:**
[IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver)
### getBaseUri() {#getBaseUri--}
```
public abstract String getBaseUri()
```


آدرس پایه (URI) SVG مشخص شده را برمی‌گرداند. برای حل پیوندهای نسبی استفاده می‌شود. رشته فقط خواندنی.

**بازگشت:**
java.lang.String
### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```


تصویر SVG را به عنوان یک فایل EMF ذخیره می‌کند.

--------------------

> ```
> The following example demonstrates how to save the SVG image into a metafile.
>  
>  // تصویر SVG جدید را ایجاد می‌کند
>  ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>  // تصویر SVG را به‌عنوان یک متا‌فایل ذخیره می‌کند
>  FileOutputStream fileStream = new FileOutputStream("SvgAsEmf.emf");
>  svgImage.writeAsEmf(fileStream);
>  
>  This sample demonstrates how to add the SVG image as a metafile to the presentation image collection.
>  
>  Presentation pres = new Presentation();
>  try {
>      // تصویر SVG جدید را ایجاد می‌کند
>      ISvgImage svgImage = new SvgImage(new FileInputStream("content.svg"));
>      ByteArrayOutputStream byteStream = new ByteArrayOutputStream();
>      // تصویر SVG را به‌عنوان یک متا‌فایل ذخیره می‌کند
>      svgImage.writeAsEmf(byteStream);
>      // متا‌فایل را به مجموعه تصاویر اضافه می‌کند
>      pres.getImages().addImage(byteStream.toByteArray());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.OutputStream | جریان هدف |