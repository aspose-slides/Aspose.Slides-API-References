---
title: IBlurEffectiveData
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Oggetto immutabile che rappresenta un effetto Blur applicato all'intera forma, incluso il riempimento.
type: docs
url: /it/com.aspose.slides/iblureffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Oggetto immutabile che rappresenta un effetto Blur applicato all'intera forma, incluso il riempimento. Tutti i canali colore, inclusa l'alpha, sono influenzati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRadius()](#getRadius--) | Restituisce o imposta il raggio della sfocatura. |
| [getGrow()](#getGrow--) | Determina se i limiti dell'oggetto devono essere ingranditi a causa della sfocatura. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

Restituisce o imposta il raggio della sfocatura. Solo lettura double.

**Restituisce:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

Determina se i limiti dell'oggetto devono essere ingranditi a causa della sfocatura. True indica che i limiti sono ingranditi mentre false indica che non lo sono. Solo lettura boolean.

**Restituisce:**
boolean