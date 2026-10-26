---
title: SmartArtNode
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Knoten eines SmartArt-Objekts dar
type: docs
url: /de/com.aspose.slides/smartartnode/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Stellt einen Knoten eines SmartArt-Objekts dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Gibt Sammlungen aller Kindknoten des aktuellen Knotens zurück. |
| [getShapes()](#getShapes--) | Gibt Sammlungen aller dem Knoten zugeordneten Formen zurück. |
| [getTextFrame()](#getTextFrame--) | Gibt den Textrahmen des Knotens zurück. |
| [isAssistant()](#isAssistant--) | Gibt zurück oder setzt den Knoten als Assistent. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Gibt zurück oder setzt den Knoten als Assistent. |
| [getLevel()](#getLevel--) | Gibt die Verschachtelungsebene des Knotens zurück. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Gibt das FillFormat-Objekt zurück, das Füllformat-Eigenschaften für einen Knoten-Bullet enthält. |
| [getPosition()](#getPosition--) | Gibt die nullbasierte Position des Knotens unter den Geschwisterknoten zurück oder setzt sie. |
| [setPosition(int value)](#setPosition-int-) | Gibt die nullbasierte Position des Knotens unter den Geschwisterknoten zurück oder setzt sie. |
| [isHidden()](#isHidden--) | Gibt true zurück, wenn dieser Knoten ein verborgener Knoten im Datenmodell ist. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Gibt den Layouttyp des Organigramms zurück oder setzt ihn für den aktuellen Knoten. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Gibt den Layouttyp des Organigramms zurück oder setzt ihn für den aktuellen Knoten. |
| [remove()](#remove--) | Entfernt den aktuellen Knoten. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Gibt Sammlungen aller Kindknoten des aktuellen Knotens zurück. Nur lesbar [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Rückgabe:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Gibt Sammlungen aller dem Knoten zugeordneten Formen zurück. Nur lesbar [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Rückgabe:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Gibt den Textrahmen des Knotens zurück. Nur lesbar [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Gibt zurück oder setzt den Knoten als Assistent. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Gibt zurück oder setzt den Knoten als Assistent. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

Gibt die Verschachtelungsebene des Knotens zurück. Nur lesbar int.

**Rückgabe:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Gibt das FillFormat-Objekt zurück, das Füllformat-Eigenschaften für einen Knoten-Bullet enthält. Hinweis: Kann für bestimmte SmartArt-Layouts, die keine Bullets für Knoten bereitstellen, null zurückgeben. Nur lesbar [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Gibt die nullbasierte Position des Knotens unter den Geschwisterknoten zurück oder setzt sie. Lesen/Schreiben int.

**Rückgabe:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Gibt die nullbasierte Position des Knotens unter den Geschwisterknoten zurück oder setzt sie. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Gibt true zurück, wenn dieser Knoten ein verborgener Knoten im Datenmodell ist. Nur lesbar boolean.

**Rückgabe:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Gibt den Layouttyp des Organigramms zurück oder setzt ihn für den aktuellen Knoten. Lesen/Schreiben [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Rückgabe:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Gibt den Layouttyp des Organigramms zurück oder setzt ihn für den aktuellen Knoten. Lesen/Schreiben [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

Entfernt den aktuellen Knoten.

**Rückgabe:**
boolean - true if removed succesfully, otherwise false