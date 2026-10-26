---
title: IPresetShadowEffectiveData
second_title: Aspose.Slides Java API hivatkozás
description: Módosíthatatlan objektum, amely egy Preset árnyékhatást képvisel.
type: docs
url: /hu/com.aspose.slides/ipresetshadoweffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IPresetShadowEffectiveData extends IEffectEffectiveData
```

Módosíthatatlan objektum, amely egy Preset árnyékhatást képvisel.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getDirection()](#getDirection--) | Az árnyék iránya. |
| [getDistance()](#getDistance--) | Az árnyék távolsága. |
| [getShadowColor()](#getShadowColor--) | Az árnyék színe. |
| [getPreset()](#getPreset--) | Preset. |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

Az árnyék iránya. Csak olvasható float.

**Visszatér:**  
float
### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

Az árnyék távolsága. Csak olvasható double.

**Visszatér:**  
double
### getShadowColor() {#getShadowColor--}
```
public abstract Color getShadowColor()
```

Az árnyék színe. Csak olvasható java.awt.Color.

**Visszatér:**  
java.awt.Color
### getPreset() {#getPreset--}
```
public abstract int getPreset()
```

Preset. Csak olvasható [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Visszatér:**  
int