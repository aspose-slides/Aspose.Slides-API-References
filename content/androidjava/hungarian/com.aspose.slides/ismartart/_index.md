---
title: ISmartArt
second_title: Aspose.Slides for Android Java API hivatkozása
description: SmartArt diagramot reprezentál.
type: docs
url: /hu/com.aspose.slides/ismartart/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

SmartArt diagramot reprezentál.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | Visszaadja az összes csomópont gyűjteményét a SmartArt objektumban. |
| [getNodes()](#getNodes--) | Visszaadja a gyökércsomópontok gyűjteményét a SmartArt objektumban. |
| [getLayout()](#getLayout--) | Visszaadja vagy beállítja a SmartArt objektum elrendezését. |
| [setLayout(int value)](#setLayout-int-) | Visszaadja vagy beállítja a SmartArt objektum elrendezését. |
| [getQuickStyle()](#getQuickStyle--) | Visszaadja vagy beállítja a SmartArt objektum gyors stílusát. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | Visszaadja vagy beállítja a SmartArt objektum gyors stílusát. |
| [getColorStyle()](#getColorStyle--) | Visszaadja vagy beállítja a SmartArt objektum színstílusát. |
| [setColorStyle(int value)](#setColorStyle-int-) | Visszaadja vagy beállítja a SmartArt objektum színstílusát. |
| [isReversed()](#isReversed--) | Visszaadja vagy beállítja a SmartArt diagram állapotát a (balról jobbra) LTR vagy (jobbról balra) RTL tekintetében, ha a diagram támogatja a megfordítást. |
| [setReversed(boolean value)](#setReversed-boolean-) | Visszaadja vagy beállítja a SmartArt diagram állapotát a (balról jobbra) LTR vagy (jobbról balra) RTL tekintetében, ha a diagram támogatja a megfordítást. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

Visszaadja az összes csomópont gyűjteményét a SmartArt objektumban. Csak olvasható [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Visszatér:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

Visszaadja a gyökércsomópontok gyűjteményét a SmartArt objektumban. Csak olvasható [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Visszatér:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

Visszaadja vagy beállítja a SmartArt objektum elrendezését. Olvasás/írás [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Visszatér:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

Visszaadja vagy beállítja a SmartArt objektum elrendezését. Olvasás/írás [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

Visszaadja vagy beállítja a SmartArt objektum gyors stílusát. Olvasás/írás [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Visszatér:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

Visszaadja vagy beállítja a SmartArt objektum gyors stílusát. Olvasás/írás [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

Visszaadja vagy beállítja a SmartArt objektum színstílusát. Olvasás/írás [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Visszatér:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

Visszaadja vagy beállítja a SmartArt objektum színstílusát. Olvasás/írás [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

Visszaadja vagy beállítja a SmartArt diagram állapotát a (balról jobbra) LTR vagy (jobbról balra) RTL tekintetében, ha a diagram támogatja a megfordítást. Olvasás/írás boolean.

**Visszatér:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

Visszaadja vagy beállítja a SmartArt diagram állapotát a (balról jobbra) LTR vagy (jobbról balra) RTL tekintetében, ha a diagram támogatja a megfordítást. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |