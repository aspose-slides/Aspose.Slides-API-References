---
title: BiLevel
second_title: Aspose.Slides per Android via Riferimento API Java
description: Rappresenta un effetto Bi-Level in bianco/nero.
type: docs
url: /it/com.aspose.slides/bilevel/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tutte le interfacce implementate:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Rappresenta un effetto Bi-Level (nero/bianco). I colori di input la cui luminanza è inferiore al valore di soglia specificato vengono cambiati in nero. I colori di input la cui luminanza è maggiore o uguale al valore specificato vengono impostati a bianco. I valori di effetto alfa non sono influenzati da questo effetto.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEffective()](#getEffective--) | Recupera i dati dell'effetto Bi-Level effettivo con l'ereditarietà applicata. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [BiLevel](../../com.aspose.slides/bilevel) specificato è uguale al [BiLevel](../../com.aspose.slides/bilevel) corrente. |
| [hashCode()](#hashCode--) | Funge da funzione hash per un tipo particolare. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```

Recupera i dati dell'effetto Bi-Level effettivo con l'ereditarietà applicata.

**Restituisce:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - Un [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se il [BiLevel](../../com.aspose.slides/bilevel) specificato è uguale al [BiLevel](../../com.aspose.slides/bilevel) corrente.

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

Funge da funzione hash per un tipo particolare.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.