---
title: IPPImage
second_title: Aspose.Slides for Java API Reference
description: تصویری را در یک ارائه نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

تصویری را در یک ارائه نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | یک کپی از داده‌های تصویر را برمی‌گرداند. |
| [getImage()](#getImage--) | یک کپی از تصویر را برمی‌گرداند. |
| [getSvgImage()](#getSvgImage--) | شیء ISvgImage را برمی‌گرداند یا تنظیم می‌کند [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | شیء ISvgImage را برمی‌گرداند یا تنظیم می‌کند [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | داده‌های تصویر را جایگزین می‌کند. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | تصویر را جایگزین می‌کند. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | تصویر را جایگزین می‌کند. |
| [getContentType()](#getContentType--) | یک نوع MIME از تصویر را برمی‌گرداند که در \#getBinaryData.getBinaryData کدگذاری شده است. |
| [getWidth()](#getWidth--) | عرض تصویر را برمی‌گرداند. |
| [getHeight()](#getHeight--) | ارتفاع تصویر را برمی‌گرداند. |
| [getX()](#getX--) | اختلاف X تصویر را برمی‌گرداند. |
| [getY()](#getY--) | اختلاف Y تصویر را برمی‌گرداند. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


یک کپی از داده‌های تصویر را برمی‌گرداند. فقط-خواندنی byte[].

**برمی‌گرداند:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


یک کپی از تصویر را برمی‌گرداند. فقط-خواندنی \#getImage.getImage.

**برمی‌گرداند:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```


شیء ISvgImage را برمی‌گرداند یا تنظیم می‌کند [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

این مقدار نشان می‌دهد که این تصویر از SVG ایجاد شده است.

**برمی‌گرداند:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```


شیء ISvgImage را برمی‌گرداند یا تنظیم می‌کند [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

این مقدار نشان می‌دهد که این تصویر از SVG ایجاد شده است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public abstract void replaceImage(byte[] newImageData)
```


داده‌های تصویر را جایگزین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newImageData | byte[] | داده‌های تصویر جدید. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public abstract void replaceImage(IImage newImage)
```


تصویر را جایگزین می‌کند. توجه: وقتی Image یک متافایل است - تبدیل به رستر می‌شود. به جای آن از replaceImage(byte[]) استفاده کنید

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | تصویر جدید. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public abstract void replaceImage(IPPImage newImage)
```


تصویر را جایگزین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | IPPImage جدید. |
### getContentType() {#getContentType--}
```
public abstract String getContentType()
```


یک نوع MIME از تصویر را برمی‌گرداند که در \#getBinaryData.getBinaryData کدگذاری شده است. فقط-خواندنی String.

**برمی‌گرداند:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


عرض تصویر را برمی‌گرداند. فقط-خواندنی int.

**برمی‌گرداند:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


ارتفاع تصویر را برمی‌گرداند. فقط-خواندنی int.

**برمی‌گرداند:**
int
### getX() {#getX--}
```
public abstract int getX()
```


اختلاف X تصویر را برمی‌گرداند. فقط-خواندنی int.

**برمی‌گرداند:**
int
### getY() {#getY--}
```
public abstract int getY()
```


اختلاف Y تصویر را برمی‌گرداند. فقط-خواندنی int.

**برمی‌گرداند:**
int