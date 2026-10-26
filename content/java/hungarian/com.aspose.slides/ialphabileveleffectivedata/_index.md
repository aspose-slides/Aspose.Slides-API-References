---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides for Java API-referencia
description: Megváltoztathatatlan objektum, amely egy Alpha Bi-Level hatást képvisel.
type: docs
url: /hu/com.aspose.slides/ialphabileveleffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Megváltoztathatatlan objektum, amely egy Alpha Bi-Level hatást képvisel. Az Alpha (Opacity) értékek, amelyek kisebbek a küszöbnél, 0-ra (teljesen átlátszó) változnak, a küszönnél nagyobb vagy egyenlő Alpha értékek 100%-ra (teljesen átlátszatlan) változnak.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getThreshold()](#getThreshold--) | Visszaadja a effekt küszöbértékét. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Visszaadja a effekt küszöbértékét. Csak olvasható float.

**Visszatér:**
float