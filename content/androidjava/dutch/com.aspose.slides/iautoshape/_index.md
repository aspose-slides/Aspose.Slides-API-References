---
title: IAutoShape
second_title: Aspose.Slides voor Android via Java API-referentie
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
| [getAutoShapeLock()](#getAutoShapeLock--) | Retourneert de vergrendelingen van AutoShape. |
| [getTextFrame()](#getTextFrame--) | Retourneert TextFrame-object voor de AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Bepaalt of deze autoshape moet worden gevuld met de achtergrondvulling van de dia in plaats van gespecificeerd door stijl of vulformaat. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Bepaalt of deze autoshape moet worden gevuld met de achtergrondvulling van de dia in plaats van gespecificeerd door stijl of vulformaat. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Voegt een nieuw TextFrame toe aan een vorm. |
| [isTextBox()](#isTextBox--) | Geeft aan of de vorm een tekstvak is. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Retourneert de vergrendelingen van AutoShape. Alleen-lezen [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Retour:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Retourneert TextFrame-object voor de AutoShape. Alleen-lezen [ITextFrame](../../com.aspose.slides/itextframe).

**Retour:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Bepaalt of deze autoshape moet worden gevuld met de achtergrondvulling van de dia in plaats van gespecificeerd door stijl of vulformaat. Lees-/schrijfbare boolean.

**Retour:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Bepaalt of deze autoshape moet worden gevuld met de achtergrondvulling van de dia in plaats van gespecificeerd door stijl of vulformaat. Lees-/schrijfbare boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Voegt een nieuw TextFrame toe aan een vorm. Als de vorm al een TextFrame heeft, wordt de tekst eenvoudigweg aangepast.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| text | java.lang.String | Standaardtekst voor een nieuw TextFrame. |

**Retour:**
[ITextFrame](../../com.aspose.slides/itextframe) - Nieuw [ITextFrame](../../com.aspose.slides/itextframe) object.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Geeft aan of de vorm een tekstvak is.

--------------------

Als een vorm niet is opgegeven als tekstvak, betekent dat niet dat er geen tekst aan kan worden gekoppeld. Een tekstvak is slechts een gespecialiseerde vorm met specifieke eigenschappen.

**Retour:**
boolean