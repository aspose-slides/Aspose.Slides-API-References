---
title: IBaseSlide
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Közös adatokat képvisel az összes diatípushoz.
type: docs
url: /hu/com.aspose.slides/ibaseslide/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Közös adatokat képviseli az összes diatípushoz.
## Metódusok

| Method | Description |
| --- | --- |
| [getShapes()](#getShapes--) | Visszaadja a dia alakzatait. |
| [getControls()](#getControls--) | Visszaadja a diára vonatkozó ActiveX vezérlők gyűjteményét. |
| [getName()](#getName--) | Visszaadja vagy beállítja a dia nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja vagy beállítja a dia nevét. |
| [getSlideId()](#getSlideId--) | Visszaadja a dia azonosítóját. |
| [getCustomData()](#getCustomData--) | Visszaadja a dia egyedi adatait. |
| [getTimeline()](#getTimeline--) | Visszaadja az animáció idővonal objektumát. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Visszaadja a TransitionEx objektumot, amely információkat tartalmaz arról, hogyan halad tovább a megadott dia a diavetítés során. |
| [getBackground()](#getBackground--) | Visszaadja a dia háttérét. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Megkeresi a megadott alternatív szöveggel rendelkező alakzat első előfordulását. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Összevonja az azonos formázású futamokat az összes megfelelő alakzat összes bekezdésében. |
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

Visszaadja a diára vonatkozó ActiveX vezérlők gyűjteményét. Csak olvasható [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Visszatér:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)

### getName() {#getName--}
```
public abstract String getName()
```

Visszaadja vagy beállítja a dia nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

Visszaadja vagy beállítja a dia nevét. Olvasás/írás String.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

Visszaadja a dia azonosítóját. Csak olvasható long.

**Visszatér:**
long

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Visszaadja a dia egyedi adatait. Csak olvasható [ICustomData](../../com.aspose.slides/icustomdata).

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

Visszaadja a TransitionEx objektumot, amely információkat tartalmaz arról, hogyan halad tovább a megadott dia a diavetítés során. Csak olvasható [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Visszatér:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)

### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

Visszaadja a dia háttérét. Csak olvasható [IBackground](../../com.aspose.slides/ibackground).

**Visszatér:**
[IBackground](../../com.aspose.slides/ibackground)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. Csak olvasható [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Visszatér:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. A mesterdia esetében ez a tulajdonság mindig false értéket ad vissza. Olvasás/írás boolean.

**Visszatér:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. A mesterdia esetében ez a tulajdonság mindig false értéket ad vissza. Olvasás/írás boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

Megkeresi a megadott alternatív szöveggel rendelkező alakzat első előfordulását.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| altText | java.lang.String | Alternatív szöveg. |

**Visszatér:**
[IShape](../../com.aspose.slides/ishape) - ShapeEx objektum vagy null.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Összevonja az azonos formázású futamokat az összes megfelelő alakzat összes bekezdésében.

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

Meghatározza, hogy a két IBaseSlide példány egyenlő-e. A visszatérési érték a dia struktúrája és statikus tartalma alapján kerül kiszámításra. Két dia akkor egyenlő, ha az összes alakzat, stílus, szöveg, animáció és egyéb beállítások stb. egyenlőek. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t, és a dinamikus tartalmakat, például a Dátumhelyőrzőben lévő aktuális dátum értékét.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | A jelenlegi IBaseSlide-pel összehasonlítandó IBaseSlide. |

**Visszatér:**
boolean - **true** ha a megadott IBaseSlide egyenlő a jelenlegi IBaseSlide-pel; egyébként **false**.