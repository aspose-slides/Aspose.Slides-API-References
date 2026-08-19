---
title: IBiLevelEffectiveData
second_title: Riferimento API di Aspose.Slides per Java
description: Oggetto immutabile che rappresenta un effetto a due livelli (nero/bianco).
type: docs
url: /it/com.aspose.slides/ibileveleffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Oggetto immutabile che rappresenta un effetto a due livelli (nero/bianco). I colori di input la cui luminanza è inferiore al valore soglia specificato vengono cambiati in nero. I colori di input la cui luminanza è maggiore o uguale al valore specificato vengono impostati a bianco. I valori dell'effetto alfa non sono influenzati da questo effetto.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getThreshold()](#getThreshold--) | Restituisce il valore soglia. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Restituisce il valore soglia. Float di sola lettura.

**Restituisce:**
float