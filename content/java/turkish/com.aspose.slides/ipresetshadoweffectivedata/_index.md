---
title: IPresetShadowEffectiveData
second_title: Aspose.Slides for Java API Referansı
description: Ön tanımlı gölge etkisini temsil eden değiştirilemez nesne.
type: docs
url: /tr/com.aspose.slides/ippresetshadoweffectivedata/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IPresetShadowEffectiveData extends IEffectEffectiveData
```

Ön Tanımlı Gölge etkisini temsil eden değiştirilemez nesne.

## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDirection()](#getDirection--) | Gölgenin yönü. |
| [getDistance()](#getDistance--) | Gölgenin mesafesi. |
| [getShadowColor()](#getShadowColor--) | Gölgenin rengi. |
| [getPreset()](#getPreset--) | Ön ayar. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Gölgenin yönü. Salt okunur float.

**Döndürür:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Gölgenin mesafesi. Salt okunur double.

**Döndürür:**
double
### getShadowColor() {#getShadowColor--}
```
public abstract Color getShadowColor()
```

Gölgenin rengi. Salt okunur java.awt.Color.

**Döndürür:**
java.awt.Color
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Ön ayar. Salt okunur [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Döndürür:**
int