---
title: ColorReplace
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un effetto di Sostituzione colore.
type: docs
url: /it/com.aspose.slides/colorreplace/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tutte le interfacce implementate:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Rappresenta un effetto di Sostituzione colore. Tutti i colori dell'effetto sono cambiati in un colore fisso. I valori alpha non sono influenzati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColor()](#getColor--) | Restituisce il formato colore che sostituirà il colore di ogni pixel. |
| [getEffective()](#getEffective--) | Ottiene i dati effettivi dell'effetto di Sostituzione colore con l'ereditarietà applicata. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [ColorReplace](../../com.aspose.slides/colorreplace) specificato è uguale al [ColorReplace](../../com.aspose.slides/colorreplace) corrente. |
| [hashCode()](#hashCode--) | Funziona come funzione hash per un tipo particolare. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Restituisce il formato colore che sostituirà il colore di ogni pixel. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Ottiene i dati effettivi dell'effetto di Sostituzione colore con l'ereditarietà applicata.

**Restituisce:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - Un [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Solo lettura long.

**Restituisce:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se il [ColorReplace](../../com.aspose.slides/colorreplace) specificato è uguale al [ColorReplace](../../com.aspose.slides/colorreplace) corrente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il [ColorReplace](../../com.aspose.slides/colorreplace) da confrontare. |

**Restituisce:**
boolean - true se gli oggetti sono uguali; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Funziona come funzione hash per un tipo particolare.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.