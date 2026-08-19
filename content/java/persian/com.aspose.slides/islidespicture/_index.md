---
title: ISlidesPicture
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک تصویر در یک ارائه است.
type: docs
url: /fa/com.aspose.slides/islidespicture/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

نمایانگر یک تصویر در یک ارائه است.
## متدها

| متد | توضیح |
| --- | --- |
| [getImage()](#getImage--) | تصویر جاسازی‌شده را برمی‌گرداند یا تنظیم می‌کند. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | تصویر جاسازی‌شده را برمی‌گرداند یا تنظیم می‌کند. |
| [getLinkPathLong()](#getLinkPathLong--) | آدرس URL تصویر پیوندی را برمی‌گرداند یا تنظیم می‌کند. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | آدرس URL تصویر پیوندی را برمی‌گرداند یا تنظیم می‌کند. |
| [getImageTransform()](#getImageTransform--) | مجموعه اثرات تبدیل تصویر را برمی‌گرداند. |
### getImage() {#getImage--}
```
public abstract IPPImage getImage()
```


تصویر جاسازی‌شده را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IPPImage](../../com.aspose.slides/ippimage).

**بازگشت:**
[IPPImage](../../com.aspose.slides/ippimage)
### setImage(IPPImage value) {#setImage-com.aspose.slides.IPPImage-}
```
public abstract void setImage(IPPImage value)
```


تصویر جاسازی‌شده را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IPPImage](../../com.aspose.slides/ippimage).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IPPImage](../../com.aspose.slides/ippimage) |  |

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


آدرس URL تصویر پیوندی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


آدرس URL تصویر پیوندی را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getImageTransform() {#getImageTransform--}
```
public abstract IImageTransformOperationCollection getImageTransform()
```


مجموعه اثرات تبدیل تصویر را برمی‌گرداند. فقط-خواندنی [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**بازگشت:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)