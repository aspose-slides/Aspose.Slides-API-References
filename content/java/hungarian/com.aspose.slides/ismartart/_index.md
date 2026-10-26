---
title: ISmartArt
second_title: Aspose.Slides Java API referencia
description: SmartArt diagramot ábrázol.
type: docs
url: /hu/com.aspose.slides/ismartart/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

A SmartArt diagramot képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Visszaadja a SmartArt objektum összes csomópontjának gyűjteményét. |
| [getNodes()](#getNodes--) | Visszaadja a SmartArt objektum gyökércsomópontjainak gyűjteményét. |
| [getLayout()](#getLayout--) | Visszakapja vagy beállítja a SmartArt objektum elrendezését. |
| [setLayout(int value)](#setLayout-int-) | Visszakapja vagy beállítja a SmartArt objektum elrendezését. |
| [getQuickStyle()](#getQuickStyle--) | Visszakapja vagy beállítja a SmartArt objektum gyors stílusát. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Visszakapja vagy beállítja a SmartArt objektum gyors stílusát. |
| [getColorStyle()](#getColorStyle--) | Visszakapja vagy beállítja a SmartArt objektum színstílusát. |
| [setColorStyle(int value)](#setColorStyle-int-) | Visszakapja vagy beállítja a SmartArt objektum színstílusát. |
| [isReversed()](#isReversed--) | Visszakapja vagy beállítja a SmartArt diagram állapotát a (balról jobbra) LTR vagy a (jobbról balra) RTL tekintetében, ha a diagram támogatja a megfordítást. |
| [setReversed(boolean value)](#setReversed-boolean-) | Visszakapja vagy beállítja a SmartArt diagram állapotát a (balról jobbra) LTR vagy a (jobbról balra) RTL tekintetében, ha a diagram támogatja a megfordítást. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

Visszaadja a SmartArt objektum összes csomópontjának gyűjteményét. Csak olvasható [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Visszatér:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

Visszaadja a SmartArt objektum gyökércsomópontjainak gyűjteményét. Csak olvasható [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Visszatér:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Visszakapja vagy beállítja a SmartArt objektum elrendezését. Olvasás/írás [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Visszatér:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

Visszakapja vagy beállítja a SmartArt objektum elrendezését. Olvasás/írás [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

Visszakapja vagy beállítja a SmartArt objektum gyors stílusát. Olvasás/írás [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Visszatér:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickShape(int value)
```

Visszakapja vagy beállítja a SmartArt objektum gyors stílusát. Olvasás/írás [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

Visszakapja vagy beállítja a SmartArt objektum színstílusát. Olvasás/írás [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Visszatér:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

Visszakapja vagy beállítja a SmartArt objektum színstílusát. Olvasás/írás [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

Visszakapja vagy beállítja a SmartArt diagram állapotát a (balról jobbra) LTR vagy a (jobbról balra) RTL tekintetében, ha a diagram támogatja a megfordítást. Olvasás/írás boolean.

**Visszatér:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

Visszakapja vagy beállítja a SmartArt diagram állapotát a (balról jobbra) LTR vagy a (jobbról balra) RTL tekintetében, ha a diagram támogatja a megfordítást. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |