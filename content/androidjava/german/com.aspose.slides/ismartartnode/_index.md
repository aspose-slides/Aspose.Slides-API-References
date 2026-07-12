---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt einen Knoten eines SmartArt-Diagramms dar.
type: docs
url: /de/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Stellt einen Knoten eines SmartArt-Diagramms dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Gibt Sammlungen aller Kindknoten des aktuellen Knotens zurück. |
| [getShapes()](#getShapes--) | Gibt Sammlungen aller dem Knoten zugeordneten Formen zurück. |
| [getTextFrame()](#getTextFrame--) | Gibt den Text des Knotens zurück oder setzt ihn. |
| [isAssistant()](#isAssistant--) | Gibt den Knoten als Assistent zurück oder setzt ihn. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Gibt den Knoten als Assistent zurück oder setzt ihn. |
| [getLevel()](#getLevel--) | Gibt die Verschachtelungsebene des Knotens zurück. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für einen Knoten-Bullet enthält. |
| [getPosition()](#getPosition--) | Gibt die nullbasierte Position des Knotens unter den Geschwisterknoten zurück oder setzt sie. |
| [setPosition(int value)](#setPosition-int-) | Gibt die nullbasierte Position des Knotens unter den Geschwisterknoten zurück oder setzt sie. |
| [isHidden()](#isHidden--) | Gibt true zurück, wenn dieser Knoten im Datenmodell ein versteckter Knoten ist. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Gibt den Layouttyp des Organigramms zurück oder setzt ihn. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Gibt den Layouttyp des Organigramms zurück oder setzt ihn. |
| [remove()](#remove--) | Entfernt den aktuellen Knoten. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Gibt Sammlungen aller Kindknoten des aktuellen Knotens zurück. Nur lesend [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Rückgabe:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Gibt Sammlungen aller dem Knoten zugeordneten Formen zurück. Nur lesend [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Rückgabe:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Gibt den Text des Knotens zurück oder setzt ihn. Nur lesend [ITextFrame](../../com.aspose.slides/itextframe).

**Rückgabe:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Gibt den Knoten als Assistent zurück oder setzt ihn. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Gibt den Knoten als Assistent zurück oder setzt ihn. Lesen/Schreiben boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Gibt die Verschachtelungsebene des Knotens zurück. Nur lesend int.

**Rückgabe:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Gibt das FillFormat-Objekt zurück, das Füllformatierungseigenschaften für einen Knoten-Bullet enthält. Hinweis: Kann für bestimmte SmartArt-Layout-Typen, die keine Bullets für Knoten bereitstellen, null zurückgeben. Nur lesend [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Gibt die nullbasierte Position des Knotens unter den Geschwisterknoten zurück oder setzt sie. Lesen/Schreiben int.

**Rückgabe:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Gibt die nullbasierte Position des Knotens unter den Geschwisterknoten zurück oder setzt sie. Lesen/Schreiben int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Gibt true zurück, wenn dieser Knoten im Datenmodell ein versteckter Knoten ist. Nur lesend boolean.

**Rückgabe:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Gibt den Layouttyp des Organigramms zurück oder setzt ihn. Lesen/Schreiben [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Rückgabe:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Gibt den Layouttyp des Organigramms zurück oder setzt ihn. Lesen/Schreiben [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

Entfernt den aktuellen Knoten.

**Rückgabe:**
boolean – true, wenn erfolgreich entfernt, sonst false.