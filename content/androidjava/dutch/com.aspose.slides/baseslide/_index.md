---
title: BaseSlide
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt gemeenschappelijke gegevens voor alle diatypen voor.
type: docs
url: /nl/com.aspose.slides/baseslide/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Stelt gemeenschappelijke gegevens voor alle diatype voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShapes()](#getShapes--) | Retourneert de shapes van een dia. |
| [getControls()](#getControls--) | Retourneert de collectie van ActiveX-controles op een dia. |
| [getName()](#getName--) | Retourneert of stelt de naam van een dia in. |
| [setName(String value)](#setName-java.lang.String-) | Retourneert of stelt de naam van een dia in. |
| [getSlideId()](#getSlideId--) | Retourneert de ID van een dia. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs samen met dezelfde opmaak in alle alinea's van alle acceptabele vormen. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Voegt runs samen met dezelfde opmaak in alle alinea's van alle acceptabele vormen. |
| [createThemeEffective()](#createThemeEffective--) | Retourneert een effectief thema voor deze dia. |
| [getCustomData()](#getCustomData--) | Retourneert de aangepaste gegevens van de dia. |
| [getTimeline()](#getTimeline--) | Retourneert animatietijdlijnobject. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Retourneert het Transition-object dat informatie bevat over hoe de opgegeven dia vordert tijdens een diavoorstelling. |
| [getBackground()](#getBackground--) | Retourneert de achtergrond van de dia. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Biedt gemakkelijke toegang tot de aanwezige hyperlinks. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Specificeert of vormen op de masterslide getoond moeten worden op dia's of niet. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Specificeert of vormen op de masterslide getoond moeten worden op dia's of niet. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Vindt de eerste voorkoming van een vorm met de opgegeven alternatieve tekst. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Retourneert IPresentation-interface. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Retourneert de shapes van een dia. Alleen-lezen [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Retourneert:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Retourneert de collectie van ActiveX-controles op een dia. Alleen-lezen [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Retourneert:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

Retourneert of stelt de naam van een dia in. Lezen/Schrijven String.

**Retourneert:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Retourneert of stelt de naam van een dia in. Lezen/Schrijven String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Retourneert de ID van een dia. Alleen-lezen long.

**Retourneert:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

Bepaalt of de twee IBaseSlide-instanties gelijk zijn. De geretourneerde waarde wordt berekend op basis van de structuur en statische inhoud van de dia. Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen etc. gelijk zijn. De vergelijking houdt geen rekening met unieke identifier-waarden, bijv. SlideId, en dynamische inhoud, bijv. de huidige datumwaarde in de Date Placeholder.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | De IBaseSlide om te vergelijken met de huidige IBaseSlide. |

**Returns:**
boolean -  **true**  if the specified IBaseSlide is equal to the current IBaseSlide; otherwise,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Voegt runs samen met dezelfde opmaak in alle alinea's van alle acceptabele vormen.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Voegt runs samen met dezelfde opmaak in alle alinea's van alle acceptabele vormen.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Retourneert een effectief thema voor deze dia.

**Retourneert:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Retourneert de aangepaste gegevens van de dia. Alleen-lezen [ICustomData](../../com.aspose.slides/icustomdata).

**Retourneert:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Retourneert animatietijdlijnobject. Alleen-lezen [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Retourneert:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Retourneert het Transition-object dat informatie bevat over hoe de opgegeven dia vordert tijdens een diavoorstelling. Alleen-lezen [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Retourneert:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Retourneert de achtergrond van de dia. Alleen-lezen [IBackground](../../com.aspose.slides/ibackground).

**Retourneert:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Biedt gemakkelijke toegang tot de aanwezige hyperlinks. Alleen-lezen [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retourneert:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Specificeert of vormen op de masterslide getoond moeten worden op dia's of niet. Voor de masterslide zelf retourneert deze eigenschap altijd false. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Specificeert of vormen op de masterslide getoond moeten worden op dia's of niet. Voor de masterslide zelf retourneert deze eigenschap altijd false. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Vindt de eerste voorkoming van een vorm met de opgegeven alternatieve tekst.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| altText | java.lang.String | Alternatieve tekst. |

**Retourneert:**
[IShape](../../com.aspose.slides/ishape) - Shape object of null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Retourneert IPresentation-interface. Alleen-lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Retourneert de basisdia. Alleen-lezen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)