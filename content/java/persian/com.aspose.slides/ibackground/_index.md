---
title: IBackground
second_title: مرجع API Aspose.Slides برای جاوا
description: پس‌زمینهٔ اسلاید را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/ibackground/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

پس‌زمینه یک اسلاید را نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | یک نوع پرشدن پس‌زمینه را برمی‌گرداند. |
| [setType(byte value)](#setType-byte-) | یک نوع پرشدن پس‌زمینه را برمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | یک FillFormat برای پرشدن BackgroundType.OwnBackground برمی‌گرداند. |
| [getEffectFormat()](#getEffectFormat--) | یک EffectFormat برای پرشدن BackgroundType.OwnBackground برمی‌گرداند. |
| [getStyleColor()](#getStyleColor--) | یک ColorFormat برای پرشدن BackgroundType.Themed برمی‌گرداند. |
| [getStyleIndex()](#getStyleIndex--) | یک شاخص از پرشدن BackgroundType.Themed در مجموعهٔ تم پس‌زمینه برمی‌گرداند. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | یک شاخص از پرشدن BackgroundType.Themed در مجموعهٔ تم پس‌زمینه برمی‌گرداند. |
| [getEffective()](#getEffective--) | دادهٔ مؤثر پس‌زمینه را با درنظرگیری وراثت دریافت می‌کند. |
### getType() {#getType--}
```
public abstract byte getType()
```

یک نوع پرشدن پس‌زمینه را برمی‌گرداند. خواندنی/نوشتنی [BackgroundType](../../com.aspose.slides/backgroundtype).

**بازگشت:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

یک نوع پرشدن پس‌زمینه را برمی‌گرداند. خواندنی/نوشتنی [BackgroundType](../../com.aspose.slides/backgroundtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

یک FillFormat برای پرشدن BackgroundType.OwnBackground برمی‌گرداند. فقط‌خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

یک EffectFormat برای پرشدن BackgroundType.OwnBackground برمی‌گرداند. فقط‌خواندنی [IEffectFormat](../../com.aspose.slides/ieffectformat).

**بازگشت:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

یک ColorFormat برای پرشدن BackgroundType.Themed برمی‌گرداند. فقط‌خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

یک شاخص از پرشدن BackgroundType.Themed در مجموعهٔ تم پس‌زمینه را برمی‌گرداند. 0 به معنی عدم پرشدن است. 1..999 - شاخص. خواندنی/نوشتنی int.

**بازگشت:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

یک شاخص از پرشدن BackgroundType.Themed در مجموعهٔ تم پس‌زمینه را برمی‌گرداند. 0 به معنی عدم پرشدن است. 1..999 - شاخص. خواندنی/نوشتنی int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

دادهٔ مؤثر پس‌زمینه را با اعمال وراثت دریافت می‌کند.

**بازگشت:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - یک [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).