---
title: Background
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر پس‌زمینه یک اسلاید.
type: docs
url: /fa/com.aspose.slides/background/
---
**ارث‌بری:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**تمامی رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject  
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

نمایانگر پس‌زمینه یک اسلاید است.

## متدها

| متد | توضیح |
| --- | --- |
| [getType()](#getType--) | یک نوع پر کردن پس‌زمینه را باز می‌گرداند. |
| [setType(byte value)](#setType-byte-) | یک نوع پر کردن پس‌زمینه را باز می‌گرداند. |
| [getFillFormat()](#getFillFormat--) | یک FillFormat برای پر کردن BackgroundType.OwnBackground را باز می‌گرداند. |
| [getEffectFormat()](#getEffectFormat--) | یک EffectFormat برای پر کردن BackgroundType.OwnBackground را باز می‌گرداند. |
| [getStyleColor()](#getStyleColor--) | یک ColorFormat برای پر کردن BackgroundType.Themed را باز می‌گرداند. |
| [getStyleIndex()](#getStyleIndex--) | یک شاخص از پر کردن BackgroundType.Themed در مجموعه تم پس‌زمینه را باز می‌گرداند. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | یک شاخص از پر کردن BackgroundType.Themed در مجموعه تم پس‌زمینه را باز می‌گرداند. |
| [getEffective()](#getEffective--) | داده‌های پس‌زمینه مؤثر را با اعمال ارث‌بری دریافت می‌کند. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | اسلاید والد یک شکل را باز می‌گرداند. |
| [getPresentation()](#getPresentation--) | ارائه والد یک اسلاید را باز می‌گرداند. |

### getType() {#getType--}
```
public final byte getType()
```

یک نوع پر کردن پس‌زمینه را باز می‌گرداند. خواندنی/نوشتنی [BackgroundType](../../com.aspose.slides/backgroundtype).

**بازگشت:**  
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

یک نوع پر کردن پس‌زمینه را باز می‌گرداند. خواندنی/نوشتنی [BackgroundType](../../com.aspose.slides/backgroundtype).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

یک FillFormat برای پر کردن BackgroundType.OwnBackground را باز می‌گرداند. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

یک EffectFormat برای پر کردن BackgroundType.OwnBackground را باز می‌گرداند. فقط-خواندنی [IEffectFormat](../../com.aspose.slides/ieffectformat).

**بازگشت:**  
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

یک ColorFormat برای پر کردن BackgroundType.Themed را باز می‌گرداند. فقط-خواندنی [IColorFormat](../../com.aspose.slides/icolorformat).

**بازگشت:**  
[IColorFormat](../../com.aspose.slides/icolorformat)

### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

یک شاخص از پر کردن BackgroundType.Themed در مجموعه تم پس‌زمینه را باز می‌گرداند. 0 به معنای عدم وجود پر کردن. 1..999 - شاخص. خواندنی/نوشتنی int.

**بازگشت:**  
int

### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

یک شاخص از پر کردن BackgroundType.Themed در مجموعه تم پس‌زمینه را باز می‌گرداند. 0 به معنای عدم وجود پر کردن. 1..999 - شاخص. خواندنی/نوشتنی int.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

داده‌های پس‌زمینه مؤثر را با اعمال ارث‌بری دریافت می‌کند.

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

نسخه. فقط-خواندنی long.

**بازگشت:**  
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را باز می‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**  
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

اسلاید والد یک شکل را باز می‌گرداند. فقط-خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**بازگشت:**  
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

ارائه والد یک اسلاید را باز می‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازگشت:**  
[Presentation](../../com.aspose.slides/presentation)