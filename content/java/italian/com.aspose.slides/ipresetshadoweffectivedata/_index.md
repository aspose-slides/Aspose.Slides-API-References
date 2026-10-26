---
title: IPresetShadowEffectiveData
second_title: Riferimento API Aspose.Slides per Java
description: Oggetto immutabile che rappresenta un effetto Ombra predefinito.
type: docs
url: /it/com.aspose.slides/ipresetshadoweffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IPresetShadowEffectiveData extends IEffectEffectiveData
```

Oggetto immutabile che rappresenta un effetto Ombra predefinito.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDirection()](#getDirection--) | Direzione dell'ombra. |
| [getDistance()](#getDistance--) | Distanza dell'ombra. |
| [getShadowColor()](#getShadowColor--) | Colore dell'ombra. |
| [getPreset()](#getPreset--) | Preset. |
### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Direzione dell'ombra. float di sola lettura.

**Restituisce:**
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Distanza dell'ombra. double di sola lettura.

**Restituisce:**
double
### getShadowColor() {#getShadowColor--}
```
public abstract Color getShadowColor()
```

Colore dell'ombra. java.awt.Color di sola lettura.

**Restituisce:**
java.awt.Color
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Preset. di sola lettura [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Restituisce:**
int