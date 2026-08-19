---
title: PVIObject
second_title: مرجع API Aspose.Slides برای Java
description: زیرساخت سرویس پایه را برای اشیائی که می‌توانند موضوع ارث‌برداری مقدار ویژگی باشند، در بر می‌گیرد.
type: docs
url: /fa/com.aspose.slides/pviobject/
---
**ارث‌بری:**
java.lang.Object

**تمام اینترفیس‌های پیاده‌سازی‌شده:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

زیرساخت سرویس پایه را برای اشیائی که می‌توانند موضوع ارث‌برداری مقدار ویژگی باشند، در بر می‌گیرد.
## متدها

| متد | توضیح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | با شیء مشخص مقایسه می‌کند. |
| [hashCode()](#hashCode--) | کد هش را باز می‌گرداند. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را باز می‌گرداند. فقط‌خواندنی IDOMObject.

**باز می‌گرداند:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط‌خواندنی long.

**باز می‌گرداند:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

والد IPresentationComponent را باز می‌گرداند. فقط‌خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**باز می‌گرداند:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**باز می‌گرداند:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

اسلاید پایه را باز می‌گرداند. فقط‌خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**باز می‌گرداند:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

ارائه را باز می‌گرداند. فقط‌خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**باز می‌گرداند:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

با شیء مشخص مقایسه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | شیء برای مقایسه. |

**باز می‌گرداند:**
boolean - True اگر اشیاء برابر باشند، در غیر این صورت False.
### hashCode() {#hashCode--}
```
public int hashCode()
```

کد هش را باز می‌گرداند.

**باز می‌گرداند:**
int - کد هش.