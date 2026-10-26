---
title: AlphaFloor
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un effetto Alpha Floor.
type: docs
url: /it/com.aspose.slides/alphafloor/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tutte le interfacce implementate:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Rappresenta un effetto Alpha Floor. I valori Alpha (opacità) inferiori al 100% vengono impostati a zero. In altre parole, tutto ciò che è parzialmente trasparente diventa completamente trasparente.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEffective()](#getEffective--) | Ottiene i dati effettivi dell'effetto Alpha Floor con l'ereditarietà applicata. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [AlphaFloor](../../com.aspose.slides/alphafloor) specificato è uguale al [AlphaFloor](../../com.aspose.slides/alphafloor) corrente. |
| [hashCode()](#hashCode--) | Funziona come funzione hash per un tipo particolare. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Ottiene i dati effettivi dell'effetto Alpha Floor con l'ereditarietà applicata.

**Restituisce:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - Un [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se il [AlphaFloor](../../com.aspose.slides/alphafloor) specificato è uguale al [AlphaFloor](../../com.aspose.slides/alphafloor) corrente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il [AlphaFloor](../../com.aspose.slides/alphafloor) da confrontare. |

**Restituisce:**
boolean - true se gli oggetti sono uguali; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funziona come funzione hash per un tipo particolare.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.