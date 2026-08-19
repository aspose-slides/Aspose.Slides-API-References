---
title: IBlurEffectiveData
second_title: Aspose.Slides per Java Riferimento API
description: Oggetto immutabile che rappresenta un effetto Blur applicato all'intera forma, compreso il riempimento.
type: docs
url: /it/com.aspose.slides/iblureffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Oggetto immutabile che rappresenta un effetto Blur applicato all'intera forma, compreso il riempimento. Tutti i canali di colore, compreso l'alpha, sono interessati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRadius()](#getRadius--) | Restituisce o imposta il raggio del blur. |
| [getGrow()](#getGrow--) | Determina se i limiti dell'oggetto devono essere ingranditi a causa del blur. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Restituisce o imposta il raggio del blur. Solo lettura double.

**Restituisce:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Determina se i limiti dell'oggetto devono essere ingranditi a causa del blur. True indica che i limiti sono ingranditi mentre false indica che non lo sono. Solo lettura boolean.

**Restituisce:**
boolean