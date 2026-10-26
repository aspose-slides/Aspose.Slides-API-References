---
title: Picture
second_title: مرجع API Aspose.Slides برای Java
description: نمایانگر یک تصویر در ارائه است.
type: docs
url: /fa/com.aspose.slides/picture/
---
**وراثت:**  
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**  
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlidesPicture](../../com.aspose.slides/islidespicture)  
```
public final class Picture implements IPVIObject, ISlidesPicture
```

نمایانگر یک تصویر در یک ارائه.

## متدها

| متد | توضیح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getImage()](#getImage--) | تصویر جاسازی‌شده را بازمی‌گرداند یا تنظیم می‌کند. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | تصویر جاسازی‌شده را بازمی‌گرداند یا تنظیم می‌کند. |
| [getLinkPathLong()](#getLinkPathLong--) | آدرس URL تصویر پیونددهی‌شده را بازمی‌گرداند یا تنظیم می‌کند. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | آدرس URL تصویر پیونددهی‌شده را بازمی‌گرداند یا تنظیم می‌کند. |
| [getImageTransform()](#getImageTransform--) | مجموعه‌ای از افکت‌های تبدیل تصویر را بازمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه را بازمی‌گرداند. |
| [equals(Object obj)](#equals-java.lang.Object-) | با شیء مشخص‌شده مقایسه می‌کند. |
| [hashCode()](#hashCode--) | هش را بازمی‌گرداند. |
| [getSlide()](#getSlide--) | اسلاید والد تصویر را بازمی‌گرداند. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شی Parent_Immediate را بازمی‌گرداند. فقط-خواندنی IDOMObject.

**بازمی‌گرداند:**  
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public final long getVersion()
```

نسخه. فقط-خواندنی long.

**بازمی‌گرداند:**  
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

شی والد IPresentationComponent را بازمی‌گرداند. فقط-خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**بازمی‌گرداند:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getImage() {#getImage--}
```
public final IPPImage getImage()
```

تصویر جاسازی‌شده را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IPPImage](../../com.aspose.slides/ippimage).

**بازمی‌گرداند:**  
[IPPImage](../../com.aspose.slides/ippimage)

### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public final void setImage(IPPImage value)
```

تصویر جاسازی‌شده را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IPPImage](../../com.aspose.slides/ippimage).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

آدرس URL تصویر پیونددهی‌شده را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازمی‌گرداند:**  
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

آدرس URL تصویر پیونددهی‌شده را بازمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public final IImageTransformOperationCollection getImageTransform()
```

مجموعه‌ای از افکت‌های تبدیل تصویر را بازمی‌گرداند. فقط-خواندنی [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**بازمی‌گرداند:**  
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه را بازمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازمی‌گرداند:**  
[IPresentation](../../com.aspose.slides/ipresentation)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

با شیء مشخص‌شده مقایسه می‌کند.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | شی برای مقایسه. |

**بازمی‌گرداند:**  
boolean - در صورتی که اشیاء برابر باشند True، در غیر این صورت False.

### hashCode() {#hashCode--}
```
public int hashCode()
```

هش را بازمی‌گرداند.

**بازمی‌گرداند:**  
int - هش.

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید والد تصویر را بازمی‌گرداند. فقط-خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**بازمی‌گرداند:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)