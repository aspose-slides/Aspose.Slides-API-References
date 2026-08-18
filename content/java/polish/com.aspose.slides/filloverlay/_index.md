---
title: FillOverlay
second_title: Aspose.Slides for Java - Dokumentacja API
description: Reprezentuje efekt Fill Overlay.
type: docs
url: /pl/com.aspose.slides/filloverlay/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie Implementowane Interfejsy:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Reprezentuje efekt Fill Overlay. Fill overlay może być użyty do określenia dodatkowego wypełnienia dla obiektu i połączenia dwóch wypełnień razem.
## Metody

| Metoda | Opis |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Format wypełnienia. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane efektu Fill Overlay z zastosowanym dziedziczeniem. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy podany [FillOverlay](../../com.aspose.slides/filloverlay) jest równy bieżącemu [FillOverlay](../../com.aspose.slides/filloverlay). |
| [hashCode()](#hashCode--) | Służy jako funkcja skrótu dla określonego typu. |
### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Format wypełnienia. Tylko do odczytu [IFillFormat](../../com.aspose.slides/ifillformat).

**Zwraca:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. Odczyt/zapis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Zwraca:**
int
### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. Odczyt/zapis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

Pobiera skuteczne dane efektu Fill Overlay z zastosowanym dziedziczeniem.

**Zwraca:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - A [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Określa, czy podany [FillOverlay](../../com.aspose.slides/filloverlay) jest równy bieżącemu [FillOverlay](../../com.aspose.slides/filloverlay).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt [FillOverlay](../../com.aspose.slides/filloverlay) do porównania. |

**Zwraca:**
boolean - true jeśli obiekty są równe; w przeciwnym razie false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Służy jako funkcja skrótu dla określonego typu.

**Zwraca:**
int - A hash code for the current object.