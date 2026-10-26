---
title: Background
second_title: Aspose.Slides Android için Java API Referansı aracılığıyla
description: Bir slaydın arka planını temsil eder.
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

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Arka plan dolgu tipini döndürür. |
| [setType(byte value)](#setType-byte-) | Arka plan dolgu tipini döndürür. |
| [getFillFormat()](#getFillFormat--) | BackgroundType.OwnBackground dolgu için bir FillFormat döndürür. |
| [getEffectFormat()](#getEffectFormat--) | BackgroundType.OwnBackground dolgu için bir EffectFormat döndürür. |
| [getStyleColor()](#getStyleColor--) | BackgroundType.Themed dolgu için bir ColorFormat döndürür. |
| [getStyleIndex()](#getStyleIndex--) | Arka plan tema koleksiyonundaki BackgroundType.Themed dolgunun dizinini döndürür. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Arka plan tema koleksiyonundaki BackgroundType.Themed dolgunun dizinini döndürür. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili arka plan verilerini alır. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Bir şeklin ebeveyn slaytını döndürür. |
| [getPresentation()](#getPresentation--) | Bir slaydın ebeveyn sunumunu döndürür. |
### getType() {#getType--}
```
public final byte getType()
```


Arka plan dolgu tipini döndürür. Okunur/Yazılır [BackgroundType](../../com.aspose.slides/backgroundtype).

**Döndürür:**
byte
### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```


Arka plan dolgu tipini döndürür. Okunur/Yazılır [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


BackgroundType.OwnBackground dolgu için bir FillFormat döndürür. Sadece okuma [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```


BackgroundType.OwnBackground dolgu için bir EffectFormat döndürür. Sadece okuma [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Döndürür:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```


BackgroundType.Themed dolgu için bir ColorFormat döndürür. Sadece okuma [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```


Arka plan tema koleksiyonundaki BackgroundType.Themed dolgunun dizinini döndürür. 0 dolgu yok demektir. 1..999 - dizin. Okunur/Yazılır int.

**Döndürür:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```


Arka plan tema koleksiyonundaki BackgroundType.Themed dolgunun dizinini döndürür. 0 dolgu yok demektir. 1..999 - dizin. Okunur/Yazılır int.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```


Kalitim uygulanmış etkili arka plan verilerini alır.

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


Versiyon. Sadece okuma long.

**Döndürür:**
long
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate nesnesini döndürür. Sadece okuma IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```


Bir şeklin ebeveyn slaytını döndürür. Sadece okuma [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Döndürür:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```


Bir slaydın ebeveyn sunumunu döndürür. Sadece okuma [IPresentation](../../com.aspose.slides/ipresentation).

**Döndürür:**
[Presentation](../../com.aspose.slides/presentation)