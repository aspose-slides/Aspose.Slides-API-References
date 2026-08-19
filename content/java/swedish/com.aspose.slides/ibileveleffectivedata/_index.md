---
title: IBiLevelEffectiveData
second_title: Aspose.Slides för Java API-referens
description: Oföränderligt objekt som representerar en Bi-Level (svart/vitt) effekt.
type: docs
url: /sv/com.aspose.slides/ibileveleffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Oföränderligt objekt som representerar en Bi-Level (svart/vitt) effekt. Ingångsfärger vars luminans är mindre än det specificerade tröskelvärdet ändras till svart. Ingångsfärger vars luminans är större än eller lika med det specificerade värdet sätts till vitt. Alfa-effektvärdena påverkas inte av denna effekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getThreshold()](#getThreshold--) | Returnerar tröskelvärdet. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Returnerar tröskelvärdet. Skrivskyddad float.

**Returnerar:**
float