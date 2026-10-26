---
title: IBaseSlide
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje wspólne dane dla wszystkich typów slajdów.
type: docs
url: /pl/com.aspose.slides/ibaseslide/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Reprezentuje wspólne dane dla wszystkich typów slajdów.
## Metody

| Metoda | Opis |
| --- | --- |
| [getShapes()](#getShapes--) | Zwraca kształty slajdu. |
| [getControls()](#getControls--) | Zwraca kolekcję kontrolek ActiveX na slajdzie. |
| [getName()](#getName--) | Zwraca lub ustawia nazwę slajdu. |
| [setName(String value)](#setName-java.lang.String-) | Zwraca lub ustawia nazwę slajdu. |
| [getSlideId()](#getSlideId--) | Zwraca identyfikator (ID) slajdu. |
| [getCustomData()](#getCustomData--) | Zwraca własne dane slajdu. |
| [getTimeline()](#getTimeline--) | Zwraca obiekt osi czasu animacji. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Zwraca obiekt TransitionEx, który zawiera informacje o tym, jak określony slajd przechodzi w trakcie pokazu slajdów. |
| [getBackground()](#getBackground--) | Zwraca tło slajdu. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Umożliwia łatwy dostęp do zawartych hiperłączy. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Określa, czy kształty na slajdzie wzorcowym mają być wyświetlane na slajdach. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Określa, czy kształty na slajdzie wzorcowym mają być wyświetlane na slajdach. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Znajduje pierwsze wystąpienie kształtu o określonym alternatywnym tekście. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Łączy fragmenty tekstu o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Określa, czy dwa wystąpienia IBaseSlide są równe. |

### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

Zwraca kształty slajdu. Tylko do odczytu [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Zwraca:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

Zwraca kolekcję kontrolek ActiveX na slajdzie. Tylko do odczytu [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Zwraca:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```

Zwraca lub ustawia nazwę slajdu. Odczyt/zapis String.

**Zwraca:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Zwraca lub ustawia nazwę slajdu. Odczyt/zapis String.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

Zwraca identyfikator (ID) slajdu. Tylko do odczytu long.

**Zwraca:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Zwraca własne dane slajdu. Tylko do odczytu [ICustomData](../../com.aspose.slides/icustomdata).

**Zwraca:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

Zwraca obiekt osi czasu animacji. Tylko do odczytu [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Zwraca:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

Zwraca obiekt TransitionEx, który zawiera informacje o tym, jak określony slajd przechodzi w trakcie pokazu slajdów. Tylko do odczytu [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Zwraca:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

Zwraca tło slajdu. Tylko do odczytu [IBackground](../../com.aspose.slides/ibackground).

**Zwraca:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Umożliwia łatwy dostęp do zawartych hiperłączy. Tylko do odczytu [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Zwraca:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Określa, czy kształty na slajdzie wzorcowym mają być wyświetlane na slajdach. Dla samego slajdu wzorcowego ta właściwość zawsze zwraca false. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Określa, czy kształty na slajdzie wzorcowym mają być wyświetlane na slajdach. Dla samego slajdu wzorcowego ta właściwość zawsze zwraca false. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

Znajduje pierwsze wystąpienie kształtu o określonym alternatywnym tekście.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| altText | java.lang.String | Tekst alternatywny. |

**Zwraca:**
[IShape](../../com.aspose.slides/ishape) - obiekt ShapeEx lub null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Łączy fragmenty tekstu o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach.

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

Określa, czy dwa wystąpienia IBaseSlide są równe. Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są równe. Porównanie nie uwzględnia unikalnych wartości identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. bieżącej wartości daty w miejscu wybioru daty.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide do porównania z bieżącym IBaseSlide. |

**Zwraca:**
boolean - **true** jeśli określony IBaseSlide jest równy bieżącemu IBaseSlide; w przeciwnym razie **false**.