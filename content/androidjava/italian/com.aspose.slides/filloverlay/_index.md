---
title: FillOverlay
second_title: Riferimento API Java di Aspose.Slides per Android
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

Rappresenta un effetto di riempimento overlay. Un overlay di riempimento può essere utilizzato per specificare un riempimento aggiuntivo per un oggetto e fondere i due riempimenti insieme.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Formato di riempimento. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Ottiene i dati effettivi dell'effetto Fill Overlay con l'ereditarietà applicata. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [FillOverlay](../../com.aspose.slides/filloverlay) specificato è uguale al [FillOverlay](../../com.aspose.slides/filloverlay) corrente. |
| [hashCode()](#hashCode--) | Funge da funzione hash per un tipo particolare. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Formato di riempimento. Solo lettura [IFillFormat](../../com.aspose.slides/ifillformat).

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

Ottiene i dati effettivi dell'effetto Fill Overlay con l'ereditarietà applicata.

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

Determina se il [FillOverlay](../../com.aspose.slides/filloverlay) specificato è uguale al [FillOverlay](../../com.aspose.slides/filloverlay) corrente.

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

Funge da funzione hash per un tipo particolare.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.