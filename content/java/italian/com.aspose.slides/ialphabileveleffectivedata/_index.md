---
title: IAlphaBiLevelEffectiveData
second_title: Riferimento API di Aspose.Slides per Java
description: Oggetto immutabile che rappresenta un effetto Alpha Bi-Level.
type: docs
url: /it/com.aspose.slides/ialphabileveleffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IAlphaBiLevelEffectiveData extends IEffectEffectiveData
```

Oggetto immutabile che rappresenta un effetto Alpha Bi-Level. I valori Alpha (Opacità) inferiori alla soglia vengono impostati a 0 (completamente trasparente) e i valori alpha maggiori o uguali alla soglia vengono impostati al 100% (completamente opaco).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getThreshold()](#getThreshold--) | Restituisce la soglia dell'effetto. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Restituisce la soglia dell'effetto. float di sola lettura.

**Restituisce:**
float