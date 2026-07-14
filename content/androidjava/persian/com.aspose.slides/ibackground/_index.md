---
title: IBackground
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: پس‌زمینه یک اسلاید را نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/ibackground/
---
**تمام رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)  
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

نمایانگر پس‌زمینه یک اسلاید است.

## متدها

| Method | Description |
| --- | --- |
| [getType()](#getType--) | یک نوع پر کردن پس‌زمینه را برمی‌گرداند. |
| [setType(byte value)](#setType-byte-) | یک نوع پر کردن پس‌زمینه را برمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | یک FillFormat برای پر کردن BackgroundType.OwnBackground برمی‌گرداند. |
| [getEffectFormat()](#getEffectFormat--) | یک EffectFormat برای پر کردن BackgroundType.OwnBackground برمی‌گرداند. |
| [getStyleColor()](#getStyleColor--) | یک ColorFormat برای پر کردن BackgroundType.Themed برمی‌گرداند. |
| [getStyleIndex()](#getStyleIndex--) | یک ایندکس از پر کردن BackgroundType.Themed در مجموعه تم پس‌زمینه برمی‌گرداند. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | یک ایندکس از پر کردن BackgroundType.Themed در مجموعه تم پس‌زمینه برمی‌گرداند. |
| [getEffective()](#getEffective--) | داده‌های پس‌زمینه مؤثر را با اعمال وراثت دریافت می‌کند. |

### getType() {#getType--}
```
public abstract byte getType()
```

یک نوع پر کردن پس‌زمینه را برمی‌گرداند. خواندنی/نوشتنی [BackgroundType](../../com.aspose.slides/backgroundtype).

**بازگشت:**  
byte

### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

یک نوع پر کردن پس‌زمینه را برمی‌گرداند. خواندنی/نوشتنی [BackgroundType](../../com.aspose.slides/backgroundtype).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

یک FillFormat برای پر کردن BackgroundType.OwnBackground برمی‌گرداند. فقط‌خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

یک EffectFormat برای پر کردن BackgroundType.OwnBackground برمی‌گرداند. فقط‌خواندنی [IEffectFormat](../../com.aspose.slides/ieffectformat).

**بازگشت:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

یک ColorFormat برای پر کردن BackgroundType.Themed برمی‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

یک ایندکس از پر کردن BackgroundType.Themed در مجموعه تم پس‌زمینه برمی‌گرداند. 0 به معنی بدون پر کردن است. 1..999 - ایندکس. خواندنی/نوشتنی int.

**بازگشت:**  
int

### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

یک ایندکس از پر کردن BackgroundType.Themed در مجموعه تم پس‌زمینه برمی‌گرداند. 0 به معنی بدون پر کردن است. 1..999 - ایندکس. خواندنی/نوشتنی int.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

داده‌های پس‌زمینه مؤثر را با اعمال وراثت دریافت می‌کند.

**بازگشت:**  
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).