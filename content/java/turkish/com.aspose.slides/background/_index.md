---
title: Background
second_title: Aspose.Slides for Java API Referansı
description: Bir slaytın arka planını temsil eder.
type: docs
url: /tr/com.aspose.slides/background/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

Bir slaytın arka planını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Arka plan doldurma türünü döndürür. |
| [setType(byte value)](#setType-byte-) | Arka plan doldurma türünü döndürür. |
| [getFillFormat()](#getFillFormat--) | BackgroundType.OwnBackground doldurma için bir FillFormat döndürür. |
| [getEffectFormat()](#getEffectFormat--) | BackgroundType.OwnBackground doldurma için bir EffectFormat döndürür. |
| [getStyleColor()](#getStyleColor--) | BackgroundType.Themed doldurma için bir ColorFormat döndürür. |
| [getStyleIndex()](#getStyleIndex--) | BackgroundType.Themed doldurma için arka plan tema koleksiyonunda bir indeks döndürür. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | BackgroundType.Themed doldurma için arka plan tema koleksiyonunda bir indeks döndürür. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili arka plan verilerini alır. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Bir şeklin üst slaydını döndürür. |
| [getPresentation()](#getPresentation--) | Bir slaydın üst sunumunu döndürür. |
### getType() {#getType--}
```
public final byte getType()
```

Arka plan doldurma türünü döndürür. Okuma/Yazma [BackgroundType](../../com.aspose.slides/backgroundtype).

**Döndürür:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Arka plan doldurma türünü döndürür. Okuma/Yazma [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

BackgroundType.OwnBackground doldurma için bir FillFormat döndürür. Salt-okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

BackgroundType.OwnBackground doldurma için bir EffectFormat döndürür. Salt-okunur [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Döndürür:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

BackgroundType.Themed doldurma için bir ColorFormat döndürür. Salt-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

BackgroundType.Themed doldurma için arka plan tema koleksiyonunda bir indeks döndürür. 0, dolgu olmadığını ifade eder. 1..999 - indeks. Okuma/Yazma int.

**Döndürür:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

BackgroundType.Themed doldurma için arka plan tema koleksiyonunda bir indeks döndürür. 0, dolgu olmadığını ifade eder. 1..999 - indeks. Okuma/Yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

Kalıtım uygulanmış etkili arka plan verilerini alır.

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

**Döndürür:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versiyon. Salt-okunur long.

**Döndürür:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

Bir şeklin üst slaydını döndürür. Salt-okunur [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Döndürür:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

Bir slaydın üst sunumunu döndürür. Salt-okunur [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[Presentation](../../com.aspose.slides/presentation)