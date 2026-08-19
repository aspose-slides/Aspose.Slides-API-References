---
title: FillOverlay
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta un effetto Fill Overlay.
type: docs
url: /it/com.aspose.slides/filloverlay/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Tutte le interfacce implementate:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Rappresenta un effetto Fill Overlay. Un Fill Overlay può essere usato per specificare un riempimento aggiuntivo per un oggetto e fondere i due riempimenti insieme.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Formato Fill. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Ottiene i dati dell'effetto Fill Overlay efficace con l'ereditarietà applicata. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [FillOverlay](../../com.aspose.slides/filloverlay) specificato è uguale al corrente [FillOverlay](../../com.aspose.slides/filloverlay). |
| [hashCode()](#hashCode--) | Funziona come funzione hash per un tipo specifico. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```


Formato Fill. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

**Restituisce:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```


FillBlendMode. Lettura/scrittura [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Restituisce:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```


FillBlendMode. Lettura/scrittura [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```


Ottiene i dati dell'effetto Fill Overlay efficace con l'ereditarietà applicata.

**Restituisce:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - Un [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
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


Determina se il [FillOverlay](../../com.aspose.slides/filloverlay) specificato è uguale al corrente [FillOverlay](../../com.aspose.slides/filloverlay).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il [FillOverlay](../../com.aspose.slides/filloverlay) da confrontare. |

**Restituisce:**
boolean - true se gli oggetti sono uguali; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funziona come funzione hash per un tipo specifico.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.