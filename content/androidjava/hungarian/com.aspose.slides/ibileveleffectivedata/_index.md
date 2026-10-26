---
title: IBiLevelEffectiveData
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Megváltoztathatatlan objektum, amely egy Bi-Level (fekete/fehér) hatást képvisel.
type: docs
url: /hu/com.aspose.slides/ibileveleffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Megváltoztathatatlan objektum, amely egy Bi-Level (fekete/fehér) effektet képvisel. Azok a bemeneti színek, amelyek luminanciája kisebb a megadott küszöbértéknél, feketére változnak. Azok a bemeneti színek, amelyek luminanciája nagyobb vagy egyenlő a megadott értéknél, fehérre állítódnak. Az alfa effektus értékek erre az effektusra nincsenek hatással.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getThreshold()](#getThreshold--) | Visszaadja a küszöbértéket. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Visszaadja a küszöbértéket. Csak olvasható float.

**Visszatér:** 
float