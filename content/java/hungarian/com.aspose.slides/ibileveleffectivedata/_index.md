---
title: IBiLevelEffectiveData
second_title: Aspose.Slides Java API referencia
description: Immutábilis objektum, amely egy kétszintű (fekete/fehér) hatást ábrázol.
type: docs
url: /hu/com.aspose.slides/ibileveleffectivedata/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Az immutábilis objektum, amely egy kétszintű (fekete/fehér) hatást reprezentál. Azok a bemeneti színek, amelyek luminanciája kisebb a megadott küszöbértéknél, feketére változtatódnak. Azok a bemeneti színek, amelyek luminanciája nagyobb vagy egyenlő a megadott értéknél, fehérre állnak. Az alfa effektus értékeket ez a hatás nem érinti.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getThreshold()](#getThreshold--) | Visszaadja a küszöbértéket. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Visszaadja a küszöbértéket. Csak olvasható float.

**Visszatér:**
float