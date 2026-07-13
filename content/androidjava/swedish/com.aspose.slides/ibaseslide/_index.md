---
title: IBaseSlide
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar gemensam data för alla bildtyper.
type: docs
url: /sv/com.aspose.slides/ibaseslide/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Representerar gemensam data för alla bildtyper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShapes()](#getShapes--) | Returnerar formerna på en bild. |
| [getControls()](#getControls--) | Returnerar samlingen av ActiveX-kontroller på en bild. |
| [getName()](#getName--) | Returnerar eller anger namnet på en bild. |
| [setName(String value)](#setName-java.lang.String-) | Returnerar eller anger namnet på en bild. |
| [getSlideId()](#getSlideId--) | Returnerar ID för en bild. |
| [getCustomData()](#getCustomData--) | Returnerar bildens anpassade data. |
| [getTimeline()](#getTimeline--) | Returnerar animations-tidslinje-objekt. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Returnerar TransitionEx-objektet som innehåller information om hur den angivna bilden avancerar under en bildspelspresentation. |
| [getBackground()](#getBackground--) | Returnerar bildens bakgrund. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Tillhandahåller enkel åtkomst till inbäddade hyperlänkar. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Anger om former på mastern bör visas på bilder eller inte. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Anger om former på mastern bör visas på bilder eller inte. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Hittar den första förekomsten av en form med angiven alternativ text. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Sammanfogar körningar med samma formatering i alla stycken i alla accepterade former. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Fastställer huruvida de två IBaseSlide-instanserna är lika. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


Returnerar formerna på en bild. Skrivskyddad [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Returnerar:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```


Returnerar samlingen av ActiveX-kontroller på en bild. Skrivskyddad [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Returnerar:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```


Returnerar eller anger namnet på en bild. Läs/skriv String.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Returnerar eller anger namnet på en bild. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```


Returnerar ID för en bild. Skrivskyddad long.

**Returnerar:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


Returnerar bildens anpassade data. Skrivskyddad [ICustomData](../../com.aspose.slides/icustomdata).

**Returnerar:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```


Returnerar animations-tidslinje-objekt. Skrivskyddad [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Returnerar:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```


Returnerar TransitionEx-objektet som innehåller information om hur den angivna bilden avancerar under en bildspelspresentation. Skrivskyddad [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Returnerar:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```


Returnerar bildens bakgrund. Skrivskyddad [IBackground](../../com.aspose.slides/ibackground).

**Returnerar:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


Tillhandahåller enkel åtkomst till inbäddade hyperlänkar. Skrivskyddad [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returnerar:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


Anger om former på mastern bör visas på bilder eller inte. För master-bilden själv returnerar denna egenskap alltid false. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


Anger om former på mastern bör visas på bilder eller inte. För master-bilden själv returnerar denna egenskap alltid false. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```


Hittar den första förekomsten av en form med angiven alternativ text.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| altText | java.lang.String | Alternativ text. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) – ShapeEx-objekt eller null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Sammanfogar körningar med samma formatering i alla stycken i alla accepterade former.

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```


Fastställer huruvida de två IBaseSlide-instanserna är lika. Returnerat värde beräknas utifrån bildens struktur och statiskt innehåll. Två bilder är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i datum-platshållare.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide som ska jämföras med den aktuella IBaseSlide. |

**Returnerar:**
boolean – **true** om den angivna IBaseSlide är lika med den aktuella IBaseSlide; annars **false**.