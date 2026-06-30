---
title: Slide
second_title: Aspose.Sildes a .NET API Referenciához
description: Egy prezentáció diáját reprezentálja.
type: docs
weight: 9940
url: /hu/aspose.slides/slide/
---
## Slide osztály

Represents a slide in a presentation.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Visszaadja a dia háttérét. Csak olvasható [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Visszaadja a dia ActiveX vezérlők gyűjteményét. Csak olvasható [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Visszaadja a dia egyedi adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Visszaadja a dia HeaderFooter kezelőjét. Csak olvasható [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Megállapítja, hogy a megadott dia rejtett-e a diavetítés során. Olvasás/írás Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Könnyű hozzáférést biztosít a beágyazott hiperhivatkozásokhoz. Csak olvasható [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Visszaadja vagy beállítja az aktuális dia elrendezési diáját. Olvasás/írás [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Visszaadja vagy beállítja egy dia nevét. Olvasás/írás String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Lehetővé teszi a jegyzetdia elérését, hozzáadását és eltávolítását. Csak olvasható [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Visszaadja az IPresentation interfészt. Csak olvasható [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Visszaadja egy dia alakzatait. Csak olvasható [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Megadja, hogy a mesterdián lévő alakzatok megjelenjenek-e a diákon vagy sem. Olvasás/írás Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Visszaadja egy dia azonosítóját. Csak olvasható UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Visszaadja a dia számát. A dia indexe a [`Slides`](../presentation/slides) gyűjteményben mindig egyenlő a SlideNumber - Presentation.FirstSlideNumber értékkel. Olvasás/írás Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Visszaadja a Transition objektumot, amely információt tartalmaz arról, hogyan halad tovább a megadott dia a diavetítés során. Csak olvasható [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Visszaadja a felülbíráló téma kezelőt. Csak olvasható [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Visszaadja az animáció idővonal objektumot. Csak olvasható [`IAnimationTimeLine`](../ianimationtimeline). |

## Módszerek

| Név | Leírás |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Visszaad egy hatékony témát ehhez a diához. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Megállapítja, hogy a két IBaseSlide példány egyenlő-e. A visszatérési érték a dia szerkezete és statikus tartalma alapján kerül kiszámításra. Két dia egyenlő, ha minden alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmat, például a Dátum helyörzőben lévő aktuális dátumértéket. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Megkeresi az első olyan alakzatot, amely a megadott alternatív szöveggel rendelkezik. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Visszaad egy Thumbnail Image objektumot (a valós méret 20%-a). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Visszaad egy Thumbnail Image objektumot. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Visszaad egy Thumbnail tiff kép objektumot a megadott paraméterekkel. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Visszaad egy Thumbnail Image objektumot a megadott mérettel. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Visszaad egy Thumbnail Image objektumot egyedi méretezéssel. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Visszaad egy Thumbnail Image objektumot a megadott mérettel. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Visszaad egy Thumbnail Image objektumot egyedi méretezéssel. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Visszaadja az adott szerző által hozzáadott összes dia megjegyzést. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Összefűzi a futamokat azonos formázással az összes bekezdésben minden elfogadott alakzatban. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Összefűzi a futamokat azonos formázással az összes bekezdésben minden elfogadott alakzatban. |
| [Remove](../../aspose.slides/slide/remove)() | Eltávolítja a diát a prezentációból. |
| [Reset](../../aspose.slides/slide/reset)() | Visszaállítja a pozíciót, méretet és formázást minden olyan alakzatra, amelynek prototípusa van az LayoutSlide-on. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Mentse a dia tartalmát EMF fájlként. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Mentse a dia tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Mentse a dia tartalmát SVG fájlként. |

### Lásd még

* osztály [BaseSlide](../baseslide)
* interfész [ISlide](../islide)
* névterület [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->