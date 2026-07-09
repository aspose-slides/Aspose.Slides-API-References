---
title: Slide
second_title: Aspose.Sildes .NET API referencia
description: Egy diát ábrázol egy prezentációban.
type: docs
weight: 9960
url: /hu/aspose.slides/slide/
---
## Slide osztály

Egy diát ábrázol egy prezentációban.

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Visszaadja a dia háttérét. Csak olvasható [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Visszaadja a dia ActiveX vezérlőinek gyűjteményét. Csak olvasható [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Visszaadja a dia egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | Visszaadja a dia HeaderFooter kezelőjét. Csak olvasható [`ISlideHeaderFooterManager`](../islideheaderfootermanager). |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | Meghatározza, hogy a megadott dia rejtett-e a diavetítés során. Olvasás-írás Boolean. |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Kényelmes hozzáférést biztosít a beágyazott hiperhivatkozásokhoz. Csak olvasható [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | Visszaadja vagy beállítja az aktuális dia elrendezési diáját. Olvasás-írás [`ILayoutSlide`](../ilayoutslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Visszaadja vagy beállítja egy dia nevét. Olvasás-írás String. |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | Lehetővé teszi a jegyzetdia elérését, hozzáadását és eltávolítását. Csak olvasható [`INotesSlideManager`](../inotesslidemanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Visszaadja az IPresentation interfészt. Csak olvasható [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Visszaadja egy dia alakzatait. Csak olvasható [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | Megadja, hogy a mesterdia alakzatait meg kell-e jeleníteni a diákon. Olvasás-írás Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Visszaadja egy dia azonosítóját. Csak olvasható UInt32. |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | Visszaadja a dia számát. A dia indexe a [`Slides`](../presentation/slides) gyűjteményben mindig egyenlő a SlideNumber - Presentation.FirstSlideNumber értékkel. Olvasás-írás Int32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Visszaadja a Transition objektumot, amely információt tartalmaz a megadott dia előrehaladásáról a diavetítés során. Csak olvasható [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | Visszaadja a felülbíráló témakezelőt. Csak olvasható [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Visszaadja az animáció idővonal objektumot. Csak olvasható [`IAnimationTimeLine`](../ianimationtimeline). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Visszaad egy hatékony témát ehhez a diához. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Meghatározza, hogy a két IBaseSlide példány egyenlő-e. A visszatérési érték a dia struktúrája és statikus tartalma alapján kerül kiszámításra. Két dia akkor egyenlő, ha minden alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmat, például a Date Placeholder aktuális dátum értékét. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Megkeresi az első előfordulását egy alakzatnak a megadott alternatív szöveggel. |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | Visszaad egy Thumbnail Image objektumot (a valós méret 20%-a). |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | Visszaad egy Thumbnail Image objektumot. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | Visszaad egy Thumbnail tiff kép objektumot a megadott paraméterekkel. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | Visszaad egy Thumbnail Image objektumot a megadott mérettel. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | Visszaad egy Thumbnail Image objektumot egyedi méretezéssel. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | Visszaad egy Thumbnail Image objektumot a megadott mérettel. |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | Visszaad egy Thumbnail Image objektumot egyedi méretezéssel. |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | Visszaadja az adott szerző által hozzáadott összes dia megjegyzést. |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | Összevonja a futamokat azonos formázással minden bekezdésben az összes elfogadható alakzatban. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Összevonja a futamokat azonos formázással minden bekezdésben az összes elfogadható alakzatban. |
| [Remove](../../aspose.slides/slide/remove)() | Eltávolítja a diát a prezentációból. |
| [Reset](../../aspose.slides/slide/reset)() | Alaphelyzetbe állítja a pozíciót, méretet és formázást minden olyan alakzatra, amelynek prototípusa van a LayoutSlide-on. |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | Elmenti a dia tartalmát EMF fájlként. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | Elmenti a dia tartalmát SVG fájlként. |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | Elmenti a dia tartalmát SVG fájlként. |

### Lásd még

* osztály [BaseSlide](../baseslide)
* interfész [ISlide](../islide)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->