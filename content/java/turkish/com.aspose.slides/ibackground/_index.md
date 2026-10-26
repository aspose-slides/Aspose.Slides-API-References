---
title: IBackground
second_title: Aspose.Slides for Java API Referansı
description: Bir slaytın arka planını temsil eder.
type: docs
url: /tr/com.aspose.slides/ibackground/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Bir slaytın arka planını temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getType()](#getType--) | Arka plan dolgusu tipini döndürür. |
| [setType(byte value)](#setType-byte-) | Arka plan dolgusu tipini döndürür. |
| [getFillFormat()](#getFillFormat--) | BackgroundType.OwnBackground doldurması için bir FillFormat döndürür. |
| [getEffectFormat()](#getEffectFormat--) | BackgroundType.OwnBackground doldurması için bir EffectFormat döndürür. |
| [getStyleColor()](#getStyleColor--) | BackgroundType.Themed doldurması için bir ColorFormat döndürür. |
| [getStyleIndex()](#getStyleIndex--) | BackgroundType.Themed doldurması için arka plan tema koleksiyonunda bir indeks döndürür. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | BackgroundType.Themed doldurması için arka plan tema koleksiyonunda bir indeks döndürür. |
| [getEffective()](#getEffective--) | Miras uygulandığında etkili arka plan verilerini alır. |
### getType() {#getType--}
```
public abstract byte getType()
```


Arka plan dolgusu tipini döndürür. Okunur/Yazılır [BackgroundType](../../com.aspose.slides/backgroundtype).

**Döndürür:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Arka plan dolgusu tipini döndürür. Okunur/Yazılır [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


BackgroundType.OwnBackground doldurması için bir FillFormat döndürür. Salt okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


BackgroundType.OwnBackground doldurması için bir EffectFormat döndürür. Salt okunur [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Döndürür:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```


BackgroundType.Themed doldurması için bir ColorFormat döndürür. Salt okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```


BackgroundType.Themed doldurması için arka plan tema koleksiyonunda bir indeks döndürür. 0 hiç dolgu yok demektir. 1..999 - indeks. Okunur/Yazılır int.

**Döndürür:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```


BackgroundType.Themed doldurması için arka plan tema koleksiyonunda bir indeks döndürür. 0 hiç dolgu yok demektir. 1..999 - indeks. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```


Miras uygulandığında etkili arka plan verilerini alır.

**Döndürür:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).