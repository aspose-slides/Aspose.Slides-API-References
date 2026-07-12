---
title: SmartArtNode
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Knoten eines SmartArt-Objekts dar
type: docs
url: /de/com.aspose.slides/smartartnode/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Stellt einen Knoten eines SmartArt-Objekts dar
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Gibt Sammlungen aller untergeordneten Knoten des aktuellen Knotens zurück. |
| [getShapes()](#getShapes--) | Gibt Sammlungen aller mit dem Knoten verknüpften Formen zurück. |
| [getTextFrame()](#getTextFrame--) | Gibt den Textrahmen des Knotens zurück. |
| [isAssistant()](#isAssistant--) | Gibt zurück oder legt fest, ob der Knoten ein Assistent ist. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Gibt zurück oder legt fest, ob der Knoten ein Assistent ist. |
| [getLevel()](#getLevel--) | Gibt die Verschachtelungsebene des Knotens zurück. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für einen Aufzählungszeichen-Knoten enthält. |
| [getPosition()](#getPosition--) | Gibt die nullbasierte Position des Knotens unter den Geschwisterknoten zurück oder legt sie fest. |
| [setPosition(int value)](#setPosition-int-) | Gibt die nullbasierte Position des Knotens unter den Geschwisterknoten zurück oder legt sie fest. |
| [isHidden()](#isHidden--) | Gibt true zurück, wenn dieser Knoten ein ausgeblendeter Knoten im Datenmodell ist. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Gibt den mit dem aktuellen Knoten verknüpften Organisationsdiagramm-Layouttyp zurück oder legt ihn fest. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Gibt den mit dem aktuellen Knoten verknüpften Organisationsdiagramm-Layouttyp zurück oder legt ihn fest. |
| [remove()](#remove--) | Entfernt den aktuellen Knoten. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Gibt Sammlungen aller untergeordneten Knoten des aktuellen Knotens zurück. Nur lesbar [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Rückgabe:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Gibt Sammlungen aller mit dem Knoten verknüpften Formen zurück. Nur lesbar [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

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

Gibt zurück oder legt fest, ob der Knoten ein Assistent ist. Lese-/Schreib-boolean.

**Rückgabe:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Gibt zurück oder legt fest, ob der Knoten ein Assistent ist. Lese-/Schreib-boolean.

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

Gibt das FillFormat-Objekt zurück, das Füllformatierungs-Eigenschaften für einen Aufzählungszeichen-Knoten enthält. Hinweis: Kann für bestimmte Typen von SmartArt-Layouts, die keine Aufzählungszeichen für Knoten bereitstellen, null zurückgeben. Nur lesbar [IFillFormat](../../com.aspose.slides/ifillformat).

**Rückgabe:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Gibt die nullbasierte Position des Knotens unter den Geschwisterknoten zurück oder legt sie fest. Lese-/Schreib-int.

**Rückgabe:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Gibt die nullbasierte Position des Knotens unter den Geschwisterknoten zurück oder legt sie fest. Lese-/Schreib-int.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Gibt true zurück, wenn dieser Knoten ein ausgeblendeter Knoten im Datenmodell ist. Nur lesbar boolean.

**Rückgabe:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Gibt den mit dem aktuellen Knoten verknüpften Organisationsdiagramm-Layouttyp zurück oder legt ihn fest. Lese-/Schreib [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Rückgabe:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Gibt den mit dem aktuellen Knoten verknüpften Organisationsdiagramm-Layouttyp zurück oder legt ihn fest. Lese-/Schreib [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

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
boolean - true, wenn erfolgreich entfernt, sonst false