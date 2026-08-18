---
title: IBaseSlide
second_title: Aspose.Slides for Java API Referencia
description: Közös adatokat képvisel az összes dia típushoz.
type: docs
url: /hu/com.aspose.slides/ibaseslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Represents common data for all slide types.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getShapes()](#getShapes--) | Visszaadja a dia alakzatait. |
| [getControls()](#getControls--) | Visszaadja az ActiveX vezérlők gyűjteményét egy dián. |
| [getName()](#getName--) | Visszaadja vagy beállítja egy dia nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja vagy beállítja egy dia nevét. |
| [getSlideId()](#getSlideId--) | Visszaadja egy dia azonosítóját. |
| [getCustomData()](#getCustomData--) | Visszaadja a dia egyéni adatait. |
| [getTimeline()](#getTimeline--) | Visszaadja az animáció idővonal objektumát. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Visszaadja a TransitionEx objektumot, amely információkat tartalmaz arról, hogyan halad tovább a megadott dia egy prezentáció során. |
| [getBackground()](#getBackground--) | Visszaadja a dia hátterét. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Kényelmes hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. A mesterdia esetében ez a tulajdonság mindig hamis értéket ad vissza. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. A mesterdia esetében ez a tulajdonság mindig hamis értéket ad vissza. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Megkeresi az első olyan alakzatot, amelynek alternatív szövege a megadott. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Összefűzi a formázás szerint egyező szövegtöredékeket az összes bekezdésben minden elfogadható alakzatban. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Meghatározza, hogy a két IBaseSlide példány egyenlő-e. |

### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

Visszaadja a dia alakzatait. Csak olvasható [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Visszatér:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

Visszaadja az ActiveX vezérlők gyűjteményét egy dián. Csak olvasható [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Visszatér:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public abstract String getName()
```

Visszaadja vagy beállítja egy dia nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Visszaadja vagy beállítja egy dia nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

Visszaadja egy dia azonosítóját. Csak olvasható long.

**Visszatér:**
long
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Visszaadja a dia egyéni adatait. Csak olvasható [ICustomData](../../com.aspose.slides/icustomdata).

**Visszatér:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

Visszaadja az animáció idővonal objektumát. Csak olvasható [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Visszatér:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

Visszaadja a TransitionEx objektumot, amely információkat tartalmaz arról, hogyan halad tovább a megadott dia egy prezentáció során. Csak olvasható [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Visszatér:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

Visszaadja a dia hátterét. Csak olvasható [IBackground](../../com.aspose.slides/ibackground).

**Visszatér:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Kényelmes hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. Csak olvasható [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Visszatér:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. A mesterdia esetében ez a tulajdonság mindig hamis értéket ad vissza. Olvasás/írás boolean.

**Visszatér:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. A mesterdia esetében ez a tulajdonság mindig hamis értéket ad vissza. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

Megkeresi az első olyan alakzatot, amelynek alternatív szövege a megadott.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| altText | java.lang.String | Alternatív szöveg. |

**Visszatér:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx object vagy null.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Összefűzi a formázás szerint egyező szövegtöredékeket az összes bekezdésben minden elfogadható alakzatban.
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

Meghatározza, hogy a két IBaseSlide példány egyenlő-e. Az eredmény a dia szerkezete és statikus tartalma alapján kerül kiszámításra. Két dia egyenlő, ha az összes alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmat, például a Dátum helyőrzőben lévő aktuális dátum értékét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Az összehasonlítandó IBaseSlide a jelenlegi IBaseSlide-hez képest. |

**Visszatér:**
boolean - **true** ha a megadott IBaseSlide egyenlő a jelenlegi IBaseSlide-vel; egyébként **false**.