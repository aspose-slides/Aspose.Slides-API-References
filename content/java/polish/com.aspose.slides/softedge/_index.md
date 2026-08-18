---
title: SoftEdge
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje efekt miękkich krawędzi.
type: docs
url: /pl/com.aspose.slides/softedge/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISoftEdge](../../com.aspose.slides/isoftedge), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class SoftEdge implements ISoftEdge, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Reprezentuje efekt miękkich krawędzi. Krawędzie kształtu są rozmyte, podczas gdy wypełnienie nie jest zmienione.
## Metody

| Metoda | Opis |
| --- | --- |
| [getRadius()](#getRadius--) | Określa promień rozmycia stosowany do krawędzi. |
| [setRadius(double value)](#setRadius-double-) | Określa promień rozmycia stosowany do krawędzi. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane efektu miękkich krawędzi z zastosowanym dziedziczeniem. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy podany [SoftEdge](../../com.aspose.slides/softedge) jest równy bieżącemu [SoftEdge](../../com.aspose.slides/softedge). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Określa promień rozmycia stosowany do krawędzi. Odczyt/zapis double.

**Zwraca:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Określa promień rozmycia stosowany do krawędzi. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getEffective() {#getEffective--}
```
public final ISoftEdgeEffectiveData getEffective()
```

Pobiera efektywne dane efektu miękkich krawędzi z zastosowanym dziedziczeniem.

**Zwraca:**
[ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata) - [ISoftEdgeEffectiveData](../../com.aspose.slides/isoftedgeeffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Zwraca obiekt nadrzędny IPresentationComponent. Tylko do odczytu [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Zwraca:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Określa, czy podany [SoftEdge](../../com.aspose.slides/softedge) jest równy bieżącemu [SoftEdge](../../com.aspose.slides/softedge).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | [SoftEdge](../../com.aspose.slides/softedge) do porównania. |

**Zwraca:**
boolean - true jeśli obiekty są równe; w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - Kod skrótu bieżącego obiektu.