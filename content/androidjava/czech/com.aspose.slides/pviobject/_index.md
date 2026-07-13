---
title: PVIObject
second_title: Aspose.Slides pro Android - reference Java API
description: Zahaluje základní infrastrukturní služby pro objekty, které mohou být předmětem dědičnosti hodnot vlastností.
type: docs
url: /cs/com.aspose.slides/pviobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.slides.IPVIObject, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public abstract class PVIObject implements IPVIObject, ISlideComponent
```

Zahaluje základní infrastrukturní služby pro objekty, které mohou být předmětem dědění hodnot vlastností.

## Metody

| Metoda | Popis |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Porovnává se se zadaným objektem. |
| [hashCode()](#hashCode--) | Vrací hash kód. |

### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze ke čtení long.

**Vrací:**
long

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public IPPresentationComponent getParent_IPresentationComponent()
```

Vrací nadřazený IPresentationComponent. Pouze ke čtení [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Vrací:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public ISlideComponent getParent_ISlideComponent()
```

**Vrací:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getSlide() {#getSlide--}
```
public BaseSlide getSlide()
```

Vrací základní snímek. Pouze ke čtení [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Vrací:**
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public Presentation getPresentation()
```

Vrací prezentaci. Pouze ke čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[Presentation](../../com.aspose.slides/presentation)

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Porovnává se se zadaným objektem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt k porovnání. |

**Vrací:**
boolean - True pokud jsou objekty stejné, jinak false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Vrací hash kód.

**Vrací:**
int - Hash kód.