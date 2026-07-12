---
title: Format
second_title: Aspose.Slides for Android via Java API Referansı
description: Grafik formatı özelliklerini temsil eder.
type: docs
url: /tr/com.aspose.slides/format/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IFormat](../../com.aspose.slides/iformat)
```
public final class Format extends PVIObject implements IFormat
```

Grafik formatı özelliklerini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getFill()](#getFill--) | Bir grafiğin dolgu stili özelliklerini döndürür. |
| [getLine()](#getLine--) | Bir grafiğin çizgi stili özelliklerini döndürür. |
| [getEffect()](#getEffect--) | Bir grafikte kullanılan efektleri döndürür. |
| [getEffect3D()](#getEffect3D--) | Bir grafiğin 3B formatını döndürür. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Sürüm. Yalnızca okunabilir long.

**Döndürür:**
long
### getFill() {#getFill--}
```
public final IFillFormat getFill()
```


Bir grafiğin dolgu stili özelliklerini döndürür. Yalnızca okunabilir [IFillFormat](../../com.aspose.slides/ifillformat).

**Döndürür:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getLine() {#getLine--}
```
public final ILineFormat getLine()
```


Bir grafiğin çizgi stili özelliklerini döndürür. Yalnızca okunabilir [ILineFormat](../../com.aspose.slides/ilineformat).

**Döndürür:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getEffect() {#getEffect--}
```
public final IEffectFormat getEffect()
```


Bir grafikte kullanılan efektleri döndürür. Yalnızca okunabilir [IEffectFormat](../../com.aspose.slides/ieffectformat).

**Döndürür:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getEffect3D() {#getEffect3D--}
```
public final IThreeDFormat getEffect3D()
```


Bir grafiğin 3B formatını döndürür. Yalnızca okunabilir [IThreeDFormat](../../com.aspose.slides/ithreedformat).

**Döndürür:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)