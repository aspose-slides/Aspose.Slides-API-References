---
title: PresetShadow
second_title: Aspose.Slides dla Androida przy użyciu interfejsu API Java
description: Reprezentuje efekt cienia wstępnie ustawionego.
type: docs
url: /pl/com.aspose.slides/presetshadow/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPresetShadow](../../com.aspose.slides/ipresetshadow), com.aspose.slides.IVisualEffect, com.aspose.slides.IDOMObject, com.aspose.slides.IPVIObject, java.lang.Cloneable
```
public final class PresetShadow implements IPresetShadow, IVisualEffect, IDOMObject, IPVIObject, Cloneable
```

Reprezentuje efekt cienia wstępnie ustawionego.
## Metody

| Metoda | Opis |
| --- | --- |
| [getDirection()](#getDirection--) | Kierunek cienia. |
| [setDirection(float value)](#setDirection-float-) | Kierunek cienia. |
| [getDistance()](#getDistance--) | Odległość cienia. |
| [setDistance(double value)](#setDistance-double-) | Odległość cienia. |
| [getShadowColor()](#getShadowColor--) | Kolor cienia. |
| [getPreset()](#getPreset--) | Ustawienie. |
| [setPreset(int value)](#setPreset-int-) | Ustawienie. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane efektu cienia wstępnie ustawionego z zastosowanym dziedziczeniem. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getVersion()](#getVersion--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy określony [PresetShadow](../../com.aspose.slides/presetshadow) jest równy bieżącemu [PresetShadow](../../com.aspose.slides/presetshadow). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu. |
### getDirection() {#getDirection--}
```
public final float getDirection()
```

Kierunek cienia. Odczyt/zapis  float .

**Zwraca:**
float
### setDirection(float value) {#setDirection-float-}
```
public final void setDirection(float value)
```

Kierunek cienia. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |
### getDistance() {#getDistance--}
```
public final double getDistance()
```

Odległość cienia. Odczyt/zapis  double .

**Zwraca:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```

Odległość cienia. Odczyt/zapis  double .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getShadowColor() {#getShadowColor--}
```
public final IColorFormat getShadowColor()
```

Kolor cienia. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getPreset() {#getPreset--}
```
public final int getPreset()
```

Ustawienie. Odczyt/zapis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Zwraca:**
int
### setPreset(int value) {#setPreset-int-}
```
public final void setPreset(int value)
```

Ustawienie. Odczyt/zapis [PresetShadowType](../../com.aspose.slides/presetshadowtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IPresetShadowEffectiveData getEffective()
```

Pobiera efektywne dane efektu cienia wstępnie ustawionego z zastosowanym dziedziczeniem.

**Zwraca:**
[IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata) - [IPresetShadowEffectiveData](../../com.aspose.slides/ipresetshadoweffectivedata).
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent\_Immediate. Tylko do odczytu IDOMObject.

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

Zwraca nadrzędny IPresentationComponent. Tylko do odczytu [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Zwraca:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Określa, czy określony [PresetShadow](../../com.aspose.slides/presetshadow) jest równy bieżącemu [PresetShadow](../../com.aspose.slides/presetshadow).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | [PresetShadow](../../com.aspose.slides/presetshadow) do porównania. |

**Zwraca:**
boolean - true jeśli obiekty są równe; w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - Skrót dla bieżącego obiektu.