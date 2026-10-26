---
title: Glow
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje efekt Glow, w którym rozmyta obwódka w kolorze jest dodawana poza krawędziami obiektu.
type: docs
url: /pl/com.aspose.slides/glow/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Reprezentuje efekt Glow, w którym rozmyta obwódka w kolorze jest dodawana poza krawędziami obiektu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getRadius()](#getRadius--) | Promień. |
| [setRadius(double value)](#setRadius-double-) | Promień. |
| [getColor()](#getColor--) | Format koloru. |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane efektu Glow z uwzględnieniem dziedziczenia. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy podany [Glow](../../com.aspose.slides/glow) jest równy bieżącemu [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```

Promień. Odczyt/zapis  double .

**Zwraca:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```

Promień. Odczyt/zapis  double .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Format koloru. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```

Pobiera skuteczne dane efektu Glow z uwzględnieniem dziedziczenia.

**Zwraca:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - A [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
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

Zwraca rodzica IPPresentationComponent. Tylko do odczytu [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Zwraca:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Określa, czy podany [Glow](../../com.aspose.slides/glow) jest równy bieżącemu [Glow](../../com.aspose.slides/glow).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | [Glow](../../com.aspose.slides/glow) do porównania. |

**Zwraca:**
boolean - true jeśli obiekty są równe; w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - Skrót dla bieżącego obiektu.