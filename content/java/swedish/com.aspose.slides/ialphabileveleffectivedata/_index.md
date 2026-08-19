---
title: IAlphaBiLevelEffectiveData
second_title: Aspose.Slides för Java API-referens
description: Immutabelt objekt som representerar en Alpha Bi-Level-effekt.
type: docs
url: /sv/com.aspose.slides/ialphabileveleffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Immutabelt objekt som representerar en Alpha Bi-Level-effekt. Alpha (Opacity)-värden som är mindre än tröskeln ändras till 0 (helt genomskinlig) och alpha-värden som är lika med eller större än tröskeln ändras till 100% (helt ogenomskinlig).
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