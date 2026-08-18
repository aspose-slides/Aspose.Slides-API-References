---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides for Java API Referansı
description: Etkili 3-B biçimlendirme özelliklerini temsil eden değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ithreedformateffectivedata/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Etkili 3-B boyutlu biçimlendirme özelliklerini temsil eden değiştirilemez nesne.

--------------------

Bu arabirim, [IThreeDFormat](../../com.aspose.slides/ithreedformat) arabirimiyle birlikte, kalıtım uygulanmış etkili biçimlendirme değerlerini döndürmek için kullanılır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 3D konturun genişliğini döndürür. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Ekstrüzyon etkisinin yüksekliğini döndürür. |
| [getDepth()](#getDepth--) | 3D şeklin derinliğini döndürür. |
| [getBevelTop()](#getBevelTop--) | Üst 3D köşe tipini döndürür. |
| [getBevelBottom()](#getBevelBottom--) | Alt 3D köşe tipini döndürür. |
| [getContourColor()](#getContourColor--) | Konturun rengini döndürür. |
| [getExtrusionColor()](#getExtrusionColor--) | Ekstrüzyonun rengini döndürür. |
| [getCamera()](#getCamera--) | Kamera ayarlarını döndürür. |
| [getLightRig()](#getLightRig--) | Işık tipini döndürür. |
| [getMaterial()](#getMaterial--) | Malzemenin tipini döndürür. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


3D konturun genişliğini döndürür. Salt okunur double.

**Döndürür:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Ekstrüzyon etkisinin yüksekliğini döndürür. Salt okunur double.

**Döndürür:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


3D şeklin derinliğini döndürür. Salt okunur double.

**Döndürür:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```


Üst 3D köşe tipini döndürür. Salt okunur [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Döndürür:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


Alt 3D köşe tipini döndürür. Salt okunur [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Döndürür:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```


Konturun rengini döndürür. Salt okunur java.awt.Color.

**Döndürür:**
java.awt.Color
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```


Ekstrüzyonun rengini döndürür. Salt okunur java.awt.Color.

**Döndürür:**
java.awt.Color
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


Kamera ayarlarını döndürür. Salt okunur [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Döndürür:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


Işık tipini döndürür. Salt okunur [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Döndürür:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Malzemenin tipini döndürür. Salt okunur [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Döndürür:**
int