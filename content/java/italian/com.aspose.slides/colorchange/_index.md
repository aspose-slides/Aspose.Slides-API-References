---
title: ColorChange
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un effetto di Color Change.
type: docs
url: /it/com.aspose.slides/colorchange/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Rappresenta un effetto di Color Change. Le istanze di FromColor sono sostituite con istanze di ToColor.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFromColor()](#getFromColor--) | Colore che verrà sostituito. |
| [getToColor()](#getToColor--) | Colore che sostituirà. |
| [getEffective()](#getEffective--) | Ottiene i dati dell'effetto Color Change effettivo con l'ereditarietà applicata. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [ColorChange](../../com.aspose.slides/colorchange) specificato è uguale al corrente [ColorChange](../../com.aspose.slides/colorchange). |
| [hashCode()](#hashCode--) | Funge da funzione hash per un tipo particolare. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```


Colore che verrà sostituito. Sola lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```


Colore che sostituirà. Sola lettura [IColorFormat](../../com.aspose.slides/icolorformat).

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


Versione. Sola lettura long.

**Restituisce:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se il [ColorChange](../../com.aspose.slides/colorchange) specificato è uguale al corrente [ColorChange](../../com.aspose.slides/colorchange).

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