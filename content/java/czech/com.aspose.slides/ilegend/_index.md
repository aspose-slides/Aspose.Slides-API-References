---
title: ILegend
second_title: Aspose.Slides pro Java - API reference
description: Reprezentuje vlastnosti legendy grafu.
type: docs
url: /cs/com.aspose.slides/ilegend/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Representuje vlastnosti legendy grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getOverlay()](#getOverlay--) | Určuje, zda budou ostatní prvky grafu povoleny překrývat legendu. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Určuje, zda budou ostatní prvky grafu povoleny překrývat legendu. |
| [getPosition()](#getPosition--) | Určuje polohu legendy v grafu. |
| [setPosition(int value)](#setPosition-int-) | Určuje polohu legendy v grafu. |
| [getFormat()](#getFormat--) | Vrací formát legendy. |
| [getEntries()](#getEntries--) | Získává položky legendy. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Určuje, zda budou ostatní prvky grafu povoleny překrývat legendu. Čtení/Zápis boolean.

**Vrací:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Určuje, zda budou ostatní prvky grafu povoleny překrývat legendu. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Určuje polohu legendy v grafu. Hodnoty, které nejsou NaN, vlastností X, Y, Width, Heigt přepíší účinek této vlastnosti. Čtení/Zápis [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Vrací:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Určuje polohu legendy v grafu. Hodnoty, které nejsou NaN, vlastností X, Y, Width, Heigt přepíší účinek této vlastnosti. Čtení/Zápis [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Vrací formát legendy. Pouze pro čtení [IFormat](../../com.aspose.slides/iformat).

**Vrací:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Získává položky legendy. Pouze pro čtení [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Vrací:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)