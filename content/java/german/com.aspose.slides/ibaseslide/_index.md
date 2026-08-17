---
title: IBaseSlide
second_title: Aspose.Slides für Java API Referenz
description: Stellt gemeinsame Daten für alle Folientypen bereit.
type: docs
url: /de/com.aspose.slides/ibaseslide/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Stellt gemeinsame Daten für alle Folientypen bereit.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShapes()](#getShapes--) | Gibt die Formen einer Folie zurück. |
| [getControls()](#getControls--) | Gibt die Sammlung von ActiveX-Steuerelementen auf einer Folie zurück. |
| [getName()](#getName--) | Gibt den Namen einer Folie zurück oder legt ihn fest. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen einer Folie zurück oder legt ihn fest. |
| [getSlideId()](#getSlideId--) | Gibt die ID einer Folie zurück. |
| [getCustomData()](#getCustomData--) | Gibt die benutzerdefinierten Daten der Folie zurück. |
| [getTimeline()](#getTimeline--) | Gibt das Animationszeitlinienobjekt zurück. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Gibt das TransitionEx-Objekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Bildschirmpräsentation fortschreitet. |
| [getBackground()](#getBackground--) | Gibt den Hintergrund der Folie zurück. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Stellt einfachen Zugriff auf enthaltene Hyperlinks bereit. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Verbindet Läufe mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. |

### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

Gibt die Formen einer Folie zurück. Nur lesbar [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Rückgabewert:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)

### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

Gibt die Sammlung von ActiveX-Steuerelementen auf einer Folie zurück. Nur lesbar [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Rückgabewert:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)

### getName() {#getName--}
```
public abstract String getName()
```

Gibt den Namen einer Folie zurück oder legt ihn fest. Lese-/Schreib String.

**Rückgabewert:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Gibt den Namen einer Folie zurück oder legt ihn fest. Lese-/Schreib String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

Gibt die ID einer Folie zurück. Nur lesbar long.

**Rückgabewert:**
long

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Gibt die benutzerdefinierten Daten der Folie zurück. Nur lesbar [ICustomData](../../com.aspose.slides/icustomdata).

**Rückgabewert:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

Gibt das Animationszeitlinienobjekt zurück. Nur lesbar [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Rückgabewert:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)

### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

Gibt das TransitionEx-Objekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Bildschirmpräsentation fortschreitet. Nur lesbar [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Rückgabewert:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)

### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

Gibt den Hintergrund der Folie zurück. Nur lesbar [IBackground](../../com.aspose.slides/ibackground).

**Rückgabewert:**
[IBackground](../../com.aspose.slides/ibackground)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Stellt einfachen Zugriff auf enthaltene Hyperlinks bereit. Nur lesbar [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Rückgabewert:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer false zurück. Lese-/Schreib boolean.

**Rückgabewert:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer false zurück. Lese-/Schreib boolean.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| altText | java.lang.String | Alternativtext. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx-Objekt oder null.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Verbindet Läufe mit gleicher Formatierung in allen Absätzen in allen zulässigen Formen.

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur der Folie und statischem Inhalt berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt keine eindeutigen Identifikatorwerte, z. B. SlideId, und keinen dynamischen Inhalt, z. B. den aktuellen Datumswert im Datums-Platzhalter.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Die IBaseSlide, mit der die aktuelle IBaseSlide verglichen wird. |

**Rückgabewert:**
boolean - **true** wenn die angegebene IBaseSlide gleich der aktuellen IBaseSlide ist; andernfalls **false**.