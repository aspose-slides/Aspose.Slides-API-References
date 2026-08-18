---
title: BaseSlide
second_title: Aspose.Slides Java API Referenciája
description: Közös adatokat képvisel az összes diatípushoz.
type: docs
url: /hu/com.aspose.slides/baseslide/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

Közös adatokat képvisel az összes diatípushoz.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getShapes()](#getShapes--) | Visszaadja a dia alakzatait. |
| [getControls()](#getControls--) | Visszaadja egy dia ActiveX vezérlőinek gyűjteményét. |
| [getName()](#getName--) | Visszaadja vagy beállítja egy dia nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja vagy beállítja egy dia nevét. |
| [getSlideId()](#getSlideId--) | Visszaadja egy dia azonosítóját. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | Megállapítja, hogy a két IBaseSlide példány egyenlő-e. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Összevonja a futamokat azonos formázással az összes bekezdésben az összes elfogadható alakzatban. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | Összevonja a futamokat azonos formázással az összes bekezdésben az összes elfogadható alakzatban. |
| [createThemeEffective()](#createThemeEffective--) | Visszaad egy hatékony témát ehhez a diához. |
| [getCustomData()](#getCustomData--) | Visszaadja a dia saját adatát. |
| [getTimeline()](#getTimeline--) | Visszaadja az animáció idővonal objektumot. |
| [getSlideShowTransition()](#getSlideShowTransition--) | Visszaadja a Transition objektumot, amely információt tartalmaz arról, hogy a megadott dia hogyan halad előre egy diavetítés során. |
| [getBackground()](#getBackground--) | Visszaadja a dia háttérét. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | Megkeresi az első alakzatot a megadott alternatív szöveggel. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | Visszaadja az IPresentation interfészt. |
| [getSlide()](#getSlide--) |  |
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

Visszaadja egy dia alakzatait. Csak olvasható [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Visszatér:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

Visszaadja egy dia ActiveX vezérlőinek gyűjteményét. Csak olvasható [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Visszatér:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

Visszaadja vagy beállítja egy dia nevét. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Visszaadja vagy beállítja egy dia nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

Visszaadja egy dia azonosítóját. Csak olvasható long.

**Visszatér:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

Megállapítja, hogy a két IBaseSlide példány egyenlő-e. A visszatérő érték a dia szerkezete és statikus tartalma alapján számítódik. Két dia egyenlő, ha az összes alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmat, például a dátumhelyőrző aktuális dátumértékét.

--------------------

> ```
> Az alábbi példa bemutatja, hogyan hasonlíthatók össze két dia.
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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | Az IBaseSlide, amellyel a jelenlegi IBaseSlide-ot összehasonlítjuk. |

**Visszatér:**
boolean -  **true**  ha a megadott IBaseSlide egyenlő a jelenlegi IBaseSlide-del; egyébként  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

Összevonja a futamokat azonos formázással az összes bekezdésben az összes elfogadható alakzatban.
### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

Összevonja a futamokat azonos formázással az összes bekezdésben az összes elfogadható alakzatban.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

Visszaad egy hatékony témát ehhez a diához.

**Visszatér:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Visszaadja a dia saját adatát. Csak olvasható [ICustomData](../../com.aspose.slides/icustomdata).

**Visszatér:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

Visszaadja az animáció idővonal objektumot. Csak olvasható [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Visszatér:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

Visszaadja a Transition objektumot, amely információt tartalmaz arról, hogy a megadott dia hogyan halad előre egy diavetítés során. Csak olvasható [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Visszatér:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

Visszaadja a dia háttérét. Csak olvasható [IBackground](../../com.aspose.slides/ibackground).

**Visszatér:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. Csak olvasható [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Visszatér:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. A mesterdia saját esetében ez a tulajdonság mindig false-t ad vissza. Olvasás/írás boolean.

**Visszatér:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. A mesterdia saját esetében ez a tulajdonság mindig false-t ad vissza. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

Megkeresi az első alakzatot a megadott alternatív szöveggel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| altText | java.lang.String | Alternatív szöveg. |

**Visszatér:**
[IShape](../../com.aspose.slides/ishape) - Shape objektum vagy null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja az IPresentation interfészt. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatér:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja az alapdia objektumot. Csak olvasható [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Visszatér:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)