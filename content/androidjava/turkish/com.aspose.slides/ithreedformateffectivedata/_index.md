---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides for Android Java API Referansı
description: Etkili 3-D biçimlendirme özelliklerini temsil eden değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ithreedformateffectivedata/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Etkili 3-D biçimlendirme özelliklerini temsil eden değiştirilemez nesne.

--------------------

Bu arabirim, [IThreeDFormat](../../com.aspose.slides/ithreedformat) arabirimiyle birlikte, kalıtım uygulanmış etkili biçimlendirme değerlerini döndürmek için kullanılır.
## Methods

| Yöntem | Açıklama |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 3D konturunun genişliğini döndürür. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Ekstrüzyon etkisinin yüksekliğini döndürür. |
| [getDepth()](#getDepth--) | 3D şeklin derinliğini döndürür. |
| [getBevelTop()](#getBevelTop--) | Üst 3D köşegenin tipini döndürür. |
| [getBevelBottom()](#getBevelBottom--) | Alt 3D köşegenin tipini döndürür. |
| [getContourColor()](#getContourColor--) | Konturun rengini döndürür. |
| [getExtrusionColor()](#getExtrusionColor--) | Ekstrüzyonun rengini döndürür. |
| [getCamera()](#getCamera--) | Kameranın ayarlarını döndürür. |
| [getLightRig()](#getLightRig--) | Işığın tipini döndürür. |
| [getMaterial()](#getMaterial--) | Malzemenin tipini döndürür. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


3D konturunun genişliğini döndürür. Salt-okunur double.

**Döndürür:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Ekstrüzyon etkisinin yüksekliğini döndürür. Salt-okunur double.

**Döndürür:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


3D şeklin derinliğini döndürür. Salt-okunur double.

**Döndürür:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```


Üst 3D köşegenin tipini döndürür. Salt-okunur [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Döndürür:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


Alt 3D köşegenin tipini döndürür. Salt-okunur [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Döndürür:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```


Konturun rengini döndürür. Salt-okunur java.lang.Integer.

**Döndürür:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```


Ekstrüzyonun rengini döndürür. Salt-okunur java.lang.Integer.

**Döndürür:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


Kameranın ayarlarını döndürür. Salt-okunur [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Döndürür:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


Işığın tipini döndürür. Salt-okunur [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Döndürür:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Malzemenin tipini döndürür. Salt-okunur [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Döndürür:**
int