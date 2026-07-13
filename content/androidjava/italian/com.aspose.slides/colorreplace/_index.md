---
title: ColorReplace
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta un effetto Color Replacement.
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

Rappresenta un effetto Color Replacement. Tutti i colori dell'effetto vengono cambiati in un colore fisso. I valori Alpha non sono influenzati.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColor()](#getColor--) | Restituisce il formato di colore che sostituirà il colore di ogni pixel. |
| [getEffective()](#getEffective--) | Ottiene i dati dell'effetto Color Replacement effettivo con l'ereditarietà applicata. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il/la [ColorReplace](../../com.aspose.slides/colorreplace) specificato è uguale al/la [ColorReplace](../../com.aspose.slides/colorreplace) corrente. |
| [hashCode()](#hashCode--) | Funge da funzione hash per un tipo particolare. |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Restituisce il formato di colore che sostituirà il colore di ogni pixel. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Ottiene i dati dell'effetto Color Replacement effettivo con l'ereditarietà applicata.

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

Determina se il/la [ColorReplace](../../com.aspose.slides/colorreplace) specificato è uguale al/la [ColorReplace](../../com.aspose.slides/colorreplace) corrente.

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

Funge da funzione hash per un tipo particolare.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.