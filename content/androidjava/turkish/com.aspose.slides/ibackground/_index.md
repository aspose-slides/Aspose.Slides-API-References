---
title: IBackground
second_title: Aspose.Slides for Android Java API Referansı
description: Bir slaytın arka planını temsil eder.
type: docs
url: /tr/com.aspose.slides/ibackground/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

Bir slaytın arka planını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Arka plan doldurma türünü döndürür. |
| [setType(byte value)](#setType-byte-) | Arka plan doldurma türünü döndürür. |
| [getFillFormat()](#getFillFormat--) | BackgroundType.OwnBackground doldurması için bir FillFormat döndürür. |
| [getEffectFormat()](#getEffectFormat--) | BackgroundType.OwnBackground doldurması için bir EffectFormat döndürür. |
| [getStyleColor()](#getStyleColor--) | BackgroundType.Themed doldurması için bir ColorFormat döndürür. |
| [getStyleIndex()](#getStyleIndex--) | Arka plan tema koleksiyonundaki BackgroundType.Themed doldurmasının dizinini döndürür. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | Arka plan tema koleksiyonundaki BackgroundType.Themed doldurmasının dizinini döndürür. |
| [getEffective()](#getEffective--) | Kalıtım uygulanmış etkili arka plan verilerini alır. |
### getType() {#getType--}
```
public abstract byte getType()
```


Arka plan doldurma türünü döndürür. Okunur/Yazılır [BackgroundType](../../com.aspose.slides/backgroundtype).

**Döndürür:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Arka plan doldurma türünü döndürür. Okunur/Yazılır [BackgroundType](../../com.aspose.slides/backgroundtype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


BackgroundType.OwnBackground doldurması için bir FillFormat döndürür. Salt Okunur [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


BackgroundType.OwnBackground doldurması için bir EffectFormat döndürür. Salt Okunur [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Döndürür:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```


BackgroundType.Themed doldurması için bir ColorFormat döndürür. Salt Okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```


Arka plan tema koleksiyonundaki BackgroundType.Themed doldurmasının dizinini döndürür. 0 hiçbir doldurma yok demektir. 1..999 - dizin. Okunur/Yazılır int.

**Döndürür:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```


Arka plan tema koleksiyonundaki BackgroundType.Themed doldurmasının dizinini döndürür. 0 hiçbir doldurma yok demektir. 1..999 - dizin. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```


Kalıtım uygulanmış etkili arka plan verilerini alır.

**Döndürür:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).