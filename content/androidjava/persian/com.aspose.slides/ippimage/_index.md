---
title: IPPImage
second_title: Aspose.Slides for Android via Java API Reference
description: یک تصویر را در ارائه نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/ippimage/
---```
public interface IPPImage
```

یک تصویر را در ارائه نمایش می‌دهد.
## متدها

| متد | توضیحات |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | یک کپی از داده‌های تصویر را برمی‌گرداند. |
| [getImage()](#getImage--) | یک کپی از تصویر را برمی‌گرداند. |
| [getSvgImage()](#getSvgImage--) | شیء ISvgImage را برمی‌گرداند یا تنظیم می‌کند [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | شیء ISvgImage را برمی‌گرداند یا تنظیم می‌کند [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | داده‌های تصویر را جایگزین می‌کند. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | تصویر را جایگزین می‌کند. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | تصویر را جایگزین می‌کند. |
| [getContentType()](#getContentType--) | یک نوع MIME از تصویر را برمی‌گرداند، کدگذاری شده در \#getBinaryData.getBinaryData. |
| [getWidth()](#getWidth--) | یک عرض از تصویر را برمی‌گرداند. |
| [getHeight()](#getHeight--) | یک ارتفاع از تصویر را برمی‌گرداند. |
| [getX()](#getX--) | یک افست X از تصویر را برمی‌گرداند. |
| [getY()](#getY--) | یک افست Y از تصویر را برمی‌گرداند. |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```

یک کپی از داده‌های تصویر را برمی‌گرداند. فقط‌خواندنی byte[].

**بازگشت:**
byte[]
### getImage() {#getImage--}
```
public abstract IImage getImage()
```

یک کپی از تصویر را برمی‌گرداند. فقط‌خواندنی \#getImage.getImage.

**بازگشت:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public abstract ISvgImage getSvgImage()
```

شیء ISvgImage را برمی‌گرداند یا تنظیم می‌کند [ISvgImage](../../com.aspose.slides/isvgimage)

این مقدار نشان می‌دهد که این تصویر از SVG ساخته شده است.

**بازگشت:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public abstract void setSvgImage(ISvgImage value)
```

شیء ISvgImage را برمی‌گرداند یا تنظیم می‌کند [ISvgImage](../../com.aspose.slides/isvgimage)

این مقدار نشان می‌دهد که این تصویر از SVG ساخته شده است.

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

تصویر را جایگزین می‌کند. توجه: هنگامی که Image یک متا‌فایل است - به رستری تبدیل خواهد شد. به جای آن از replaceImage(byte[]) استفاده کنید

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

یک نوع MIME از تصویر را برمی‌گرداند، کدگذاری شده در \#getBinaryData.getBinaryData. فقط‌خواندنی String.

**بازگشت:**
java.lang.String
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

یک عرض از تصویر را برمی‌گرداند. فقط‌خواندنی int.

**بازگشت:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

یک ارتفاع از تصویر را برمی‌گرداند. فقط‌خواندنی int.

**بازگشت:**
int
### getX() {#getX--}
```
public abstract int getX()
```

یک افست X از تصویر را برمی‌گرداند. فقط‌خواندنی int.

**بازگشت:**
int
### getY() {#getY--}
```
public abstract int getY()
```

یک افست Y از تصویر را برمی‌گرداند. فقط‌خواندنی int.

**بازگشت:**
int