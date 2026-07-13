---
title: IBlurEffectiveData
second_title: Aspose.Slides för Android via Java API-referens
description: Oföränderligt objekt som representerar en Blur-effekt som tillämpas på hela formen inklusive dess fyllning.
type: docs
url: /sv/com.aspose.slides/iblureffectivedata/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Oföränderligt objekt som representerar en Blur-effekt som tillämpas på hela formen, inklusive dess fyllning. Alla färgkanaler, inklusive alfa, påverkas.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRadius()](#getRadius--) | Returnerar eller anger blur radius. |
| [getGrow()](#getGrow--) | Avgör om objektets gränser ska växa som ett resultat av suddning. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Returnerar eller anger blur radius. Skrivskyddad double.

**Returns:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Avgör om objektets gränser ska växa som ett resultat av suddning. True indikerar att gränserna växer medan false indikerar att de inte gör det. Skrivskyddad boolean.

**Returns:**
boolean