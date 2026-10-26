---
title: IImageCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر مجموعه‌ای از PPImage.
type: docs
url: /fa/com.aspose.slides/iimagecollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

نمایانگر مجموعه‌ای از PPImage.
## متدها

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | تصویر را بر اساس ایندکس آن بازمی‌گرداند. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | افزودن یک تصویر به ارائه. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | افزودن یک تصویر به ارائه از جریان. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | ایجاد و افزودن یک تصویر به ارائه از جریان. |
| [addImage(byte[] buffer)](#addImage-byte---) | تصویر را از بافر مشخص شده به ارائه اضافه می‌کند. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | یک نسخه از تصویر را از ارائه دیگری اضافه می‌کند. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | افزودن یک تصویر به ارائه از شیء SVG. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```


تصویر را بر اساس ایندکس آن بازمی‌گرداند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | ایندکس. |

**بازگرداندن:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```


افزودن یک تصویر به ارائه.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | تصویر برای افزودن.

--------------------

این متد فایل‌های متافایل WMF/EMF را قبل از درج در ارائه به تصویر PNG شطرنجی تبدیل می‌کند. |

**بازگرداندن:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```


افزودن یک تصویر به ارائه از جریان.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | جریان برای افزودن تصویر از آن.

--------------------

این متد می‌تواند فایل‌های متافایل WMF/EMF را بدون تبدیل به تصویر PNG شطرنجی به ارائه اضافه کند. |

**بازگرداندن:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```


ایجاد و افزودن یک تصویر به ارائه از جریان.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | جریان برای افزودن فایل تصویر از آن. |
| loadingStreamBehavior | int | رفتاری که بر روی جریان اعمال می‌شود. |

**بازگرداندن:**
[IPPImage](../../com.aspose.slides/ippimage) - [IPPImage](../../com.aspose.slides/ippimage) اضافه‌شده.
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```


تصویر را از بافر مشخص شده به ارائه اضافه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| buffer | byte[] | بافر. |

**بازگرداندن:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```


یک نسخه از تصویر را از ارائه دیگری اضافه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | تصویر منبع. |

**بازگرداندن:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```


افزودن یک تصویر به ارائه از شیء SVG.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | شیء تصویر SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**بازگرداندن:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.