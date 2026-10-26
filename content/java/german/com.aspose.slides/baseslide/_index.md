---
title: BaseSlide
second_title: Aspose.Slides für Java API-Referenz
description: Stellt gemeinsame Daten für alle Folientypen bereit.
type: docs
url: /de/com.aspose.slides/baseslide/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Stellt gemeinsame Daten für alle Folientypen bereit.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShapes()](#getShapes--) | Gibt die Formen einer Folie zurück. |
| [getControls()](#getControls--) | Gibt die Sammlung von ActiveX-Steuerelementen einer Folie zurück. |
| [getName()](#getName--) | Gibt den Namen einer Folie zurück oder legt ihn fest. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen einer Folie zurück oder legt ihn fest. |
| [getSlideId()](#getSlideId--) | Gibt die ID einer Folie zurück. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Verbindet Abschnitte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Verbindet Abschnitte mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen. |
| [createThemeEffective()](#createThemeEffective--) | Gibt ein effektives Theme für diese Folie zurück. |
| [getCustomData()](#getCustomData--) | Gibt die benutzerdefinierten Daten der Folie zurück. |
| [getTimeline()](#getTimeline--) | Gibt das Animationszeitlinienobjekt zurück. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Gibt das Transition-Objekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Bildschirmschau fortschreitet. |
| [getBackground()](#getBackground--) | Gibt den Hintergrund der Folie zurück. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Stellt einfachen Zugriff auf enthaltene Hyperlinks bereit. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Legt fest, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Legt fest, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Gibt die IPresentation-Schnittstelle zurück. |
| [getSlide()](#getSlide--) |  |
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


Gibt die Formen einer Folie zurück. Nur-Lesen [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Rückgabewert:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```


Gibt die Sammlung von ActiveX-Steuerelementen einer Folie zurück. Nur-Lesen [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Rückgabewert:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```


Gibt den Namen einer Folie zurück oder legt ihn fest. Lese/Schreib String.

**Rückgabewert:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Gibt den Namen einer Folie zurück oder legt ihn fest. Lese/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```


Gibt die ID einer Folie zurück. Nur-Lesen long.

**Rückgabewert:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```


Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt nicht die eindeutigen Identifikatorwerte, z. B. SlideId, und dynamische Inhalte, z. B. das aktuelle Datum in einem Datumsplatzhalter.

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Das IBaseSlide, das mit dem aktuellen IBaseSlide verglichen werden soll. |

**Rückgabewert:**
boolean -  **true**  wenn das angegebene IBaseSlide dem aktuellen IBaseSlide entspricht; andernfalls  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```


Verbindet Abschnitte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen.
### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```


Verbindet Abschnitte mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


Gibt ein effektives Theme für diese Folie zurück.

**Rückgabewert:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


Gibt die benutzerdefinierten Daten der Folie zurück. Nur-Lesen [ICustomData](../../com.aspose.slides/icustomdata).

**Rückgabewert:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```


Gibt das Animationszeitlinienobjekt zurück. Nur-Lesen [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Rückgabewert:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```


Gibt das Transition-Objekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Bildschirmschau fortschreitet. Nur-Lesen [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Rückgabewert:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```


Gibt den Hintergrund der Folie zurück. Nur-Lesen [IBackground](../../com.aspose.slides/ibackground).

**Rückgabewert:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


Stellt einfachen Zugriff auf enthaltene Hyperlinks bereit. Nur-Lesen [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Rückgabewert:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


Legt fest, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer false zurück. Lese/Schreib boolean.

**Rückgabewert:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


Legt fest, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer false zurück. Lese/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```


Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| altText | java.lang.String | Alternativtext. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) - Shape-Objekt oder null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Parent_Immediate-Objekt zurück. Nur-Lesen IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Gibt die IPresentation-Schnittstelle zurück. Nur-Lesen [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabewert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Gibt die Basisschicht zurück. Nur-Lesen [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Rückgabewert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)