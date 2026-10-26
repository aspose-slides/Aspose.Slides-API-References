---
title: BaseSlide
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje wspólne dane dla wszystkich typów slajdów.
type: docs
url: /pl/com.aspose.slides/baseslide/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Reprezentuje wspólne dane dla wszystkich typów slajdów.
## Metody

| Metoda | Opis |
| --- | --- |
| [getShapes()](#getShapes--) | Zwraca kształty slajdu. |
| [getControls()](#getControls--) | Zwraca kolekcję kontrolek ActiveX na slajdzie. |
| [getName()](#getName--) | Zwraca lub ustawia nazwę slajdu. |
| [setName(String value)](#setName-java.lang.String-) | Zwraca lub ustawia nazwę slajdu. |
| [getSlideId()](#getSlideId--) | Zwraca identyfikator slajdu. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Określa, czy dwa wystąpienia IBaseSlide są równe. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [createThemeEffective()](#createThemeEffective--) | Zwraca efektywny motyw dla tego slajdu. |
| [getCustomData()](#getCustomData--) | Zwraca niestandardowe dane slajdu. |
| [getTimeline()](#getTimeline--) | Zwraca obiekt osi czasu animacji. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Zwraca obiekt Transition, który zawiera informacje o tym, jak określony slajd przechodzi w trakcie pokazu slajdów. |
| [getBackground()](#getBackground--) | Zwraca tło slajdu. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Umożliwia łatwy dostęp do zawartych hiperłączy. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Określa, czy kształty na slajdzie nadrzędnym mają być wyświetlane na slajdach, czy nie. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Określa, czy kształty na slajdzie nadrzędnym mają być wyświetlane na slajdach, czy nie. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Znajduje pierwsze wystąpienie kształtu o podanym alternatywnym tekście. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Zwraca interfejs IPresentation. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Zwraca kształty slajdu. tylko do odczytu [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Zwraca:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```


Zwraca kolekcję kontrolek ActiveX na slajdzie. tylko do odczytu [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Zwraca:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```


Zwraca lub ustawia nazwę slajdu. odczyt/zapis String.

**Zwraca:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Zwraca lub ustawia nazwę slajdu. odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```


Zwraca identyfikator slajdu. tylko do odczytu long.

**Zwraca:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```


Określa, czy dwa wystąpienia IBaseSlide są równe. Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia, itp., są identyczne. Porównanie nie uwzględnia unikalnych wartości identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. bieżącej wartości daty w miejscu daty.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide do porównania z bieżącym IBaseSlide. |

**Zwraca:**
boolean -  **true**  jeśli podany IBaseSlide jest równy bieżącemu IBaseSlide; w przeciwnym razie,  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```


Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```


Łączy fragmenty o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Zwraca efektywny motyw dla tego slajdu.

**Zwraca:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Zwraca niestandardowe dane slajdu. tylko do odczytu [ICustomData](../../com.aspose.slides/icustomdata).

**Zwraca:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```


Zwraca obiekt osi czasu animacji. tylko do odczytu [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Zwraca:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```


Zwraca obiekt Transition, który zawiera informacje o tym, jak określony slajd przechodzi w trakcie pokazu slajdów. tylko do odczytu [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Zwraca:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```


Zwraca tło slajdu. tylko do odczytu [IBackground](../../com.aspose.slides/ibackground).

**Zwraca:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Umożliwia łatwy dostęp do zawartych hiperłączy. tylko do odczytu [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Zwraca:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


Określa, czy kształty na slajdzie nadrzędnym mają być wyświetlane na slajdach, czy nie. Dla samego slajdu nadrzędnego ta własność zawsze zwraca false. odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


Określa, czy kształty na slajdzie nadrzędnym mają być wyświetlane na slajdach, czy nie. Dla samego slajdu nadrzędnego ta własność zawsze zwraca false. odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```


Znajduje pierwsze wystąpienie kształtu o podanym alternatywnym tekście.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| altText | java.lang.String | Alternatywny tekst. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - obiekt Shape lub null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Zwraca obiekt Parent_Immediate. tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Zwraca interfejs IPresentation. tylko do odczytu [IPresentation](../../com.aspose.slides/ipresentation).

**Zwraca:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Zwraca podstawowy slajd. tylko do odczytu [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Zwraca:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)