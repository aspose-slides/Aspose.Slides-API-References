---
title: ColorChange
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un effetto di Cambio Colore.
type: docs
url: /it/com.aspose.slides/colorchange/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tutte le interfacce implementate:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Rappresenta un effetto di Cambio Colore. Le istanze di FromColor vengono sostituite con le istanze di ToColor.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFromColor()](#getFromColor--) | Colore che verrà sostituito. |
| [getToColor()](#getToColor--) | Colore che sostituirà. |
| [getEffective()](#getEffective--) | Ottiene i dati dell'effetto Color Change effettivo con l'ereditarietà applicata. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [ColorChange](../../com.aspose.slides/colorchange) specificato è uguale al [ColorChange](../../com.aspose.slides/colorchange) corrente. |
| [hashCode()](#hashCode--) | Funge da funzione hash per un tipo particolare. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```


Colore che verrà sostituito. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```


Colore che sostituirà. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```


Ottiene i dati dell'effetto Color Change effettivo con l'ereditarietà applicata.

**Restituisce:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - Un [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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


Determina se il [ColorChange](../../com.aspose.slides/colorchange) specificato è uguale al [ColorChange](../../com.aspose.slides/colorchange) corrente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il [ColorChange](../../com.aspose.slides/colorchange) da confrontare. |

**Restituisce:**
boolean - true se gli oggetti sono uguali; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funge da funzione hash per un tipo particolare.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.