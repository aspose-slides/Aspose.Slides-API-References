---
title: Glow
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta un effetto Glow in cui un contorno sfocato di colore è aggiunto al di fuori dei bordi dell'oggetto.
type: docs
url: /it/com.aspose.slides/glow/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Rappresenta un effetto Glow, in cui è aggiunto un contorno sfocato di colore intorno ai bordi dell'oggetto.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRadius()](#getRadius--) | Raggio. |
| [setRadius(double value)](#setRadius-double-) | Raggio. |
| [getColor()](#getColor--) | Formato colore. |
| [getEffective()](#getEffective--) | Ottiene i dati dell'effetto Glow effettivo con l'ereditarietà applicata. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se il [Glow](../../com.aspose.slides/glow) specificato è uguale al corrente [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Funziona come una funzione hash per un tipo particolare. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Raggio. Lettura/scrittura  double .

**Restituisce:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Raggio. Lettura/scrittura  double .

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Formato colore. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


Ottiene i dati dell'effetto Glow effettivo con l'ereditarietà applicata.

**Restituisce:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Versione. Solo lettura long.

**Restituisce:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Restituisce il parent IPresentationComponent. Solo lettura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Restituisce:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se il [Glow](../../com.aspose.slides/glow) specificato è uguale al corrente [Glow](../../com.aspose.slides/glow).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Il [Glow](../../com.aspose.slides/glow) da confrontare. |

**Restituisce:**
boolean - vero se gli oggetti sono uguali; altrimenti, falso.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Funziona come una funzione hash per un tipo particolare.

**Restituisce:**
int - Un codice hash per l'oggetto corrente.