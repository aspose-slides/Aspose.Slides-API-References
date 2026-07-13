---
title: SoftEdge
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta un effetto di bordo morbido.
type: docs
url: /it/com.aspose.slides/softedge/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Rappresenta un effetto di bordo morbido. I bordi della forma sono sfocati, mentre il riempimento non è influenzato.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRadius()](#getRadius--) | Specifica il raggio della sfocatura da applicare ai bordi. |
| [setRadius(double value)](#setRadius-double-) | Specifica il raggio della sfocatura da applicare ai bordi. |
| [getEffective()](#getEffective--) | Ottiene i dati dell'effetto Soft Edge effettivi con l'ereditarietà applicata. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [SoftEdge](../../com.aspose.slides/softedge) specificato è uguale all'attuale [SoftEdge](../../com.aspose.slides/softedge). |
| [hashCode()](#hashCode--) | Funziona come funzione hash per un tipo specifico. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Specifică il raggio della sfocatura da applicare ai bordi. Lettura/scrittura double.

**Restituisce:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Specifică il raggio della sfocatura da applicare ai bordi. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```


Ottiene i dati dell'effetto Soft Edge effettivi con l'ereditarietà applicata.

**Restituisce:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - Un [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Restituisce l'oggetto Parent_Immediate. Sola lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Versione. Sola lettura long.

**Restituisce:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Restituisce il padre IPresentationComponent. Sola lettura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Restituisce:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se il [SoftEdge](../../com.aspose.slides/softedge) specificato è uguale all'attuale [SoftEdge](../../com.aspose.slides/softedge).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il [SoftEdge](../../com.aspose.slides/softedge) da confrontare. |

**Restituisce:**
boolean - true se gli oggetti sono uguali; altrimenti, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funziona come funzione hash per un tipo specifico.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.