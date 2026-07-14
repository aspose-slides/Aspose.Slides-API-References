---
title: ISlidesPicture
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش یک تصویر در یک ارائه.
type: docs
url: /fa/com.aspose.slides/islidespicture/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface ISlidesPicture extends ISlideComponent
```

نمایش یک تصویر در یک ارائه.
## متدها

| متد | توضیح |
| --- | --- |
| [getImage()](#getImage--) | تصویر جاسازی‌شده را برمی‌گرداند یا تنظیم می‌کند. |
| [setImage(IPPImage value)](#setImage-com.aspose.slides.IPPImage-) | تصویر جاسازی‌شده را برمی‌گرداند یا تنظیم می‌کند. |
| [getLinkPathLong()](#getLinkPathLong--) | آدرس URL تصویر پیوندی را برمی‌گرداند یا تنظیم می‌کند. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | آدرس URL تصویر پیوندی را برمی‌گرداند یا تنظیم می‌کند. |
| [getImageTransform()](#getImageTransform--) | مجموعه‌ای از اثرات تبدیل تصویر را برمی‌گرداند. |
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

مجموعه‌ای از اثرات تبدیل تصویر را برمی‌گرداند. فقط خواندنی [IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection).

**بازگشت:**
[IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)