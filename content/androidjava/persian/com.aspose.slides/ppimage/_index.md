---
title: PPImage
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک تصویر را در یک ارائه توصیف می‌کند.
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

یک تصویر را در یک ارائه توصیف می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getBinaryData()](#getBinaryData--) | کپی داده‌های یک تصویر را برمی‌گرداند. |
| [getImage()](#getImage--) | کپی یک تصویر را برمی‌گرداند. |
| [getSvgImage()](#getSvgImage--) | شی ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) را برمی‌گرداند یا تنظیم می‌کند. |
| [setSvgImage(ISvgImage value)](#setSvgImage-com.aspose.slides.ISvgImage-) | شی ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) را برمی‌گرداند یا تنظیم می‌کند. |
| [replaceImage(byte[] newImageData)](#replaceImage-byte---) | داده‌های تصویر را جایگزین می‌کند. |
| [replaceImage(IImage newImage)](#replaceImage-com.aspose.slides.IImage-) | داده‌های تصویر را جایگزین می‌کند. |
| [replaceImage(IPPImage newImage)](#replaceImage-com.aspose.slides.IPPImage-) | داده‌های تصویر را جایگزین می‌کند. |
| [getContentType()](#getContentType--) | نوع MIME یک تصویر را برمی‌گرداند که در BinaryData (\#getBinaryData.getBinaryData) رمزگذاری شده است. |
| [getWidth()](#getWidth--) | عرض یک تصویر را برمی‌گرداند. |
| [getHeight()](#getHeight--) | ارتفاع یک تصویر را برمی‌گرداند. |
| [getX()](#getX--) | مقدار افست X یک تصویر را برمی‌گرداند. |
| [getY()](#getY--) | مقدار افست Y یک تصویر را برمی‌گرداند. |
| [hashCode()](#hashCode--) | کد هش یک تصویر را برمی‌گرداند. |
| [dispose()](#dispose--) | شی را تخلیه می‌کند. |
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

کپی داده‌های یک تصویر را برمی‌گرداند. فقط‌خواندنی  byte[] .

**بازگرداندن:**  
byte[] - آرایه‌ای از بایت‌ها
### getImage() {#getImage--}
```
public final IImage getImage()
```

کپی یک تصویر را برمی‌گرداند. فقط‌خواندنی [IImage](../../com.aspose.slides/iimage).

**بازگرداندن:**  
[IImage](../../com.aspose.slides/iimage)
### getSvgImage() {#getSvgImage--}
```
public final ISvgImage getSvgImage()
```

شی ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) را برمی‌گرداند یا تنظیم می‌کند.

--------------------

این مقدار نشان می‌دهد که این تصویر از SVG ایجاد شده است.

**بازگرداندن:**  
[ISvgImage](../../com.aspose.slides/isvgimage)
### setSvgImage(ISvgImage value) {#setSvgImage-com.aspose.slides.ISvgImage-}
```
public final void setSvgImage(ISvgImage value)
```

شی ISvgImage [ISvgImage](../../com.aspose.slides/isvgimage) را برمی‌گرداند یا تنظیم می‌کند.

--------------------

این مقدار نشان می‌دهد که این تصویر از SVG ایجاد شده است.

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

داده‌های تصویر را جایگزین می‌کند. توجه: وقتی Image یک متافایل است - به رستر تبدیل می‌شود. به‌جای آن از ReplaceImage(byte[]) استفاده کنید.

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

نوع MIME یک تصویر را برمی‌گرداند که در BinaryData (\#getBinaryData.getBinaryData) رمزگذاری شده است. فقط‌خواندنی String.

**بازگرداندن:**  
java.lang.String
### getWidth() {#getWidth--}
```
public final int getWidth()
```

عرض یک تصویر را برمی‌گرداند. فقط‌خواندنی  int .

**بازگرداندن:**  
int
### getHeight() {#getHeight--}
```
public final int getHeight()
```

ارتفاع یک تصویر را برمی‌گرداند. فقط‌خواندنی  int .

**بازگرداندن:**  
int
### getX() {#getX--}
```
public final int getX()
```

مقدار افست X یک تصویر را برمی‌گرداند. فقط‌خواندنی  int .

**بازگرداندن:**  
int
### getY() {#getY--}
```
public final int getY()
```

مقدار افست Y یک تصویر را برمی‌گرداند. فقط‌خواندنی  int .

**بازگرداندن:**  
int
### hashCode() {#hashCode--}
```
public int hashCode()
```

کد هش یک تصویر را برمی‌گرداند.

**بازگرداندن:**  
int - کد هش.
### dispose() {#dispose--}
```
public final void dispose()
```

شی را تخلیه می‌کند.