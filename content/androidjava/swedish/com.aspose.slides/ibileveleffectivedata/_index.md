---
title: IBiLevelEffectiveData
second_title: Aspose.Slides för Android via Java API-referens
description: Oföränderligt objekt som representerar en tvånivå svart/vit-effekt.
type: docs
url: /sv/com.aspose.slides/ibileveleffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Oföränderligt objekt som representerar en tvånivåeffekt (black/white). Inmatningsfärger vars luminans är mindre än det angivna tröskelvärdet ändras till svart. Inmatningsfärger vars luminans är större än eller lika med det angivna värdet sätts till vitt. Alfa-effektvärdena påverkas inte av denna effekt.

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