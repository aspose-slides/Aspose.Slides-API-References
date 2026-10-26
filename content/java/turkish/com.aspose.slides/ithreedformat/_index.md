---
title: IThreeDFormat
second_title: Aspose.Slides for Java API Referansı
description: 3D özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/ithreedformat/
---
**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

3D özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | 3D konturun genişliğini alır veya ayarlar. |
| [setContourWidth(double value)](#setContourWidth-double-) | 3D konturun genişliğini alır veya ayarlar. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Ekstrüzyon etkisinin yüksekliğini alır veya ayarlar. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Ekstrüzyon etkisinin yüksekliğini alır veya ayarlar. |
| [getDepth()](#getDepth--) | 3D şeklin derinliğini alır veya ayarlar. |
| [setDepth(double value)](#setDepth-double-) | 3D şeklin derinliğini alır veya ayarlar. |
| [getBevelTop()](#getBevelTop--) | Üst 3D köşe yuvarlamasının tipini alır veya ayarlar. |
| [getBevelBottom()](#getBevelBottom--) | Alt 3D köşe yuvarlamasının tipini alır veya ayarlar. |
| [getContourColor()](#getContourColor--) | Konturun rengini alır veya ayarlar. |
| [getExtrusionColor()](#getExtrusionColor--) | Ekstrüzyonun rengini alır veya ayarlar. |
| [getCamera()](#getCamera--) | Kameranın ayarlarını alır veya ayarlar. |
| [getLightRig()](#getLightRig--) | Işığın tipini alır veya ayarlar. |
| [getMaterial()](#getMaterial--) | Malzemenin tipini alır veya ayarlar. |
| [setMaterial(int value)](#setMaterial-int-) | Malzemenin tipini alır veya ayarlar. |
| [getEffective()](#getEffective--) | Miras uygulanmış etkili 3D biçimlendirme verilerini alır. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

3D konturun genişliğini alır veya ayarlar. Okunabilir/Yazılabilir double.

**Döndürür:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

3D konturun genişliğini alır veya ayarlar. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Ekstrüzyon etkisinin yüksekliğini alır veya ayarlar. Okunabilir/Yazılabilir double.

**Döndürür:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Ekstrüzyon etkisinin yüksekliğini alır veya ayarlar. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

3D şeklin derinliğini alır veya ayarlar. Okunabilir/Yazılabilir double.

**Döndürür:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

3D şeklin derinliğini alır veya ayarlar. Okunabilir/Yazılabilir double.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Üst 3D köşe yuvarlamasının tipini alır veya ayarlar. Salt-okunur [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Döndürür:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Alt 3D köşe yuvarlamasının tipini alır veya ayarlar. Salt-okunur [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Döndürür:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Konturun rengini alır veya ayarlar. Salt-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Ekstrüzyonun rengini alır veya ayarlar. Salt-okunur [IColorFormat](../../com.aspose.slides/icolorformat).

**Döndürür:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Kameranın ayarlarını alır veya ayarlar. Salt-okunur [ICamera](../../com.aspose.slides/icamera).

**Döndürür:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Işığın tipini alır veya ayarlar. Salt-okunur [ILightRig](../../com.aspose.slides/ilightrig).

**Döndürür:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Malzemenin tipini alır veya ayarlar. Okunabilir/Yazılabilir [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Döndürür:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Malzemenin tipini alır veya ayarlar. Okunabilir/Yazılabilir [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

Miras uygulanmış etkili 3D biçimlendirme verilerini alır.

**Döndürür:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).