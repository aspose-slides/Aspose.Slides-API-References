---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: A SmartArt diagram egy csomópontját képviseli.
type: docs
url: /hu/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

A SmartArt diagram egy csomópontját képviseli.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Visszaadja az aktuális csomópont összes gyermekcsomópontjának gyűjteményét. |
| [getShapes()](#getShapes--) | Visszaadja az adott csomóponthoz tartozó összes alakzat gyűjteményét. |
| [getTextFrame()](#getTextFrame--) | Visszaadja vagy beállítja a csomópont szövegét. |
| [isAssistant()](#isAssistant--) | Visszaadja vagy beállítja a csomópontot segédként. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Visszaadja vagy beállítja a csomópontot segédként. |
| [getLevel()](#getLevel--) | Visszaadja a csomópont beágyazási szintjét. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Visszaadja a FillFormat objektumot, amely a csomópont jelölőjének kitöltési formázási tulajdonságait tartalmazza. |
| [getPosition()](#getPosition--) | Visszaadja vagy beállítja a csomópont nullától kezdődő pozícióját a testvércsomópontok között. |
| [setPosition(int value)](#setPosition-int-) | Visszaadja vagy beállítja a csomópont nullától kezdődő pozícióját a testvércsomópontok között. |
| [isHidden()](#isHidden--) | Igazat ad vissza, ha ez a csomópont rejtett a adatmodellben. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Visszaadja vagy beállítja a jelenlegi csomóponthoz tartozó szervezeti diagram elrendezés típusát. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Visszaadja vagy beállítja a jelenlegi csomóponthoz tartozó szervezeti diagram elrendezés típusát. |
| [remove()](#remove--) | Eltávolítja a jelenlegi csomópontot. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Visszaadja az aktuális csomópont összes gyermekcsomópontjának gyűjteményét. Csak olvasható [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Visszatér:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Visszaadja az adott csomóponthoz tartozó összes alakzat gyűjteményét. Csak olvasható [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Visszatér:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Visszaadja vagy beállítja a csomópont szövegét. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Visszaadja vagy beállítja a csomópontot segédként. Olvasás/írás boolean.

**Visszatér:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Visszaadja vagy beállítja a csomópontot segédként. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Visszaadja a csomópont beágyazási szintjét. Csak olvasható int.

**Visszatér:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Visszaadja a FillFormat objektumot, amely a csomópont jelölőjének kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos SmartArt elrendezések esetén null értéket adhat vissza, amelyek nem biztosítanak jelölőket a csomópontokhoz. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Visszaadja vagy beállítja a csomópont nullától kezdődő pozícióját a testvércsomópontok között. Olvasás/írás int.

**Visszatér:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Visszaadja vagy beállítja a csomópont nullától kezdődő pozícióját a testvércsomópontok között. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Igazat ad vissza, ha ez a csomópont rejtett a adatmodellben. Csak olvasható boolean.

**Visszatér:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Visszaadja vagy beállítja a jelenlegi csomóponthoz tartozó szervezeti diagram elrendezés típusát. Olvasás/írás [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Visszatér:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Visszaadja vagy beállítja a jelenlegi csomóponthoz tartozó szervezeti diagram elrendezés típusát. Olvasás/írás [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

Eltávolítja a jelenlegi csomópontot.

**Visszatér:**
boolean - igaz, ha sikeresen eltávolították, egyébként hamis.