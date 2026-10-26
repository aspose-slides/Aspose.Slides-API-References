---
title: ISmartArtNode
second_title: Aspose.Slides for Java API Reference
description: Represents node of a SmartArt diagram.
type: docs
url: /hu/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

A SmartArt diagram csomópontját képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Visszaadja az aktuális csomópont összes gyermekcsomópontját tartalmazó gyűjteményeket. |
| [getShapes()](#getShapes--) | Visszaadja a csomóponthoz kapcsolódó összes alakzatot tartalmazó gyűjteményeket. |
| [getTextFrame()](#getTextFrame--) | Visszaadja vagy beállítja a csomópont szövegét. |
| [isAssistant()](#isAssistant--) | Visszaadja vagy beállítja a csomópontot asszisztensként. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Visszaadja vagy beállítja a csomópontot asszisztensként. |
| [getLevel()](#getLevel--) | Visszaadja a csomópont beágyazási szintjét. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Visszaadja a FillFormat objektumot, amely a csomópont jelölőjének kitöltési formázási tulajdonságait tartalmazza. |
| [getPosition()](#getPosition--) | Visszaadja vagy beállítja a csomópont nullától kezdődő pozícióját a testvércsoportok között. |
| [setPosition(int value)](#setPosition-int-) | Visszaadja vagy beállítja a csomópont nullától kezdődő pozícióját a testvércsoportok között. |
| [isHidden()](#isHidden--) | Igaz értéket ad vissza, ha ez a csomópont egy rejtett csomópontról van szó az adatmodellben. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Visszaadja vagy beállítja a jelenlegi csomóponthoz kapcsolódó szervezeti diagram elrendezés típusát. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Visszaadja vagy beállítja a jelenlegi csomóponthoz kapcsolódó szervezeti diagram elrendezés típusát. |
| [remove()](#remove--) | Eltávolítja az aktuális csomópontot. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Visszaadja az aktuális csomópont összes gyermekcsomópontját tartalmazó gyűjteményeket. Csak olvasható [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Visszatér:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Visszaadja a csomóponthoz kapcsolódó összes alakzatot tartalmazó gyűjteményeket. Csak olvasható [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

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

Visszaadja vagy beállítja a csomópontot asszisztensként. Olvasható/írható logikai.

**Visszatér:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Visszaadja vagy beállítja a csomópontot asszisztensként. Olvasható/írható logikai.

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

Visszaadja a FillFormat objektumot, amely a csomópont jelölőjének kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos SmartArt elrendezéstípusok esetén, amelyek nem biztosítanak jelölőket a csomópontokhoz, null értéket adhat vissza. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Visszaadja vagy beállítja a csomópont nullától kezdődő pozícióját a testvércsoportok között. Olvasható/írható int.

**Visszatér:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Visszaadja vagy beállítja a csomópont nullától kezdődő pozícióját a testvércsoportok között. Olvasható/írható int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Igaz értéket ad vissza, ha ez a csomópont egy rejtett csomópontról van szó az adatmodellben. Csak olvasható logikai.

**Visszatér:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Visszaadja vagy beállítja a jelenlegi csomóponthoz kapcsolódó szervezeti diagram elrendezés típusát. Olvasható/írható [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Visszatér:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Visszaadja vagy beállítja a jelenlegi csomóponthoz kapcsolódó szervezeti diagram elrendezés típusát. Olvasható/írható [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

Eltávolítja az aktuális csomópontot.

**Visszatér:**
boolean - igaz, ha a eltávolítás sikeres, egyébként hamis.