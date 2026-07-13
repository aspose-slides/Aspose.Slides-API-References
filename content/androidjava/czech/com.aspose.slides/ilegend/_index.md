---
title: ILegend
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje vlastnosti legendy grafu.
type: docs
url: /cs/com.aspose.slides/ilegend/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Reprezentuje vlastnosti legendy grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getOverlay()](#getOverlay--) | Určuje, zda mají být ostatní prvky grafu povoleny překrývat legendu. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Určuje, zda mají být ostatní prvky grafu povoleny překrývat legendu. |
| [getPosition()](#getPosition--) | Určuje umístění legendy v grafu. |
| [setPosition(int value)](#setPosition-int-) | Určuje umístění legendy v grafu. |
| [getFormat()](#getFormat--) | Vrací formát legendy. |
| [getEntries()](#getEntries--) | Získává položky legendy. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Určuje, zda mají být ostatní prvky grafu povoleny překrývat legendu. Čtení/Zápis boolean.

**Návratová hodnota:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Určuje, zda mají být ostatní prvky grafu povoleny překrývat legendu. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Určuje umístění legendy v grafu. Hodnoty X, Y, Width, Heigt, které nejsou NaN, přepíší účinek této vlastnosti. Čtení/Zápis [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Návratová hodnota:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Určuje umístění legendy v grafu. Hodnoty X, Y, Width, Heigt, které nejsou NaN, přepíší účinek této vlastnosti. Čtení/Zápis [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Vrací formát legendy. Pouze ke čtení [IFormat](../../com.aspose.slides/iformat).

**Návratová hodnota:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```


Získává položky legendy. Pouze ke čtení [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Návratová hodnota:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)