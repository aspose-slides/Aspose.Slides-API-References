---
title: PVIObject
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: زیرساخت سرویس پایه را برای اشیائی که می‌توانند موضوع ارث‌بری مقدار ویژگی باشند، دربر می‌گیرد.
type: docs
url: /fa/com.aspose.slides/pviobject/
---
**ارث‌بری:**
java.lang.Object

**همهٔ رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

سرویس زیرساخت پایه را برای اشیائی که می‌توانند موضوع ارث‌بری مقدار ویژگی باشند، دربر می‌گیرد.
## متدها

| متد | توضیح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | با شیء مشخص‌شده مقایسه می‌کند. |
| [hashCode()](#hashCode--) | کد هش را برمی‌گرداند. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```


شی Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**باز می‌گرداند:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```


نسخه. فقط خواندنی long.

**باز می‌گرداند:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```


والد IPresentationComponent را برمی‌گرداند. فقط خواندنی [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

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


اسلاید پایه را برمی‌گرداند. فقط خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**باز می‌گرداند:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```


ارائه را برمی‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**باز می‌گرداند:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


با شیء مشخص‌شده مقایسه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| obj | java.lang.Object | شی برای مقایسه. |

**باز می‌گرداند:**
boolean - اگر اشیاء برابر باشند True، در غیر این صورت false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


کد هش را برمی‌گرداند.

**باز می‌گرداند:**
int - کد هش.