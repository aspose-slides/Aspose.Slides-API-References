---
title: IBiLevelEffectiveData
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Oggetto immutabile che rappresenta un effetto bi-livello nero/bianco.
type: docs
url: /it/com.aspose.slides/ibileveleffectivedata/
---
**Tutte le Interfacce Implementate:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBiLevelEffectiveData extends IEffectEffectiveData
```

Oggetto immutabile che rappresenta un effetto a due livelli (nero/bianco). I colori di input la cui luminanza è inferiore al valore di soglia specificato vengono trasformati in nero. I colori di input la cui luminanza è maggiore o uguale al valore specificato vengono impostati su bianco. I valori di effetto alpha non sono influenzati da questo effetto.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getThreshold()](#getThreshold--) | Restituisce il valore della soglia. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Restituisce il valore della soglia. Float di sola lettura.

**Restituisce:**
float