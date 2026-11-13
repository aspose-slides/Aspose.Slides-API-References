---
title: Slide
second_title: Aspose.Sildes .NET API-referencia
description: Egy diát képvisel egy prezentációban.
type: docs
weight: 9980
url: /hu/aspose.slides/slide/
---
## Slide osztály

Egy diát képvisel egy prezentációban.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Visszaadja a dia háttérképét. Csak olvasható [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Visszaadja a dián lévő ActiveX vezérlők gyűjteményét. Csak olvasható [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Visszaadja a dia egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Visszaadja a dia HeaderFooter kezelőjét. Csak olvasható [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Megadja, hogy a megadott dia rejtett-e a diavetítés alatt. Olvasás/írás Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Könnyű hozzáférést biztosít a beágyazott hiperhivatkozásokhoz. Csak olvasható [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Visszaadja vagy beállítja az aktuális dia elrendezését. Olvasás/írás [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Visszaadja vagy beállítja a dia nevét. Olvasás/írás String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Lehetővé teszi a jegyzet dia elérését, hozzáadását és eltávolítását. Csak olvasható [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Visszaadja az IPresentation interfészt. Csak olvasható [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Visszaadja a dia alakzatainak gyűjteményét. Csak olvasható [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. Olvasás/írás Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Visszaadja a dia azonosítóját. Csak olvasható UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Visszaadja a dia számát. A dia indexe a [`Slides`](../presentation/slides) gyűjteményben mindig egyenlő a SlideNumber - Presentation.FirstSlideNumber értékkel. Olvasás/írás Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Visszaadja a Transition objektumot, amely információt tartalmaz arról, hogyan halad tovább a megadott dia a diavetítés során. Csak olvasható [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Visszaadja a felülbíráló téma kezelőt. Csak olvasható [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Visszaadja az animáció idővonal objektumot. Csak olvasható [`IAnimationTimeLine`](../ianimationtimeline). |

## Módszerek

| Név | Leírás |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Visszaad egy hatékony témát ehhez a diához. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Megállapítja, hogy a két IBaseSlide példány egyenlő-e. A visszatérési érték a dia struktúrája és statikus tartalma alapján számítódik. Két dia egyenlő, ha minden alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmat, például a Dátum helyőrzőben jelenlegi dátumértéket. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Megkeresi az első olyan alakzatot, amelynek a megadott alternatív szövege van. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Visszaad egy Miniatűr Kép objektumot (a valós méret 20%-a). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Visszaad egy Miniatűr Kép objektumot. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Visszaad egy megadott paraméterekkel rendelkező Miniatűr tiff képet. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Visszaad egy megadott méretű Miniatűr Kép objektumot. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Visszaad egy egyedi átméretezéssel rendelkező Miniatűr Kép objektumot. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Visszaad egy megadott méretű Miniatűr Kép objektumot. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Visszaad egy egyedi átméretezéssel rendelkező Miniatűr Kép objektumot. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Visszaadja az adott szerző által hozzáadott összes dia megjegyzést. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Egyesíti a futamokat azonos formázással az összes bekezdésben minden megfelelő alakzaton. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Egyesíti a futamokat azonos formázással az összes bekezdésben minden megfelelő alakzaton. |
| [Remove](../../aspose.slides/slide/remove)() | Eltávolítja a diát a prezentációból. |
| [Reset](../../aspose.slides/slide/reset)() | Visszaállítja minden alakzat pozícióját, méretét és formázását, amelynek prototípusa a LayoutSlide-on van. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Elmenti a dia tartalmát EMF fájlként. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Elmenti a dia tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Elmenti a dia tartalmát SVG fájlként. |

### Lásd még

* osztály [BaseSlide](../baseslide)
* interfész [ISlide](../islide)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->