---
title: Glow
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Představuje efekt Glow, ve kterém je okolo hran objektu přidán rozmazaný obrys barvy.
type: docs
url: /cs/com.aspose.slides/glow/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IGlow](../../com.aspose.slides/iglow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class Glow implements IGlow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Představuje efekt Glow, ve kterém je okolo hran objektu přidán rozmazaný obrys barvy.
## Metody

| Metoda | Popis |
| --- | --- |
| [getRadius()](#getRadius--) | Poloměr. |
| [setRadius(double value)](#setRadius-double-) | Poloměr. |
| [getColor()](#getColor--) | Formát barvy. |
| [getEffective()](#getEffective--) | Získá efektivní data Glow efektu s aplikovaným děděním. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Určuje, zda je zadaný [Glow](../../com.aspose.slides/glow) roven aktuálnímu [Glow](../../com.aspose.slides/glow). |
| [hashCode()](#hashCode--) | Slouží jako hashovací funkce pro konkrétní typ. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Poloměr. Čtení/zápis double.

**Vrací:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Poloměr. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```


Formát barvy. Pouze pro čtení [IColorFormat](../../com.aspose.slides/icolorformat).

**Vrací:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IGlowEffectiveData getEffective()
```


Získá efektivní data Glow efektu s aplikovaným děděním.

**Vrací:**
[IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata) - [IGlowEffectiveData](../../com.aspose.slides/igloweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getVersion() {#getVersion--}
```
public final long getVersion()
```


Verze. Pouze pro čtení long.

**Vrací:**
long
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```


Vrací rodičovský IPresentationComponent. Pouze pro čtení [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Vrací:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Určuje, zda je zadaný [Glow](../../com.aspose.slides/glow) roven aktuálnímu [Glow](../../com.aspose.slides/glow).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Zadaný [Glow](../../com.aspose.slides/glow) k porovnání. |

**Vrací:**
boolean - true, pokud jsou objekty rovny; jinak false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Slouží jako hashovací funkce pro konkrétní typ.

**Vrací:**
int - Hash kód aktuálního objektu.