---
title: FillOverlay
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje efekt Fill Overlay.
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

Reprezentuje efekt Fill Overlay. Fill overlay může být použit k určení další výplně pro objekt a k jejich smíchání.

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

Formát výplně. Pouze ke čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Návratová hodnota:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. Čtení/Zápis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Návratová hodnota:**
int

### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. Čtení/Zápis [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

Získá efektivní data efektu Fill Overlay s aplikovanou dědičností.

**Návratová hodnota:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - A [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze ke čtení long.

**Návratová hodnota:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Určuje, zda je specifikovaný [FillOverlay](../../com.aspose.slides/filloverlay) roven aktuálnímu [FillOverlay](../../com.aspose.slides/filloverlay).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | [FillOverlay](../../com.aspose.slides/filloverlay) k porovnání. |

**Návratová hodnota:**
boolean - true pokud jsou objekty stejné; jinak false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Slouží jako hashovací funkce pro konkrétní typ.

**Návratová hodnota:**
int - A hash code for the current object.