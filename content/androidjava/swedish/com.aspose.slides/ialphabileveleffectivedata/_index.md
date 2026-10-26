---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides för Android via Java API-referens
description: Oföränderligt objekt som representerar en Alpha Bi-Level-effekt.
type: docs
url: /sv/com.aspose.slides/ialphabileveleffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Oföränderligt objekt som representerar en Alpha Bi-Level-effekt. Alpha (Opacity)-värden mindre än tröskelvärdet ändras till 0 (fullt transparent) och alpha-värden större än eller lika med tröskelvärdet ändras till 100 % (fullt ogenomskinlig).
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getThreshold()](#getThreshold--) | Returnerar effektens tröskelvärde. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Returnerar effektens tröskelvärde. Skrivskyddad float.

**Returnerar:**
float