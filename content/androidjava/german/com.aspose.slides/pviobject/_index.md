---
title: PVIObject
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Kapselt die grundlegende Service-Infrastruktur für Objekte, die Gegenstand einer Vererbung von Eigenschaftswerten sein können.
type: docs
url: /de/com.aspose.slides/pviobject/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Kapselt die grundlegende Service-Infrastruktur für Objekte, die Gegenstand einer Vererbung von Eigenschaftswerten sein können.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Vergleicht mit dem angegebenen Objekt. |
| [hashCode()](#hashCode--) | Gibt den Hashcode zurück. |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur-Lese IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur-Lese long.

**Rückgabewert:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPresentationComponent getParent_IPresentationComponent()
```

Gibt das übergeordnete IPresentationComponent zurück. Nur-Lese [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Rückgabewert:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**Rückgabewert:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

Gibt die Basisfolie zurück. Nur-Lese [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Rückgabewert:**
[BaseSlide](../../com.aspose.slides/baseslide)
### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

Gibt die Präsentation zurück. Nur-Lese [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabewert:**
[Presentation](../../com.aspose.slides/presentation)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Vergleicht mit dem angegebenen Objekt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | java.lang.Object | Zu vergleichendes Objekt. |

**Rückgabewert:**
boolean - true, wenn Objekte gleich sind, sonst false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Gibt den Hashcode zurück.

**Rückgabewert:**
int - Hashcode.