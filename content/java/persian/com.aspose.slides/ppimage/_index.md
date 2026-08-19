---
title: PPImage
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر یک تصویر در ارائه است.
type: docs
url: /fa/com.aspose.slides/ppimage/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IPPImage](../../com.aspose.slides/ippimage), com.aspose.ms.System.IDisposable
```
public class PPImage implements IPPImage, System.IDisposable
```

نمایانگر یک تصویر در ارائه است.
## متدها

| متد | توضیح |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | یک کپی از داده‌های تصویر را برمی‌گرداند. |
| [getImage()](#getImage--) | یک کپی از تصویر را برمی‌گرداند. |
| [getSvgImage()](#getSvgImage--) | بازگرداندن یا تنظیم شیء ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | بازگرداندن یا تنظیم شیء ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | داده‌های تصویر را جایگزین می‌کند. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | داده‌های تصویر را جایگزین می‌کند. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | داده‌های تصویر را جایگزین می‌کند. |
| [getContentType()](#getContentType--) | یک نوع MIME از تصویر را برمی‌گرداند که در BinaryData (\#getBinaryData.getBinaryData) رمزگذاری شده است. |
| [getWidth()](#getWidth--) | عرض یک تصویر را برمی‌گرداند. |
| [getHeight()](#getHeight--) | ارتفاع یک تصویر را برمی‌گرداند. |
| [getX()](#getX--) | مقدار جابجایی X یک تصویر را برمی‌گرداند. |
| [getY()](#getY--) | مقدار جابجایی Y یک تصویر را برمی‌گرداند. |
| [hashCode()](#hashCode--) | کد هش یک تصویر را برمی‌گرداند. |
| [dispose()](#dispose--) | شیء را از بین می‌برد. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

یک کپی از داده‌های تصویر را برمی‌گرداند. فقط خواندنی  byte[] .

**بازمی‌گرداند:**
byte[] - آرایه‌ای از بایت‌ها
### getImage() {#getImage--}
```
public final IImage getImage()
```

یک کپی از تصویر را برمی‌گرداند. فقط خواندنی [IImage](../../com.aspose.slides/iimage).

**بازمی‌گرداند:**
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

بازگرداندن یا تنظیم شیء ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

این مقدار نشان می‌دهد که این تصویر از SVG ساخته شده است.

**بازمی‌گرداند:**
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```

بازگرداندن یا تنظیم شیء ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage)

--------------------

این مقدار نشان می‌دهد که این تصویر از SVG ساخته شده است.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ISvgImage](../../com.aspose.slides/isvgimage) |  |
### replaceImage(byte[] newImageData) {#replaceImage-byte---}
```
public final void replaceImage(byte[] newImageData)
```

داده‌های تصویر را جایگزین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newImageData | byte[] | داده‌های تصویر جدید. |
### replaceImage(IImage newImage) {#replaceImage-com.aspose.slides.IImage-}
```
public final void replaceImage(IImage newImage)
```

داده‌های تصویر را جایگزین می‌کند. توجه: زمانی که Image یک metafile است - به صورت rasterized تبدیل می‌شود. به جای آن از ReplaceImage(byte[]) استفاده کنید

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newImage | [IImage](../../com.aspose.slides/iimage) | تصویر جدید. |
### replaceImage(IPPImage newImage) {#replaceImage-com.aspose.slides.IPPImage-}
```
public final void replaceImage(IPPImage newImage)
```

داده‌های تصویر را جایگزین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| newImage | [IPPImage](../../com.aspose.slides/ippimage) | IPPImage جدید. |
### getContentType() {#getContentType--}
```
public final String getContentType()
```

یک نوع MIME از تصویر را برمی‌گرداند که در BinaryData (\#getBinaryData.getBinaryData) رمزگذاری شده است. فقط خواندنی String.

**بازمی‌گرداند:**
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```

عرض یک تصویر را برمی‌گرداند. فقط خواندنی  int .

**بازمی‌گرداند:**
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```

ارتفاع یک تصویر را برمی‌گرداند. فقط خواندنی  int .

**بازمی‌گرداند:**
int
### getX() {#getX--}
```
public final int getX()
```

مقدار جابجایی X یک تصویر را برمی‌گرداند. فقط خواندنی  int .

**بازمی‌گرداند:**
int
### getY() {#getY--}
```
public final int getY()
```

مقدار جابجایی Y یک تصویر را برمی‌گرداند. فقط خواندنی  int .

**بازمی‌گرداند:**
int
### hashCode() {#hashCode--}
```
public int hashCode()
```

کد هش یک تصویر را برمی‌گرداند.

**بازمی‌گرداند:**
int - کد هش.
### dispose() {#dispose--}
```
public final void dispose()
```

شیء را از بین می‌برد.