---
title: ISmartArtNode
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een knoop van een SmartArt-diagram voor.
type: docs
url: /nl/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Stelt een knoop van een SmartArt-diagram voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Geeft collecties van alle onderliggende knopen van de huidige knoop terug. |
| [getShapes()](#getShapes--) | Geeft collecties van alle vormen die aan de knoop zijn gekoppeld terug. |
| [getTextFrame()](#getTextFrame--) | Geeft de tekst van de knoop terug of stelt deze in. |
| [isAssistant()](#isAssistant--) | Geeft de knoop als assistent terug of stelt deze in. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Geeft de knoop als assistent terug of stelt deze in. |
| [getLevel()](#getLevel--) | Geeft het nestingsniveau van de knoop terug. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Geeft het FillFormat-object terug dat opvulopmaak-eigenschappen bevat voor een knoop-bullet. |
| [getPosition()](#getPosition--) | Geeft de nulgebaseerde positie van de knoop onder broers en zussen terug of stelt deze in. |
| [setPosition(int value)](#setPosition-int-) | Geeft de nulgebaseerde positie van de knoop onder broers en zussen terug of stelt deze in. |
| [isHidden()](#isHidden--) | Geeft true terug als deze knoop een verborgen knoop is in het datamodel. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Geeft het lay-outtype van het organigram terug of stelt dit in voor de huidige knoop. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Geeft het lay-outtype van het organigram terug of stelt dit in voor de huidige knoop. |
| [remove()](#remove--) | Verwijder de huidige knoop. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

Geeft collecties van alle onderliggende knopen van de huidige knoop terug. Alleen-lezen [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Retour:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

Geeft collecties van alle vormen die aan de knoop zijn gekoppeld terug. Alleen-lezen [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Retour:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

Geeft de tekst van de knoop terug of stelt deze in. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retour:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

Geeft de knoop als assistent terug of stelt deze in. Lezen/schrijven boolean.

**Retour:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

Geeft de knoop als assistent terug of stelt deze in. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

Geeft het nestingsniveau van de knoop terug. Alleen-lezen int.

**Retour:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

Geeft het FillFormat-object terug dat opvulopmaak-eigenschappen bevat voor een knoop-bullet. Opmerking: kan null retourneren voor bepaalde typen SmartArt-lay-out die geen bullets voor knopen bieden. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Geeft de nulgebaseerde positie van de knoop onder broers en zussen terug of stelt deze in. Lezen/schrijven int.

**Retour:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Geeft de nulgebaseerde positie van de knoop onder broers en zussen terug of stelt deze in. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

Geeft true terug als deze knoop een verborgen knoop is in het datamodel. Alleen-lezen boolean.

**Retour:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

Geeft het lay-outtype van het organigram terug of stelt dit in voor de huidige knoop. Lezen/schrijven [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Retour:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

Geeft het lay-outtype van het organigram terug of stelt dit in voor de huidige knoop. Lezen/schrijven [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

Verwijder de huidige knoop.

**Retour:**
boolean - true als succesvol verwijderd, anders false.