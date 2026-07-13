---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt een knooppunt van een SmartArt-diagram voor.
type: docs
url: /nl/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Stelt een knooppunt van een SmartArt-diagram voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Retourneert collecties van alle onderliggende knooppunten van het huidige knooppunt. |
| [getShapes()](#getShapes--) | Retourneert collecties van alle vormen die aan het knooppunt zijn gekoppeld. |
| [getTextFrame()](#getTextFrame--) | Retourneert of stelt tekst van het knooppunt in. |
| [isAssistant()](#isAssistant--) | Retourneert of stelt het knooppunt in als assistent. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Retourneert of stelt het knooppunt in als assistent. |
| [getLevel()](#getLevel--) | Retourneert het geneste niveau van het knooppunt. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Retourneert het FillFormat-object dat opvul-opmaak-eigenschappen voor een knooppunt-opsommingsteken bevat. |
| [getPosition()](#getPosition--) | Retourneert of stelt de nul-gebaseerde positie van het knooppunt onder broers en zussen in. |
| [setPosition(int value)](#setPosition-int-) | Retourneert of stelt de nul-gebaseerde positie van het knooppunt onder broers en zussen in. |
| [isHidden()](#isHidden--) | Retourneert true als dit knooppunt een verborgen knooppunt is in het datamodel. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Retourneert of stelt het type organigram-indeling geassocieerd met het huidige knooppunt in. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Retourneert of stelt het type organigram-indeling geassocieerd met het huidige knooppunt in. |
| [remove()](#remove--) | Verwijder het huidige knooppunt. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Retourneert collecties van alle onderliggende knooppunten van het huidige knooppunt. Alleen-lezen [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retour:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Retourneert collecties van alle vormen die aan het knooppunt zijn gekoppeld. Alleen-lezen [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Retour:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Retourneert of stelt tekst van het knooppunt in. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retour:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Retourneert of stelt het knooppunt in als assistent. Lezen/Schrijven boolean.

**Retour:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Retourneert of stelt het knooppunt in als assistent. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Retourneert het geneste niveau van het knooppunt. Alleen-lezen int.

**Retour:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Retourneert het FillFormat-object dat opvul-opmaak-eigenschappen voor een knooppunt-opsommingsteken bevat. Opmerking: kan null retourneren voor bepaalde typen SmartArt-indeling die geen opsommingstekens voor knooppunten biedt. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Retourneert of stelt de nul-gebaseerde positie van het knooppunt onder broers en zussen in. Lezen/Schrijven int.

**Retour:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Retourneert of stelt de nul-gebaseerde positie van het knooppunt onder broers en zussen in. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Retourneert true als dit knooppunt een verborgen knooppunt is in het datamodel. Alleen-lezen boolean.

**Retour:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Retourneert of stelt het type organigram-indeling geassocieerd met het huidige knooppunt in. Lezen/Schrijven [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Retour:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Retourneert of stelt het type organigram-indeling geassocieerd met het huidige knooppunt in. Lezen/Schrijven [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

Verwijder het huidige knooppunt.

**Retour:**
boolean - true if removed succesfully, otherwise false.