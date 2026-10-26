---
title: IImageCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایشگر مجموعه‌ای از PPImage.
type: docs
url: /fa/com.aspose.slides/iimagecollection/
---
**تمام رابط‌های پیاده‌سازی شده:**
com.aspose.slides.IGenericCollection
```
public interface IImageCollection extends IGenericCollection<IPPImage>
```

نمایشگر مجموعه‌ای از PPImage.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | تصویر را بر اساس ایندکس آن بر می‌گرداند. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | یک تصویر به یک ارائه اضافه می‌کند. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | یک تصویر از جریان به یک ارائه اضافه می‌کند. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | یک تصویر را از جریان ایجاد و به ارائه اضافه می‌کند. |
| [addImage(byte[] buffer)](#addImage-byte---) | یک تصویر را از بافر مشخص به یک ارائه اضافه می‌کند. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | یک نسخه از تصویر را از ارائه دیگری اضافه می‌کند. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | یک تصویر را از شیء SVG به یک ارائه اضافه می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPPImage get_Item(int index)
```

تصویر را بر اساس ایندکس آن بر می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس. |

**بازگشت:**
[IPPImage](../../com.aspose.slides/ippimage) - Image.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public abstract IPPImage addImage(IImage image)
```

یک تصویر به یک ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | تصویر برای اضافه کردن.

--------------------

این متد قبل از وارد کردن به ارائه، فایل‌های متافایل WMF/EMF را به تصویر PNG رستر تبدیل می‌کند. |

**بازگشت:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه شده.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public abstract IPPImage addImage(InputStream stream)
```

یک تصویر از جریان به یک ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان برای اضافه کردن تصویر.

--------------------

این متد می‌تواند فایل‌های متافایل WMF/EMF را بدون تبدیل به تصویر PNG رستر به یک ارائه اضافه کند. |

**بازگشت:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه شده.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public abstract IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

یک تصویر را از جریان ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان برای اضافه کردن فایل تصویر. |
| loadingStreamBehavior | int | رفتاری که بر روی جریان اعمال می‌شود. |

**بازگشت:**
[IPPImage](../../com.aspose.slides/ippimage) - اضافه شده [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public abstract IPPImage addImage(byte[] buffer)
```

یک تصویر را از بافر مشخص به یک ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | byte[] | بافر. |

**بازگشت:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه شده.
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public abstract IPPImage addImage(IPPImage imageSource)
```

یک نسخه از تصویر را از ارائه دیگری اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | تصویر منبع. |

**بازگشت:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه شده.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public abstract IPPImage addImage(ISvgImage svgImage)
```

یک تصویر را از شیء تصویر SVG به یک ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | شیء تصویر SVG [ISvgImage](../../com.aspose.slides/isvgimage) |

**بازگشت:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه شده.