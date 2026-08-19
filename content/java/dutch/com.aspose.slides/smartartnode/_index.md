---
title: SmartArtNode
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt knoop van een SmartArt-object
type: docs
url: /nl/com.aspose.slides/smartartnode/
---
**Overerving:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Stelt een knoop van een SmartArt-object voor
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Retourneert collecties van alle kindknopen van de huidige knoop. |
| [getShapes()](#getShapes--) | Retourneert collecties van alle vormen die aan de knoop zijn gekoppeld. |
| [getTextFrame()](#getTextFrame--) | Retourneert tekstframe van de knoop. |
| [isAssistant()](#isAssistant--) | Retourneert of stelt de knoop in als assistent. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Retourneert of stelt de knoop in als assistent. |
| [getLevel()](#getLevel--) | Retourneert nestingniveau van de knoop. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Retourneert het FillFormat-object dat opvulopmaakeigenschappen voor een knoopkogel bevat. |
| [getPosition()](#getPosition--) | Retourneert of stelt de nulgebaseerde positie van de knoop ten opzichte van broederknooppunten in. |
| [setPosition(int value)](#setPosition-int-) | Retourneert of stelt de nulgebaseerde positie van de knoop ten opzichte van broederknooppunten in. |
| [isHidden()](#isHidden--) | Retourneert true als deze knoop een verborgen knoop in het datamodel is. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Retourneert of stelt het diagramtype van een organigram in dat is gekoppeld aan de huidige knoop. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Retourneert of stelt het diagramtype van een organigram in dat is gekoppeld aan de huidige knoop. |
| [remove()](#remove--) | Verwijder huidige knoop. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Retourneert collecties van alle kindknopen van de huidige knoop. Alleen-lezen [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retour:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Retourneert collecties van alle vormen die aan de knoop zijn gekoppeld. Alleen-lezen [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Retour:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Retourneert tekstframe van de knoop. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retour:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Retourneert of stelt de knoop in als assistent. Lezen/schrijven boolean.

**Retour:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Retourneert of stelt de knoop in als assistent. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

Retourneert nestingniveau van de knoop. Alleen-lezen int.

**Retour:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Retourneert het FillFormat-object dat opvulopmaakeigenschappen voor een knoopkogel bevat. Opmerking: kan null retourneren voor bepaalde typen SmartArt-lay-out die geen kogels voor knopen bieden. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Retourneert of stelt de nulgebaseerde positie van de knoop ten opzichte van broederknooppunten in. Lezen/schrijven int.

**Retour:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Retourneert of stelt de nulgebaseerde positie van de knoop ten opzichte van broederknooppunten in. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Retourneert true als deze knoop een verborgen knoop in het datamodel is. Alleen-lezen boolean.

**Retour:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Retourneert of stelt het diagramtype van een organigram in dat is gekoppeld aan de huidige knoop. Lezen/schrijven [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Retour:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Retourneert of stelt het diagramtype van een organigram in dat is gekoppeld aan de huidige knoop. Lezen/schrijven [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

Verwijder huidige knoop.

**Retour:**
boolean - true if removed succesfully, otherwise false