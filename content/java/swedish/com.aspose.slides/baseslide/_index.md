---
title: BaseSlide
second_title: Aspose.Slides för Java API-referens
description: Representerar gemensam data för alla bildtyper.
type: docs
url: /sv/com.aspose.slides/baseslide/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Representerar gemensam data för alla bildtyper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShapes()](#getShapes--) | Returnerar formerna på en bild. |
| [getControls()](#getControls--) | Returnerar samlingen av ActiveX-kontroller på en bild. |
| [getName()](#getName--) | Returnerar eller anger namnet på en bild. |
| [setName(String value)](#setName-java.lang.String-) | Returnerar eller anger namnet på en bild. |
| [getSlideId()](#getSlideId--) | Returnerar ID-et för en bild. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Avgör om de två IBaseSlide-instanserna är lika. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Sammanfogar körningar med samma formatering i alla stycken i alla godkända former. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Sammanfogar körningar med samma formatering i alla stycken i alla godkända former. |
| [createThemeEffective()](#createThemeEffective--) | Returnerar ett effektivt tema för denna bild. |
| [getCustomData()](#getCustomData--) | Returnerar bildens anpassade data. |
| [getTimeline()](#getTimeline--) | Returnerar animations-tidslinje-objektet. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Returnerar Transition-objektet som innehåller information om hur den angivna bilden avancerar under en bildspelsvisning. |
| [getBackground()](#getBackground--) | Returnerar bildens bakgrund. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Tillhandahåller enkel åtkomst till inbäddade hyperlänkar. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Anger om former på huvudbilden ska visas på bildspel eller inte. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Anger om former på huvudbilden ska visas på bildspel eller inte. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Hittar första förekomsten av en form med den angivna alternativa texten. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Returnerar IPresentation-gränssnittet. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Returnerar formerna på en bild. Skrivskyddad [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Returnerar:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Returnerar samlingen av ActiveX-kontroller på en bild. Skrivskyddad [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Returnerar:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

Returnerar eller anger namnet på en bild. Läs/skriv String.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Returnerar eller anger namnet på en bild. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Returnerar ID-et för en bild. Skrivskyddad long.

**Returnerar:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

Avgör om de två IBaseSlide-instanserna är lika. Returvärdet beräknas baserat på bildens struktur och statiska innehåll. Två bilder är lika om alla former, stilar, texter, animationer och andra inställningar osv. är lika. Jämförelsen tar inte hänsyn till unika identifierarvärden, t.ex. SlideId och dynamiskt innehåll, t.ex. aktuellt datumvärde i datum-platshållare.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide att jämföra med den aktuella IBaseSlide. |

**Returnerar:**
boolean - **true** om den angivna IBaseSlide är lika med den aktuella IBaseSlide; annars **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Sammanfogar körningar med samma formatering i alla stycken i alla godkända former.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Sammanfogar körningar med samma formatering i alla stycken i alla godkända former.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Returnerar ett effektivt tema för denna bild.

**Returnerar:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Returnerar bildens anpassade data. Skrivskyddad [ICustomData](../../com.aspose.slides/icustomdata).

**Returnerar:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Returnerar animations-tidslinje-objektet. Skrivskyddad [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Returnerar:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Returnerar Transition-objektet som innehåller information om hur den angivna bilden avancerar under en bildspelsvisning. Skrivskyddad [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Returnerar:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Returnerar bildens bakgrund. Skrivskyddad [IBackground](../../com.aspose.slides/ibackground).

**Returnerar:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Tillhandahåller enkel åtkomst till inbäddade hyperlänkar. Skrivskyddad [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returnerar:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Anger om former på huvudbilden ska visas på bildspel eller inte. För själva huvudbilden returnerar denna egenskap alltid false. Läs/skriv boolean.

**Returnerar:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Anger om former på huvudbilden ska visas på bildspel eller inte. För själva huvudbilden returnerar denna egenskap alltid false. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Hittar första förekomsten av en form med den angivna alternativa texten.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| altText | java.lang.String | Alternativ text. |

**Returnerar:**
[IShape](../../com.aspose.slides/ishape) - Shape-objekt eller null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objektet. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Returnerar IPresentation-gränssnittet. Skrivskyddad [IPresentation](../../com.aspose.slides/ipresentation).

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Returnerar den grundläggande bilden. Skrivskyddad [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returnerar:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)