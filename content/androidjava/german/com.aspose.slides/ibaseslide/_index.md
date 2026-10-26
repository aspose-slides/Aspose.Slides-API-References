---
title: IBaseSlide
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt gemeinsame Daten für alle Folientypen dar.
type: docs
url: /de/com.aspose.slides/ibaseslide/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Stellt gemeinsame Daten für alle Folientypen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShapes()](#getShapes--) | Gibt die Formen einer Folie zurück. |
| [getControls()](#getControls--) | Gibt die Sammlung von ActiveX-Steuerelementen einer Folie zurück. |
| [getName()](#getName--) | Gibt den Namen einer Folie zurück oder setzt ihn. |
| [setName(String value)](#setName-java.lang.String-) | Gibt den Namen einer Folie zurück oder setzt ihn. |
| [getSlideId()](#getSlideId--) | Gibt die ID einer Folie zurück. |
| [getCustomData()](#getCustomData--) | Gibt die benutzerdefinierten Daten der Folie zurück. |
| [getTimeline()](#getTimeline--) | Gibt das Animations-Zeitlinien-Objekt zurück. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Gibt das TransitionEx-Objekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Bildschirmpräsentation fortschreitet. |
| [getBackground()](#getBackground--) | Gibt den Hintergrund der Folie zurück. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Ermöglicht einfachen Zugriff auf enthaltene Hyperlinks. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Findet das erste Vorkommen einer Form mit dem angegebenen Alternativtext. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Verbindet Lauftexte mit gleicher Formatierung in allen Absätzen aller akzeptablen Formen. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. |
### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

Gibt die Formen einer Folie zurück. Nur lesend [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Rückgabe:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

Gibt die Sammlung von ActiveX-Steuerelementen einer Folie zurück. Nur lesend [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Rückgabe:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```

Gibt den Namen einer Folie zurück oder setzt ihn. Lesen/Schreiben String.

**Rückgabe:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Gibt den Namen einer Folie zurück oder setzt ihn. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

Gibt die ID einer Folie zurück. Nur lesend long.

**Rückgabe:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Gibt die benutzerdefinierten Daten der Folie zurück. Nur lesend [ICustomData](../../com.aspose.slides/icustomdata).

**Rückgabe:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

Gibt das Animations-Zeitlinien-Objekt zurück. Nur lesend [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Rückgabe:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

Gibt das TransitionEx-Objekt zurück, das Informationen darüber enthält, wie die angegebene Folie während einer Bildschirmpräsentation fortschreitet. Nur lesend [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Rückgabe:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

Gibt den Hintergrund der Folie zurück. Nur lesend [IBackground](../../com.aspose.slides/ibackground).

**Rückgabe:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Ermöglicht einfachen Zugriff auf enthaltene Hyperlinks. Nur lesend [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Rückgabe:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer false zurück. Lesen/Schreiben boolean.

**Rückgabe:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Gibt an, ob Formen auf der Masterfolie auf Folien angezeigt werden sollen oder nicht. Für die Masterfolie selbst gibt diese Eigenschaft immer false zurück. Lesen/Schreiben boolean.

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
**Rückgabe:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx-Objekt oder null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Verbindet Lauftexte mit gleicher Formatierung in allen Absätzen aller akzeptablen Formen.
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

Bestimmt, ob die beiden IBaseSlide-Instanzen gleich sind. Der Rückgabewert wird basierend auf der Struktur und dem statischen Inhalt der Folie berechnet. Zwei Folien sind gleich, wenn alle Formen, Stile, Texte, Animationen und andere Einstellungen usw. gleich sind. Der Vergleich berücksichtigt nicht eindeutige Identifikatorwerte, z. B. SlideId, und dynamische Inhalte, z. B. den aktuellen Datumswert im Datums-Platzhalter.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Das IBaseSlide, das mit dem aktuellen IBaseSlide verglichen werden soll. |
**Rückgabe:**
boolean - **true**, wenn das angegebene IBaseSlide dem aktuellen IBaseSlide gleich ist; sonst **false**.