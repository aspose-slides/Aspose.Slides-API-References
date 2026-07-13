---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar en nod i ett SmartArt-diagram.
type: docs
url: /sv/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Representerar en nod i ett SmartArt-diagram.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Returnerar samlingar av alla underordnade noder till den aktuella noden. |
| [getShapes()](#getShapes--) | Returnerar samlingar av alla former som är associerade med noden. |
| [getTextFrame()](#getTextFrame--) | Returnerar eller anger texten för noden. |
| [isAssistant()](#isAssistant--) | Returnerar eller anger noden som assistent. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Returnerar eller anger noden som assistent. |
| [getLevel()](#getLevel--) | Returnerar nästningsnivå för noden. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en nodpunkt. |
| [getPosition()](#getPosition--) | Returnerar eller anger nollbaserad position för noden bland syskonnoder. |
| [setPosition(int value)](#setPosition-int-) | Returnerar eller anger nollbaserad position för noden bland syskonnoder. |
| [isHidden()](#isHidden--) | Returnerar sant om denna nod är en dold nod i datamodellen. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Returnerar eller anger organisationsdiagrammets layouttyp som är associerad med den aktuella noden. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Returnerar eller anger organisationsdiagrammets layouttyp som är associerad med den aktuella noden. |
| [remove()](#remove--) | Ta bort aktuell nod. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```


Returnerar samlingar av alla underordnade noder till den aktuella noden. Endast läsning [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returnerar:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```


Returnerar samlingar av alla former som är associerade med noden. Endast läsning [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Returnerar:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Returnerar eller anger texten för noden. Endast läsning [ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```


Returnerar eller anger noden som assistent. Läs/skriv boolean.

**Returnerar:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```


Returnerar eller anger noden som assistent. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```


Returnerar nästningsnivå för noden. Endast läsning int.

**Returnerar:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```


Returnerar FillFormat-objektet som innehåller fyllningsformateringsegenskaper för en nodpunkt. Obs: kan returnera null för vissa typer av SmartArt-layout som inte tillhandahåller punkter för noder. Endast läsning [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Returnerar eller anger nollbaserad position för noden bland syskonnoder. Läs/skriv int.

**Returnerar:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Returnerar eller anger nollbaserad position för noden bland syskonnoder. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Returnerar sant om denna nod är en dold nod i datamodellen. Endast läsning boolean.

**Returnerar:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```


Returnerar eller anger organisationsdiagrammets layouttyp som är associerad med den aktuella noden. Läs/skriv [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Returnerar:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```


Returnerar eller anger organisationsdiagrammets layouttyp som är associerad med den aktuella noden. Läs/skriv [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```


Ta bort aktuell nod.

**Returnerar:**
boolean - sant om borttagning lyckades, annars falskt.