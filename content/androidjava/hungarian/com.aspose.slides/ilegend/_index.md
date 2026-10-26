---
title: ILegend
second_title: Aspose.Slides Androidra Java API referencia
description: A diagramok jelmagyarázatának tulajdonságait képviseli.
type: docs
url: /hu/com.aspose.slides/ilegend/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

A diagram jelmagyarázatának tulajdonságait képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getOverlay()](#getOverlay--) | Meghatározza, hogy a többi diagram elem átfedheti-e a jelmagyarázatot. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Meghatározza, hogy a többi diagram elem átfedheti-e a jelmagyarázatot. |
| [getPosition()](#getPosition--) | Meghatározza a jelmagyarázat pozícióját a diagramon. |
| [setPosition(int value)](#setPosition-int-) | Meghatározza a jelmagyarázat pozícióját a diagramon. |
| [getFormat()](#getFormat--) | Visszaadja a jelmagyarázat formátumát. |
| [getEntries()](#getEntries--) | Lekéri a jelmagyarázat bejegyzéseit. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

Meghatározza, hogy a többi diagram elem átfedheti-e a jelmagyarázatot. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

Meghatározza, hogy a többi diagram elem átfedheti-e a jelmagyarázatot. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Meghatározza a jelmagyarázat pozícióját a diagramon. A X, Y, Width, Heigt tulajdonságok nem NaN értékei felülbírálják ennek a tulajdonságnak a hatását. Olvasás/írás [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Visszatérési érték:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Meghatározza a jelmagyarázat pozícióját a diagramon. A X, Y, Width, Heigt tulajdonságok nem NaN értékei felülbírálják ennek a tulajdonságnak a hatását. Olvasás/írás [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Visszaadja a jelmagyarázat formátumát. Csak olvasható [IFormat](../../com.aspose.slides/iformat).

**Visszatérési érték:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

Lekéri a jelmagyarázat bejegyzéseit. Csak olvasható [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Visszatérési érték:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)