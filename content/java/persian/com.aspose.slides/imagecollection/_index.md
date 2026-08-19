---
title: ImageCollection
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر مجموعه‌ای از PPImage.
type: docs
url: /fa/com.aspose.slides/imagecollection/
---
**ارث‌بری:**  
java.lang.Object, com.aspose.slides.DomObject

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IImageCollection](../../com.aspose.slides/iimagecollection)  
```
public final class ImageCollection extends DomObject<Presentation> implements IImageCollection
```

نمایش‌دهندهٔ مجموعه‌ای از PPImage.

## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد تصویرها در مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عنصر را در اندیس مشخص‌شده دریافت می‌کند. |
| [addImage(IPPImage imageSource)](#addImage-com.aspose.slides.IPPImage-) | یک کپی از تصویر را از یک ارائه دیگر اضافه می‌کند. |
| [addImage(IImage image)](#addImage-com.aspose.slides.IImage-) | یک تصویر به ارائه اضافه می‌کند. |
| [addImage(InputStream stream)](#addImage-java.io.InputStream-) | یک تصویر را از جریان به ارائه اضافه می‌کند. |
| [addImage(InputStream stream, int loadingStreamBehavior)](#addImage-java.io.InputStream-int-) | یک تصویر را از جریان ایجاد و به ارائه اضافه می‌کند. |
| [addImage(byte[] buffer)](#addImage-byte---) | یک تصویر را از بافر مشخص‌شده به ارائه اضافه می‌کند. |
| [addImage(ISvgImage svgImage)](#addImage-com.aspose.slides.ISvgImage-) | یک تصویر را از شیء Svg به ارائه اضافه می‌کند. |
| [iterator()](#iterator--) | یک شمارشگر که در مجموعه مرور می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک پیمایشگر جاوا برای کل مجموعه را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (امنیت‌پذیر). |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |

### size() {#size--}
```
public final int size()
```

تعداد تصویرها در مجموعه را برمی‌گرداند. فقط‌خواندنی int .

**باز می‌گرداند:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IPPImage get_Item(int index)
```

عنصر را در اندیس مشخص‌شده دریافت می‌کند. فقط‌خواندنی [IPPImage](../../com.aspose.slides/ippimage).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**باز می‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage)

### addImage(IPPImage imageSource) {#addImage-com.aspose.slides.IPPImage-}
```
public final IPPImage addImage(IPPImage imageSource)
```

یک کپی از تصویر را از یک ارائه دیگر اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| imageSource | [IPPImage](../../com.aspose.slides/ippimage) | تصویر منبع. |

**باز می‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.

### addImage(IImage image) {#addImage-com.aspose.slides.IImage-}
```
public final IPPImage addImage(IImage image)
```

یک تصویر به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| image | [IImage](../../com.aspose.slides/iimage) | تصویر برای افزودن. |

--------------------
این متد فایل‌های متافایل WMF/EMF را به تصویر PNG شطرنجی تبدیل می‌کند قبل از وارد کردن به یک ارائه. |

**باز می‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.

### addImage(InputStream stream) {#addImage-java.io.InputStream-}
```
public final IPPImage addImage(InputStream stream)
```

یک تصویر را از جریان به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان برای افزودن تصویر از آن. |

--------------------
این متد می‌تواند فایل‌های متافایل WMF/EMF را بدون تبدیل به تصویر PNG شطرنجی به یک ارائه اضافه کند. |

**باز می‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.

### addImage(InputStream stream, int loadingStreamBehavior) {#addImage-java.io.InputStream-int-}
```
public final IPPImage addImage(InputStream stream, int loadingStreamBehavior)
```

یک تصویر را از جریان ایجاد و به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | java.io.InputStream | جریان برای افزودن فایل تصویر از آن. |
| loadingStreamBehavior | int | رفتاری که بر روی جریان اعمال خواهد شد. |

**باز می‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage) - اضافه‌شده [IPPImage](../../com.aspose.slides/ippimage).

### addImage(byte[] buffer) {#addImage-byte---}
```
public final IPPImage addImage(byte[] buffer)
```

یک تصویر را از بافر مشخص‌شده به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | byte[] | بافر. |

**باز می‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.

### addImage(ISvgImage svgImage) {#addImage-com.aspose.slides.ISvgImage-}
```
public final IPPImage addImage(ISvgImage svgImage)
```

یک تصویر را از شیء Svg به ارائه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | شیء تصویر Svg [ISvgImage](../../com.aspose.slides/isvgimage) |

**باز می‌گرداند:**
[IPPImage](../../com.aspose.slides/ippimage) - تصویر اضافه‌شده.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iterator()
```

یک شمارشگر که در مجموعه مرور می‌کند را برمی‌گرداند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPPImage> iteratorJava()
```

یک پیمایشگر جاوا برای کل مجموعه را برمی‌گرداند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPPImage> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (امنیت‌پذیر). فقط‌خواندنی boolean .

**باز می‌گرداند:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط‌خواندنی Object .

**باز می‌گرداند:**
java.lang.Object