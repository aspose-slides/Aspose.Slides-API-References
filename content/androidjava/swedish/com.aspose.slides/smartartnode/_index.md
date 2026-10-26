---
title: SmartArtNode
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en nod i ett SmartArt-objekt
type: docs
url: /sv/com.aspose.slides/smartartnode/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Representerar en nod i ett SmartArt-objekt
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Returnerar samlingar av alla underordnade noder till den aktuella noden. |
| [getShapes()](#getShapes--) | Returnerar samlingar av alla former som är associerade med noden. |
| [getTextFrame()](#getTextFrame--) | Returnerar textramen för noden. |
| [isAssistant()](#isAssistant--) | Returnerar eller anger noden som assistent. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Returnerar eller anger noden som assistent. |
| [getLevel()](#getLevel--) | Returnerar nästningsnivå för noden. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Returnerar FillFormat-objektet som innehåller fyllningsformaterings-egenskaper för en nodpunkt. |
| [getPosition()](#getPosition--) | Returnerar eller anger nollbaserad position för noden bland syskon-noder. |
| [setPosition(int value)](#setPosition-int-) | Returnerar eller anger nollbaserad position för noden bland syskon-noder. |
| [isHidden()](#isHidden--) | Returnerar true om den här noden är en dold nod i datamodellen. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Returnerar eller anger layouttyp för organisationsdiagram som är associerad med den aktuella noden. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Returnerar eller anger layouttyp för organisationsdiagram som är associerad med den aktuella noden. |
| [remove()](#remove--) | Ta bort aktuell nod. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Returnerar samlingar av alla underordnade noder till den aktuella noden. Endast läsning [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returnerar:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Returnerar samlingar av alla former som är associerade med noden. Endast läsning [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Returnerar:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Returnerar textramen för noden. Endast läsning [ITextFrame](../../com.aspose.slides/itextframe).

**Returnerar:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Returnerar eller anger noden som assistent. Läs/skriv boolesk.

**Returnerar:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Returnerar eller anger noden som assistent. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

Returnerar nästningsnivå för noden. Endast läsning int.

**Returnerar:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Returnerar FillFormat-objektet som innehåller fyllningsformaterings-egenskaper för en nodpunkt. Obs: kan returnera null för vissa typer av SmartArt-layout som inte tillhandahåller punkter för noder. Endast läsning [IFillFormat](../../com.aspose.slides/ifillformat).

**Returnerar:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Returnerar eller anger nollbaserad position för noden bland syskon-noder. Läs/skriv int.

**Returnerar:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Returnerar eller anger nollbaserad position för noden bland syskon-noder. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Returnerar true om den här noden är en dold nod i datamodellen. Endast läsning boolesk.

**Returnerar:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Returnerar eller anger layouttyp för organisationsdiagram som är associerad med den aktuella noden. Läs/skriv [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Returnerar:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Returnerar eller anger layouttyp för organisationsdiagram som är associerad med den aktuella noden. Läs/skriv [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

Ta bort aktuell nod.

**Returnerar:**
boolean - true om borttagning lyckas, annars false