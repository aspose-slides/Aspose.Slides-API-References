---
title: ImageCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایشگر مجموعه‌ای از PPImage.
type: docs
url: /fa/com.aspose.slides/imagecollection/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

نمایشگر مجموعه‌ای از PPImage.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد تصاویر موجود در مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در اندیس مشخص‌شده را دریافت می‌کند. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | یک نسخه از تصویر را از ارائهٔ دیگر اضافه می‌کند. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | تصویری را به ارائه اضافه می‌کند. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | تصویری را از جریان به ارائه اضافه می‌کند. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | یک تصویر را از جریان ایجاد و به ارائه اضافه می‌کند. |
| [addImage(byte[] buffer)](#addImage-byte---) | تصویری را از بافر مشخص به ارائه اضافه می‌کند. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | تصویری را از شیء Svg به ارائه اضافه می‌کند. |
| [iterator()](#iterator--) | یک شمارنده را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر مجموعه را به آرایهٔ مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همزمان (thread-safe) است. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همزمانی را برمی‌گرداند. |
### size() {#size--}
```
public final int size()
```

تعداد تصاویر موجود در مجموعه را برمی‌گرداند. فقط-خواندنی  int .

**بازمی‌گرداند:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

عنصر موجود در اندیس مشخص‌شده را دریافت می‌کند. فقط-خواندنی [IPPImage](../../com.aspose.slides/ippimage).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازمی‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage)
### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

یک نسخه از تصویر را از ارائهٔ دیگر اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | تصویر منبع. |

**بازمی‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.
### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

تصویری را به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | تصویر برای اضافه کردن. |

--------------------

این متد پرونده‌های متافایل WMF/EMF را پیش از وارد کردن به ارائه به تصویر PNG شطرنجی تبدیل می‌کند. |

**بازمی‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.
### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

تصویری را از جریان به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان برای اضافه کردن تصویر. |

--------------------

این متد می‌تواند پرونده‌های متافایل WMF/EMF را بدون تبدیل به تصویر PNG شطرنجی به ارائه اضافه کند. |

**بازمی‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.
### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

یک تصویر را از جریان ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان برای اضافه کردن فایل تصویر. |
| loadingStreamBehavior | int | رفتاری که بر روی جریان اعمال می‌شود. |

**بازمی‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage) - اضافه‌شده [IPPImage](../../com.aspose.slides/ippimage).
### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

تصویری را از بافر مشخص به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | byte[] | بافر. |

**بازمی‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.
### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

تصویری را از شیء Svg به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | شیء تصویر Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**بازمی‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

یک شمارنده را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند.

**بازمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**بازمی‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر مجموعه را به آرایهٔ مشخص شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همزمان (thread-safe) است. فقط-خواندنی  boolean .

**بازمی‌گرداند:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همزمانی را برمی‌گرداند. فقط-خواندنی  Object .

**بازمی‌گرداند:**
java.lang.Object