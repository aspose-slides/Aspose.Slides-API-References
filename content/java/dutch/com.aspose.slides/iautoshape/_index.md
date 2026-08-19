---
title: IAutoShape
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een AutoShape voor.
type: docs
url: /nl/com.aspose.slides/iautoshape/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Stelt een AutoShape voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Retourneert AutoShape's locks. |
| [getTextFrame()](#getTextFrame--) | Retourneert TextFrame object voor de AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Bepaalt of deze autoshape moet worden gevuld met slide's background fill in plaats van gespecificeerd door style of fill format. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Bepaalt of deze autoshape moet worden gevuld met slide's background fill in plaats van gespecificeerd door style of fill format. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Voegt een nieuw TextFrame toe aan een vorm. |
| [isTextBox()](#isTextBox--) | Specificeert of de vorm een tekstvak is. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Retourneert AutoShape's locks. Alleen-lezen [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Retourneert:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Retourneert TextFrame object voor de AutoShape. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retourneert:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Bepaalt of deze autoshape moet worden gevuld met slide's background fill in plaats van gespecificeerd door style of fill format. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Bepaalt of deze autoshape moet worden gevuld met slide's background fill in plaats van gespecificeerd door style of fill format. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Voegt een nieuw TextFrame toe aan een vorm. Als de vorm al TextFrame heeft, dan wijzigt het eenvoudigweg de tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Standaardtekst voor een nieuw TextFrame. |

**Retourneert:**
[ITextFrame](../../com.aspose.slides/itextframe) - Nieuw [ITextFrame](../../com.aspose.slides/itextframe) object.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Specificeert of de vorm een tekstvak is.

--------------------

Als een vorm niet is gespecificeerd als een tekstvak betekent dit niet dat er geen tekst aan kan worden gekoppeld. Een tekstvak is slechts een gespecialiseerde vorm met specifieke eigenschappen.

**Retourneert:**
boolean