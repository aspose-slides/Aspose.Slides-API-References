---
title: SmartArtNode
second_title: Aspose.Slides Androidra a Java API hivatkozás
description: A SmartArt objektum csomópontját képviseli
type: docs
url: /hu/com.aspose.slides/smartartnode/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

A SmartArt objektum csomópontját képviseli
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Visszaadja az aktuális csomópont összes gyermekcsomópontjának gyűjteményét. |
| [getShapes()](#getShapes--) | Visszaadja az aktuális csomóponthoz kapcsolódó összes alakzat gyűjteményét. |
| [getTextFrame()](#getTextFrame--) | Visszaadja a csomópont szövegkeretét. |
| [isAssistant()](#isAssistant--) | Visszaadja vagy beállítja a csomópontot segédként. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Visszaadja vagy beállítja a csomópontot segédként. |
| [getLevel()](#getLevel--) | Visszaadja a csomópont beágyazási szintjét. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Visszaadja a FillFormat objektumot, amely a csomópont jelölőjének kitöltési formázási tulajdonságait tartalmazza. |
| [getPosition()](#getPosition--) | Visszaadja vagy beállítja a csomópont nullánál kezdődő pozícióját a testvércsomópontok között. |
| [setPosition(int value)](#setPosition-int-) | Visszaadja vagy beállítja a csomópont nullánál kezdődő pozícióját a testvércsomópontok között. |
| [isHidden()](#isHidden--) | Visszaadja, ha ez a csomópont rejtett a adatmodellben. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Visszaadja vagy beállítja a jelenlegi csomóponthoz kapcsolódó szervezeti diagram elrendezés típusát. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Visszaadja vagy beállítja a jelenlegi csomóponthoz kapcsolódó szervezeti diagram elrendezés típusát. |
| [remove()](#remove--) | Eltávolítja az aktuális csomópontot. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Visszaadja az aktuális csomópont összes gyermekcsomópontjának gyűjteményét. Csak olvasható [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Visszatér:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Visszaadja az aktuális csomóponthoz kapcsolódó összes alakzat gyűjteményét. Csak olvasható [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Visszatér:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Visszaadja a csomópont szövegkeretét. Csak olvasható [ITextFrame](../../com.aspose.slides/itextframe).

**Visszatér:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Visszaadja vagy beállítja a csomópontot segédként. Olvasás/írás boolean.

**Visszatér:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Visszaadja vagy beállítja a csomópontot segédként. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

Visszaadja a csomópont beágyazási szintjét. Csak olvasható int.

**Visszatér:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Visszaadja a FillFormat objektumot, amely a csomópont jelölőjének kitöltési formázási tulajdonságait tartalmazza. Megjegyzés: bizonyos SmartArt elrendezések esetén, amelyek nem biztosítanak jelölőket a csomópontokhoz, null értéket adhat vissza. Csak olvasható [IFillFormat](../../com.aspose.slides/ifillformat).

**Visszatér:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Visszaadja vagy beállítja a csomópont nullánál kezdődő pozícióját a testvércsomópontok között. Olvasás/írás int.

**Visszatér:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Visszaadja vagy beállítja a csomópont nullánál kezdődő pozícióját a testvércsomópontok között. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Visszaadja, ha ez a csomópont rejtett a adatmodellben. Csak olvasható boolean.

**Visszatér:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Visszaadja vagy beállítja a jelenlegi csomóponthoz kapcsolódó szervezeti diagram elrendezés típusát. Olvasás/írás [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Visszatér:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Visszaadja vagy beállítja a jelenlegi csomóponthoz kapcsolódó szervezeti diagram elrendezés típusát. Olvasás/írás [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

Eltávolítja az aktuális csomópontot.

**Visszatér:**
boolean - true ha sikeresen eltávolítva, egyébként false