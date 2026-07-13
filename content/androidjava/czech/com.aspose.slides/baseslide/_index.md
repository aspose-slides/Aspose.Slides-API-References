---
title: BaseSlide
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje společná data pro všechny typy snímků.
type: docs
url: /cs/com.aspose.slides/baseslide/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Reprezentuje společná data pro všechny typy snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [getShapes()](#getShapes--) | Vrací tvary snímku. |
| [getControls()](#getControls--) | Vrací kolekci ovládacích prvků ActiveX na snímku. |
| [getName()](#getName--) | Vrací nebo nastavuje název snímku. |
| [setName(String value)](#setName-java.lang.String-) | Vrací nebo nastavuje název snímku. |
| [getSlideId()](#getSlideId--) | Vrací ID snímku. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Určuje, zda jsou dvě instance IBaseSlide rovny. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Spojuje úseky se stejným formátováním ve všech odstavcích ve všech použitelných tvarech. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Spojuje úseky se stejným formátováním ve všech odstavcích ve všech použitelných tvarech. |
| [createThemeEffective()](#createThemeEffective--) | Vrací efektivní motiv pro tento snímek. |
| [getCustomData()](#getCustomData--) | Vrací vlastní data snímku. |
| [getTimeline()](#getTimeline--) | Vrací objekt časové osy animace. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Vrací objekt Transition, který obsahuje informace o tom, jak se určený snímek posouvá během prezentace. |
| [getBackground()](#getBackground--) | Vrací pozadí snímku. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Poskytuje snadný přístup k obsaženým hypertextovým odkazům. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, nebo ne. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, nebo ne. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Vyhledá první výskyt tvaru s určeným alternativním textem. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Vrací rozhraní IPresentation. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Vrací tvary snímku. Pouze ke čtení [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Vrací:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Vrací kolekci ovládacích prvků ActiveX na snímku. Pouze ke čtení [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Vrací:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

Vrací nebo nastavuje název snímku. Čtení/zápis String.

**Vrací:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Vrací nebo nastavuje název snímku. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Vrací ID snímku. Pouze ke čtení long.

**Vrací:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

Určuje, zda jsou dvě instance IBaseSlide rovny. Návratová hodnota je vypočítána na základě struktury snímku a statického obsahu. Dva snímky jsou rovny, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. rovny. Porovnání nebere v úvahu jedinečné hodnoty identifikátorů, např. SlideId, a dynamický obsah, např. aktuální datum v zástupci data.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide k porovnání s aktuální IBaseSlide. |

**Vrací:**
boolean -  **true**  pokud je určený IBaseSlide roven aktuálnímu IBaseSlide; jinak,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Spojuje úseky se stejným formátováním ve všech odstavcích ve všech použitelných tvarech.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Spojuje úseky se stejným formátováním ve všech odstavcích ve všech použitelných tvarech.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Vrací efektivní motiv pro tento snímek.

**Vrací:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Vrací vlastní data snímku. Pouze ke čtení [ICustomData](../../com.aspose.slides/icustomdata).

**Vrací:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Vrací objekt časové osy animace. Pouze ke čtení [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Vrací:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Vrací objekt Transition, který obsahuje informace o tom, jak se určený snímek posouvá během prezentace. Pouze ke čtení [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Vrací:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Vrací pozadí snímku. Pouze ke čtení [IBackground](../../com.aspose.slides/ibackground).

**Vrací:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Poskytuje snadný přístup k obsaženým hypertextovým odkazům. Pouze ke čtení [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Vrací:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, nebo ne. Pro samotný hlavní snímek tato vlastnost vždy vrací false. Čtení/zápis boolean.

**Vrací:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích, nebo ne. Pro samotný hlavní snímek tato vlastnost vždy vrací false. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Vyhledá první výskyt tvaru s určeným alternativním textem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| altText | java.lang.String | Alternativní text. |

**Vrací:**
[IShape](../../com.aspose.slides/ishape) - objekt Shape nebo null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Vrací objekt Parent_Immediate. Pouze ke čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Vrací rozhraní IPresentation. Pouze ke čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Vrací základní snímek. Pouze ke čtení [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)