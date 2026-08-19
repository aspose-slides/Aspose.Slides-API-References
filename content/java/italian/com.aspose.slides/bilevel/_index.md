---
title: BiLevel
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un effetto Bi-Level (nero/bianco).
type: docs
url: /it/com.aspose.slides/bilevel/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tutte le interfacce implementate:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Rappresenta un effetto Bi-Level (nero/bianco). I colori di input la cui luminanza è inferiore al valore soglia specificato vengono convertiti in nero. I colori di input la cui luminanza è maggiore o uguale al valore specificato vengono impostati a bianco. I valori alpha dell'effetto non sono influenzati da questo effetto.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEffective()](#getEffective--) | Ottiene i dati dell'effetto Bi-Level effettivo con l'eredità applicata. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [BiLevel](../../com.aspose.slides/bilevel) specificato è uguale all'attuale [BiLevel](../../com.aspose.slides/bilevel). |
| [hashCode()](#hashCode--) | Funge da funzione hash per un tipo specifico. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Ottiene i dati dell'effetto Bi-Level effettivo con l'eredità applicata.

**Restituisce:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - Un [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se il [BiLevel](../../com.aspose.slides/bilevel) specificato è uguale all'attuale [BiLevel](../../com.aspose.slides/bilevel).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il [BiLevel](../../com.aspose.slides/bilevel) da confrontare. |

**Restituisce:**
boolean - true se gli oggetti sono uguali; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Funge da funzione hash per un tipo specifico.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.