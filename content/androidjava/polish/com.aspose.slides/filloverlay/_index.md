---
title: FillOverlay
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje efekt nakładki wypełnienia.
type: docs
url: /pl/com.aspose.slides/filloverlay/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Reprezentuje efekt nakładki wypełnienia. Nakładka wypełnienia może być użyta do określenia dodatkowego wypełnienia obiektu i połączenia obu wypełnień.

## Metody

| Metoda | Opis |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Format wypełnienia. |
| [getBlend()](#getBlend--) | Tryb mieszania wypełnienia. |
| [setBlend(int value)](#setBlend-int-) | Tryb mieszania wypełnienia. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane efektu Fill Overlay z zastosowanym dziedziczeniem. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Określa, czy określony [FillOverlay](../../com.aspose.slides/filloverlay) jest równy bieżącemu [FillOverlay](../../com.aspose.slides/filloverlay). |
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

Tryb mieszania wypełnienia. Odczyt/zapis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Zwraca:**
int

### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

Tryb mieszania wypełnienia. Odczyt/zapis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

Pobiera efektywne dane efektu Fill Overlay z zastosowanym dziedziczeniem.

**Zwraca:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata)

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

Określa, czy określony [FillOverlay](../../com.aspose.slides/filloverlay) jest równy bieżącemu [FillOverlay](../../com.aspose.slides/filloverlay).

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
int - Kod skrótu dla bieżącego obiektu.