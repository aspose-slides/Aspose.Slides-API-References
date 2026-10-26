---
title: BaseSlide
second_title: Aspose.Slides für Android über Java API-Referenz
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
| [getControls()](#getControls--) | Gibt die Sammlung der ActiveX-Steuerelemente einer Folie zurück. |
| [getName()](#getName--) | Gibt den Namen einer Folie zurück oder setzt ihn. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen einer Folie zurück oder setzt ihn. |
| [getSlideId()](#getSlideId--) | Gibt die ID einer Folie zurück. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Fügt Lauftexte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen zusammen. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Fügt Lauftexte mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen zusammen. |
| [createThemeEffective()](#createThemeEffective--) | Gibt ein wirksames Theme für diese Folie zurück. |
| [getCustomData()](#getCustomData--) | Gibt die benutzerdefinierten Daten der Folie zurück. |
| [getTimeline()](#getTimeline--) | Gibt das Animationszeitlinienobjekt zurück. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Gibt das Transition-Objekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Bildschirmpräsentation fortschreitet. |
| [getBackground()](#getBackground--) | Gibt den Hintergrund der Folie zurück. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Bietet einfachen Zugriff auf enthaltene Hyperlinks. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Gibt an, ob Formen der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Gibt an, ob Formen der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Gibt die IPresentation-Schnittstelle zurück. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Gibt die Formen einer Folie zurück. Nur lesbar [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Rückgabewert:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Gibt die Sammlung der ActiveX-Steuerelemente einer Folie zurück. Nur lesbar [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Rückgabewert:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

Gibt den Namen einer Folie zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Gibt den Namen einer Folie zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Gibt die ID einer Folie zurück. Nur lesbar long.

**Rückgabewert:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Bezeichnerwerte, z. B. SlideId, und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert in einem Datumsplatzhalter.

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
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Die IBaseSlide, mit der die aktuelle IBaseSlide verglichen wird. |

**Rückgabewert:**
boolean -  **true**  wenn die angegebene IBaseSlide gleich der aktuellen IBaseSlide ist; andernfalls **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Fügt Lauftexte mit gleicher Formatierung in allen Absätzen aller zulässigen Formen zusammen.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Fügt Lauftexte mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen zusammen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |

### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Gibt ein wirksames Theme für diese Folie zurück.

**Rückgabewert:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Gibt die benutzerdefinierten Daten der Folie zurück. Nur lesbar [ICustomData](../../com.aspose.slides/icustomdata).

**Rückgabewert:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Gibt das Animationszeitlinienobjekt zurück. Nur lesbar [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Rückgabewert:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Gibt das Transition-Objekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Bildschirmpräsentation fortschreitet. Nur lesbar [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Rückgabewert:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Gibt den Hintergrund der Folie zurück. Nur lesbar [IBackground](../../com.aspose.slides/ibackground).

**Rückgabewert:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Bietet einfachen Zugriff auf enthaltene Hyperlinks. Nur lesbar [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Rückgabewert:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Gibt an, ob Formen der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer false zurück. Lesen/Schreiben boolean.

**Rückgabewert:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Gibt an, ob Formen der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer false zurück. Lesen/Schreiben boolean.

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

Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Gibt die IPresentation-Schnittstelle zurück. Nur lesbar [IPresentation](../../com.aspose.slides/ipresentation).

**Rückgabewert:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Gibt die Basissfolie zurück. Nur lesbar [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Rückgabewert:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)