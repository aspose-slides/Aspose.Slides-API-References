---
title: IBaseSlide
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt gemeenschappelijke gegevens voor alle dia-types.
type: docs
url: /nl/com.aspose.slides/ibaseslide/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Vertegenwoordigt gemeenschappelijke gegevens voor alle dia-types.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShapes()](#getShapes--) | Retourneert de vormen van een dia. |
| [getControls()](#getControls--) | Retourneert de collectie ActiveX-besturingselementen op een dia. |
| [getName()](#getName--) | Retourneert of stelt de naam van een dia in. |
| [setName(String value)](#setName-java.lang.String-) | Retourneert of stelt de naam van een dia in. |
| [getSlideId()](#getSlideId--) | Retourneert de ID van een dia. |
| [getCustomData()](#getCustomData--) | Retourneert de aangepaste gegevens van de dia. |
| [getTimeline()](#getTimeline--) | Retourneert het animatietijdlijnobject. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Retourneert het TransitionEx-object dat informatie bevat over hoe de opgegeven dia tijdens een diavoorstelling wordt voortgezet. |
| [getBackground()](#getBackground--) | Retourneert de achtergrond van de dia. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Biedt gemakkelijke toegang tot de ingesloten hyperlinks. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Bepaalt of vormen op de masterslides op dia's moeten worden weergegeven of niet. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Bepaalt of vormen op de masterslides op dia's moeten worden weergegeven of niet. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Zoekt de eerste instantie van een vorm met de opgegeven alternatieve tekst. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs met dezelfde opmaak samen in alle alinea's in alle geschikte vormen. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


Retourneert de vormen van een dia. Alleen-lezen [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Retour:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```


Retourneert de collectie ActiveX-besturingselementen op een dia. Alleen-lezen [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Retour:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```


Retourneert of stelt de naam van een dia in. Lezen/schrijven String.

**Retour:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Retourneert of stelt de naam van een dia in. Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```


Retourneert de ID van een dia. Alleen-lezen long.

**Retour:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


Retourneert de aangepaste gegevens van de dia. Alleen-lezen [ICustomData](../../com.aspose.slides/icustomdata).

**Retour:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```


Retourneert het animatietijdlijnobject. Alleen-lezen [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Retour:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```


Retourneert het TransitionEx-object dat informatie bevat over hoe de opgegeven dia tijdens een diavoorstelling wordt voortgezet. Alleen-lezen [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Retour:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```


Retourneert de achtergrond van de dia. Alleen-lezen [IBackground](../../com.aspose.slides/ibackground).

**Retour:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


Biedt gemakkelijke toegang tot de ingesloten hyperlinks. Alleen-lezen [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retour:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


Bepaalt of vormen op de masterslides op dia's moeten worden weergegeven of niet. Voor de masterslide zelf geeft deze eigenschap altijd **false** terug. Lezen/schrijven boolean.

**Retour:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


Bepaalt of vormen op de masterslides op dia's moeten worden weergegeven of niet. Voor de masterslide zelf geeft deze eigenschap altijd **false** terug. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```


Zoekt de eerste instantie van een vorm met de opgegeven alternatieve tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| altText | java.lang.String | Alternatieve tekst. |

**Retour:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx object of null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Voegt runs met dezelfde opmaak samen in alle alinea's in alle geschikte vormen.

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```


Bepaalt of de twee IBaseSlide-instanties gelijk zijn. De geretourneerde waarde wordt berekend op basis van de structuur en statische inhoud van de dia. Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, zoals SlideId, en dynamische inhoud, zoals de huidige datumwaarde in Date Placeholder.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | De IBaseSlide om te vergelijken met de huidige IBaseSlide. |

**Retour:**
boolean - **true** als de opgegeven IBaseSlide gelijk is aan de huidige IBaseSlide; anders, **false**.