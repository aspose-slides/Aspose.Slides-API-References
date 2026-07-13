---
title: PVIObject
second_title: Aspose.Slides per Android via Riferimento API Java
description: Incapsula l'infrastruttura di servizio di base per gli oggetti che possono essere soggetti a ereditarietà del valore della proprietà.
type: docs
url: /it/com.aspose.slides/pviobject/
---
**Ereditarietà:**
java.lang.Object

**Tutte le Interfacce Implementate:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Incapsula l'infrastruttura di servizio di base per gli oggetti che possono essere soggetti a ereditarietà del valore della proprietà.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Confronta con l'oggetto specificato. |
| [hashCode()](#hashCode--) | Restituisce il codice hash. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Restituisce l'oggetto Parent_Immediate. Solo lettura IDOMObject.

**Restituisce:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Solo lettura long.

**Restituisce:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

Restituisce il genitore IPresentationComponent. Solo lettura [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Restituisce:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**Restituisce:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

Restituisce la slide di base. Solo lettura [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Restituisce:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

Restituisce la presentazione. Solo lettura [IPresentation](../../com.aspose.slides/ipresentation).

**Restituisce:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Confronta con l'oggetto specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | Oggetto da confrontare. |

**Restituisce:**
boolean - Vero se gli oggetti sono uguali, altrimenti falso.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Restituisce il codice hash.

**Restituisce:**
int - Codice hash.