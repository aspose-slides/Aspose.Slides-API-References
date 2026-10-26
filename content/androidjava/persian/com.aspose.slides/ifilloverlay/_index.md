---
title: IFillOverlay
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک اثر پوشش پر است.
type: docs
url: /fa/com.aspose.slides/ifilloverlay/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

نمایش‌پوشش پر را توصیف می‌کند. یک نمایش‌پوشش پر می‌تواند برای تعیین پرکردن اضافی برای یک شیء استفاده شود و دو پرکردن را با هم ترکیب کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | قالب پر. |
### getBlend() {#getBlend--}
```
public abstract int getBlend()
```


FillBlendMode. خواندنی/نوشتنی [FillBlendMode](../../com.aspose.slides/fillblendmode).

**بازگشت:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```


FillBlendMode. خواندنی/نوشتنی [FillBlendMode](../../com.aspose.slides/fillblendmode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


قالب پر. فقط‌خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)