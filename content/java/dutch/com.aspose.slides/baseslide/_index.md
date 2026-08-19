---
title: BaseSlide
second_title: Aspose.Slides voor Java API-referentie
description: Stelt gemeenschappelijke gegevens voor alle diatypes voor.
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

Stelt gemeenschappelijke gegevens voor alle type dia's voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShapes()](#getShapes--) | Retourneert de vormen van een dia. |
| [getControls()](#getControls--) | Retourneert de verzameling ActiveX-besturingselementen op een dia. |
| [getName()](#getName--) | Retourneert of stelt de naam van een dia in. |
| [setName(String value)](#setName-java.lang.String-) | Retourneert of stelt de naam van een dia in. |
| [getSlideId()](#getSlideId--) | Retourneert de ID van een dia. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Bepaalt of de twee IBaseSlide-instanties gelijk zijn. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Voegt runs met dezelfde opmaak samen in alle alinea's in alle acceptabele vormen. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Voegt runs met dezelfde opmaak samen in alle alinea's in alle acceptabele vormen. |
| [createThemeEffective()](#createThemeEffective--) | Retourneert een effectief thema voor deze dia. |
| [getCustomData()](#getCustomData--) | Retourneert de aangepaste gegevens van de dia. |
| [getTimeline()](#getTimeline--) | Retourneert animatietijdlijnobject. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Retourneert het Transition-object dat informatie bevat over hoe de opgegeven dia tijdens een diavoorstelling wordt voortgezet. |
| [getBackground()](#getBackground--) | Retourneert de achtergrond van de dia. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Biedt gemakkelijke toegang tot ingesloten hyperlinks. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Geeft aan of vormen op de masterdia op dia's moeten worden weergegeven of niet. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Geeft aan of vormen op de masterdia op dia's moeten worden weergegeven of niet. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Vindt de eerste instantie van een vorm met de opgegeven alternatieve tekst. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Retourneert IPresentation-interface. |
| [getSlide()](#getSlide--) |  |
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Retourneert de vormen van een dia. Alleen lezen [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Retourneert:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```


Retourneert de verzameling ActiveX-besturingselementen op een dia. Alleen lezen [IControlCollection](../../com.aspose.slides/icontrolcollection).

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```


Retourneert de ID van een dia. Alleen lezen long.

**Retourneert:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```


Bepaalt of de twee IBaseSlide-instanties gelijk zijn. De geretourneerde waarde wordt berekend op basis van de structuur en statische inhoud van de dia. Twee dia's zijn gelijk als alle vormen, stijlen, teksten, animaties en andere instellingen, enz., gelijk zijn. De vergelijking houdt geen rekening met unieke identificatiewaarden, bijvoorbeeld SlideId, en dynamische inhoud, bijvoorbeeld de huidige datumnotering in een datum-placeholder.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | De IBaseSlide om te vergelijken met de huidige IBaseSlide. |

**Retourneert:**
boolean -  **true**  als de opgegeven IBaseSlide gelijk is aan de huidige IBaseSlide; anders,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```


Voegt runs met dezelfde opmaak samen in alle alinea's in alle acceptabele vormen.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```


Voegt runs met dezelfde opmaak samen in alle alinea's in alle acceptabele vormen.

**Parameters:**
| Parameter | Type | Beschrijving |
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


Retourneert de aangepaste gegevens van de dia. Alleen lezen [ICustomData](../../com.aspose.slides/icustomdata).

**Retourneert:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```


Retourneert animatietijdlijnobject. Alleen lezen [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Retourneert:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```


Retourneert het Transition-object dat informatie bevat over hoe de opgegeven dia tijdens een diavoorstelling wordt voortgezet. Alleen lezen [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Retourneert:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```


Retourneert de achtergrond van de dia. Alleen lezen [IBackground](../../com.aspose.slides/ibackground).

**Retourneert:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Biedt gemakkelijke toegang tot ingesloten hyperlinks. Alleen lezen [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Retourneert:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


Geeft aan of vormen op de masterdia op dia's moeten worden weergegeven of niet. Voor de masterdia zelf geeft deze eigenschap altijd false terug. Lezen/Schrijven boolean.

**Retourneert:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


Geeft aan of vormen op de masterdia op dia's moeten worden weergegeven of niet. Voor de masterdia zelf geeft deze eigenschap altijd false terug. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```


Vindt de eerste instantie van een vorm met de opgegeven alternatieve tekst.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| altText | java.lang.String | Alternatieve tekst. |

**Retourneert:**
[IShape](../../com.aspose.slides/ishape) - Shape-object of null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate-object. Alleen lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Retourneert IPresentation-interface. Alleen lezen [IPresentation](../../com.aspose.slides/ipresentation).

**Retourneert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Retourneert de basisdia. Alleen lezen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Retourneert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)