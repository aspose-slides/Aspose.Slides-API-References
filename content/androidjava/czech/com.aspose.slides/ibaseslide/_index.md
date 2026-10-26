---
title: IBaseSlide
second_title: Aspose.Slides pro Android přes Java API
description: Reprezentuje společná data pro všechny typy snímků.
type: docs
url: /cs/com.aspose.slides/ibaseslide/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Reprezentuje společná data pro všechny typy snímků.
## Metody

| Method | Description |
| --- | --- |
| [getShapes()](#getShapes--) | Vrací tvary snímku. |
| [getControls()](#getControls--) | Vrací kolekci ovládacích prvků ActiveX na snímku. |
| [getName()](#getName--) | Vrací nebo nastavuje název snímku. |
| [setName(String value)](#setName-java.lang.String-) | Vrací nebo nastavuje název snímku. |
| [getSlideId()](#getSlideId--) | Vrací ID snímku. |
| [getCustomData()](#getCustomData--) | Vrací vlastní data snímku. |
| [getTimeline()](#getTimeline--) | Vrací objekt časové osy animace. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Vrací objekt TransitionEx, který obsahuje informace o tom, jak se určený snímek postupuje během prezentace. |
| [getBackground()](#getBackground--) | Vrací pozadí snímku. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Poskytuje snadný přístup k obsaženým hyperodkazům. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Určuje, zda by měly být tvary na hlavním snímku zobrazeny na snímcích, nebo ne. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Určuje, zda by měly být tvary na hlavním snímku zobrazeny na snímcích, nebo ne. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Najde první výskyt tvaru s určeným alternativním textem. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Spojí běhy se stejným formátováním ve všech odstavcích ve všech vhodných tvarech. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Určuje, zda jsou dvě instance IBaseSlide rovny. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```


Vrací tvary snímku. Pouze pro čtení [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Vrací:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```


Vrací kolekci ovládacích prvků ActiveX na snímku. Pouze pro čtení [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Vrací:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```


Vrací nebo nastavuje název snímku. Čtení/zápis String.

**Vrací:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


Vrací nebo nastavuje název snímku. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```


Vrací ID snímku. Pouze pro čtení long.

**Vrací:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```


Vrací vlastní data snímku. Pouze pro čtení [ICustomData](../../com.aspose.slides/icustomdata).

**Vrací:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```


Vrací objekt časové osy animace. Pouze pro čtení [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Vrací:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```


Vrací objekt TransitionEx, který obsahuje informace o tom, jak se určený snímek postupuje během prezentace. Pouze pro čtení [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Vrací:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```


Vrací pozadí snímku. Pouze pro čtení [IBackground](../../com.aspose.slides/ibackground).

**Vrací:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```


Poskytuje snadný přístup k obsaženým hyperodkazům. Pouze pro čtení [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Vrací:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


Určuje, zda by měly být tvary na hlavním snímku zobrazeny na snímcích, nebo ne. Pro samotný hlavní snímek tato vlastnost vždy vrací false. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


Určuje, zda by měly být tvary na hlavním snímku zobrazeny na snímcích, nebo ne. Pro samotný hlavní snímek tato vlastnost vždy vrací false. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```


Najde první výskyt tvaru s určeným alternativním textem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| altText | java.lang.String | Alternativní text. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx object or null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Spojí běhy se stejným formátováním ve všech odstavcích ve všech vhodných tvarech.

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```


Určuje, zda jsou dvě instance IBaseSlide rovny. Návratová hodnota je vypočítána na základě struktury snímku a statického obsahu. Dva snímky jsou stejné, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. stejné. Porovnání nebere v úvahu hodnoty jedinečných identifikátorů, např. SlideId a dynamický obsah, např. aktuální datum v zástupci data.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | The IBaseSlide to compare with the current IBaseSlide. |

**Vrací:**
boolean - **true** if the specified IBaseSlide is equal to the current IBaseSlide; otherwise, **false**.