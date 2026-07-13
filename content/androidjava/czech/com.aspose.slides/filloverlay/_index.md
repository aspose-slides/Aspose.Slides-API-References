---
title: FillOverlay
second_title: Aspose.Slides pro Android prostřednictvím referenční dokumentace Java API
description: Představuje efekt Fill Overlay.
type: docs
url: /cs/com.aspose.slides/filloverlay/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Všechny implementované rozhraní:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Představuje efekt Fill Overlay. Fill overlay může být použit k určení další výplně pro objekt a ke sloučení obou výplní.

## Metody

| Metoda | Popis |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Fill format. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Gets effective Fill Overlay effect data with the inheritance applied. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [FillOverlay](../../com.aspose.slides/filloverlay) is equal to the current [FillOverlay](../../com.aspose.slides/filloverlay). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Fill format. Jen ke čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Návratová hodnota:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. Čtení/zápis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Návratová hodnota:**
int

### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. Čtení/zápis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

Získá efektivní data efektu Fill Overlay s aplikovaným děděním.

**Návratová hodnota:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - A [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Jen ke čtení long.

**Návratová hodnota:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Určuje, zda je zadaný [FillOverlay](../../com.aspose.slides/filloverlay) roven aktuálnímu [FillOverlay](../../com.aspose.slides/filloverlay).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt [FillOverlay](../../com.aspose.slides/filloverlay) pro porovnání. |

**Návratová hodnota:**
boolean - true pokud jsou objekty stejné; jinak false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro konkrétní typ.

**Návratová hodnota:**
int - hash kód pro aktuální objekt.