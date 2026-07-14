---
title: Background
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: پس‌زمینه یک اسلاید را نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/background/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject  
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

پس‌زمینهٔ یک اسلاید را نمایندگی می‌کند.

## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | یک نوع پر کردن پس‌زمینه را برمی‌گرداند. |
| [setType(byte value)](#setType-byte-) | یک نوع پر کردن پس‌زمینه را برمی‌گرداند. |
| [getFillFormat()](#getFillFormat--) | یک FillFormat برای پر کردن BackgroundType.OwnBackground برمی‌گرداند. |
| [getEffectFormat()](#getEffectFormat--) | یک EffectFormat برای پر کردن BackgroundType.OwnBackground برمی‌گرداند. |
| [getStyleColor()](#getStyleColor--) | یک ColorFormat برای پر کردن BackgroundType.Themed برمی‌گرداند. |
| [getStyleIndex()](#getStyleIndex--) | یک ایندکس از پر کردن BackgroundType.Themed در مجموعهٔ تم پس‌زمینه را برمی‌گرداند. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | یک ایندکس از پر کردن BackgroundType.Themed در مجموعهٔ تم پس‌زمینه را برمی‌گرداند. |
| [getEffective()](#getEffective--) | دادهٔ پس‌زمینهٔ مؤثر با اعمال وراثت را دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | اسلاید مادر یک شکل را برمی‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائهٔ مادر یک اسلاید را برمی‌گرداند. |

### getType() {#getType--}
```
public final byte getType()
```

یک نوع پر کردن پس‌زمینه را برمی‌گرداند. قابل خواندن/نوشتن [BackgroundType](../../com.aspose.slides/backgroundtype).

**بازگشت:**  
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

یک نوع پر کردن پس‌زمینه را برمی‌گرداند. قابل خواندن/نوشتن [BackgroundType](../../com.aspose.slides/backgroundtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

یک FillFormat برای پر کردن BackgroundType.OwnBackground برمی‌گرداند. فقط خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

یک EffectFormat برای پر کردن BackgroundType.OwnBackground برمی‌گرداند. فقط خواندنی [IEffectFormat](../../com.aspose.slides/ieffectformat).

**بازگشت:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

یک ColorFormat برای پر کردن BackgroundType.Themed برمی‌گرداند. فقط خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

یک ایندکس از پر کردن BackgroundType.Themed در مجموعهٔ تم پس‌زمینه را برمی‌گرداند. 0 به معنی عدم پر کردن است. 1..999 - ایندکس. قابل خواندن/نوشتن int.

**بازگشت:**  
int

### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

یک ایندکس از پر کردن BackgroundType.Themed در مجموعهٔ تم پس‌زمینه را برمی‌گرداند. 0 به معنی عدم پر کردن است. 1..999 - ایندکس. قابل خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

دادهٔ پس‌زمینهٔ مؤثر با اعمال وراثت را دریافت می‌کند.

--------------------

> ```
> This example demonstrates getting effective background properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**  
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - یک [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

نسخه. فقط خواندنی long.

**بازگشت:**  
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

یک شیء Parent_Immediate را برمی‌گرداند. فقط خواندنی IDOMObject.

**بازگشت:**  
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

اسلاید مادر یک شکل را برمی‌گرداند. فقط خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**بازگشت:**  
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

ارائهٔ مادر یک اسلاید را برمی‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**  
[Presentation](../../com.aspose.slides/presentation)