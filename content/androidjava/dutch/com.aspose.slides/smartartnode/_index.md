---
title: SmartArtNode
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een knooppunt van een SmartArt-object voor
type: docs
url: /nl/com.aspose.slides/smartartnode/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Stelt een knooppunt van een SmartArt-object voor
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Retourneert collecties van alle onderliggende knooppunten van het huidige knooppunt. |
| [getShapes()](#getShapes--) | Retourneert collecties van alle vormen die aan het knooppunt zijn gekoppeld. |
| [getTextFrame()](#getTextFrame--) | Retourneert tekstframe van het knooppunt. |
| [isAssistant()](#isAssistant--) | Retourneert of stelt het knooppunt in als assistent. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Retourneert of stelt het knooppunt in als assistent. |
| [getLevel()](#getLevel--) | Retourneert het insluitingsniveau van het knooppunt. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Retourneert het FillFormat-object dat opvulopmaak-eigenschappen bevat voor een knooppuntkogel. |
| [getPosition()](#getPosition--) | Retourneert of stelt de nul-gebaseerde positie van het knooppunt tussen broederknooppunten in. |
| [setPosition(int value)](#setPosition-int-) | Retourneert of stelt de nul-gebaseerde positie van het knooppunt tussen broederknooppunten in. |
| [isHidden()](#isHidden--) | Retourneert true als dit knooppunt een verborgen knooppunt is in het datamodel. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Retourneert of stelt het lay-outtype van het organigram in dat aan het huidige knooppunt is gekoppeld. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Retourneert of stelt het lay-outtype van het organigram in dat aan het huidige knooppunt is gekoppeld. |
| [remove()](#remove--) | Verwijder het huidige knooppunt. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

Retourneert collecties van alle onderliggende knooppunten van het huidige knooppunt. Alleen-lezen [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retourneert:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

Retourneert collecties van alle vormen die aan het knooppunt zijn gekoppeld. Alleen-lezen [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Retourneert:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

Retourneert tekstframe van het knooppunt. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retourneert:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

Retourneert of stelt het knooppunt in als assistent. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

Retourneert of stelt het knooppunt in als assistent. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public final int getLevel()
```

Retourneert het insluitingsniveau van het knooppunt. Alleen-lezen int.

**Retourneert:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

Retourneert het FillFormat-object dat opvulopmaak-eigenschappen bevat voor een knooppuntkogel. Opmerking: kan null retourneren voor bepaalde typen SmartArt-lay-out die geen kogels voor knooppunten bieden. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retourneert:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Retourneert of stelt de nul-gebaseerde positie van het knooppunt tussen broederknooppunten in. Lezen/schrijven int.

**Retourneert:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Retourneert of stelt de nul-gebaseerde positie van het knooppunt tussen broederknooppunten in. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

Retourneert true als dit knooppunt een verborgen knooppunt is in het datamodel. Alleen-lezen boolean.

**Retourneert:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

Retourneert of stelt het lay-outtype van het organigram in dat aan het huidige knooppunt is gekoppeld. Lezen/schrijven [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Retourneert:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

Retourneert of stelt het lay-outtype van het organigram in dat aan het huidige knooppunt is gekoppeld. Lezen/schrijven [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public final boolean remove()
```

Verwijder het huidige knooppunt.

**Retourneert:**
boolean - true als succesvol verwijderd, anders false