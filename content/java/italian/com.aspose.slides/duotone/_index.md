---
title: Duotone
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta un effetto Duotone.
type: docs
url: /it/com.aspose.slides/duotone/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tutte le interfacce implementate:**
[com.aspose.slides.IDuotone](../../com.aspose.slides/iduotone), com.aspose.slides.IVisualEffect
```
public final class Duotone extends ImageTransformOperation implements IDuotone, IVisualEffect
```

Rappresenta un effetto Duotone. Per ogni pixel, combina Color1 e Color2 tramite un'interpolazione lineare per determinare il nuovo colore per quel pixel.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColor1()](#getColor1--) | Restituisce il formato di colore di destinazione per i pixel scuri. |
| [getColor2()](#getColor2--) | Restituisce il formato di colore di destinazione per i pixel chiari. |
| [getEffective()](#getEffective--) | Ottiene i dati dell'effetto Duotone effettivo con l'ereditarietà applicata. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [Duotone](../../com.aspose.slides/duotone) specificato è uguale al [Duotone](../../com.aspose.slides/duotone) corrente. |
| [hashCode()](#hashCode--) | Funge da funzione hash per un tipo determinato. |
### getColor1() {#getColor1--}
```
public final IColorFormat getColor1()
```


Restituisce il formato di colore di destinazione per i pixel scuri. Sola lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getColor2() {#getColor2--}
```
public final IColorFormat getColor2()
```


Restituisce il formato di colore di destinazione per i pixel chiari. Sola lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IDuotoneEffectiveData getEffective()
```


Ottiene i dati dell'effetto Duotone effettivo con l'ereditarietà applicata.

**Restituisce:**
[IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata) - Un [IDuotoneEffectiveData](../../com.aspose.slides/iduotoneeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versione. Sola lettura long.

**Restituisce:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se il [Duotone](../../com.aspose.slides/duotone) specificato è uguale al [Duotone](../../com.aspose.slides/duotone) corrente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il [Duotone](../../com.aspose.slides/duotone) da confrontare. |

**Restituisce:**
boolean - true se gli oggetti sono uguali; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funge da funzione hash per un tipo determinato.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.