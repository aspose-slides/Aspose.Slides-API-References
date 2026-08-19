---
title: IBlurEffectiveData
second_title: Aspose.Slides för Java API-referens
description: Oföränderligt objekt som representerar en Blur-effekt som tillämpas på hela formen, inklusive dess fyllning.
type: docs
url: /sv/com.aspose.slides/iblureffectivedata/
---
**All Implemented Interfaces:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Oföränderligt objekt som representerar en Blur-effekt som tillämpas på hela formen, inklusive dess fyllning. Alla färgkanaler, inklusive alfa, påverkas.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getRadius()](#getRadius--) | Returnerar eller anger radius för oskärpa. |
| [getGrow()](#getGrow--) | Bestämmer om objektets gränser ska utökas som ett resultat av oskärpan. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Returnerar eller anger radius för oskärpa. Skrivskyddad double.

**Returnerar:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Bestämmer om objektets gränser ska utökas som ett resultat av oskärpan. True indikerar att gränserna utökas medan false indikerar att de inte gör det. Skrivskyddad boolean.

**Returnerar:**
boolean