---
title: MasterSlide
second_title: Aspose.Sildes .NET API referenciája
description: Egy mesterdiát képvisel egy bemutatóban.
type: docs
weight: 8030
url: /hu/aspose.slides/masterslide/
---
## MasterSlide osztály

Represents a master slide in a presentation.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Visszaadja a dia háttérét. Csak olvasható [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Visszaadja a törzsszöveg stílusát. Csak olvasható [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Visszaadja a diához tartozó ActiveX vezérlők gyűjteményét. Csak olvasható [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Visszaadja a dia egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Visszaadja a mesterdia rajzoló útmutatóinak gyűjteményét. Csak olvasható [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Igaz értéket ad vissza, ha létezik legalább egy dia, amely függ ettől a mesterdiától. Csak olvasható Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Visszaadja a mesterdia HeaderFooter kezelőjét. Csak olvasható [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. Csak olvasható [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Visszaadja ennek a mesterdiának a gyermek elrendezésdiái gyűjteményét. Csak olvasható [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Visszaadja vagy beállítja egy mesterdia nevét. Olvasás/írás String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Visszaadja egy másik szöveg stílusát. Csak olvasható [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Visszaadja az IPresentation interfészt. Csak olvasható [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Meghatározza, hogy a megfelelő mester törlésre kerül-e, amikor az összes azt követő diát törlik. Megjegyzés: az Aspose.Slides önmagában soha nem távolít el használaton kívüli mestert; a használaton kívüli mesterek tényleges eltávolításához hívja meg a(z) [`RemoveUnused`](../masterslidecollection/removeunused) Olvasás/írás Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Visszaadja egy dia alakjait. Csak olvasható [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Megadja, hogy a mesterdián lévő alakzatok megjelenjenek-e a diákon vagy sem. A mesterdia esetén ez a tulajdonság mindig `false` értéket ad vissza. Olvasás/írás Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Visszaadja egy dia azonosítóját. Csak olvasható UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Visszaadja a Transition objektumot, amely információkat tartalmaz arról, hogyan lép tovább a megadott dia a diavetítés során. Csak olvasható [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Visszaadja a téma kezelőt. Csak olvasható [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Visszaadja az animáció idővonal objektumot. Csak olvasható [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Visszaadja egy címszöveg stílusát. Csak olvasható [`ITextStyle`](../itextstyle). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Létrehoz egy új mesterdiát a jelenlegi alapján, egy külső témát alkalmaz rá, és alkalmazza a létrehozott mesterdiát minden függő diára. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Visszaad egy hatékony témát ehhez a diához. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Megállapítja, hogy a két IBaseSlide példány egyenlő-e. A visszatérési érték a dia struktúrája és statikus tartalma alapján számítódik. Két dia egyenlő, ha minden alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmakat, például a Dátum helyőrző aktuális dátumértékét. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Megkeresi az adott alternatív szöveggel rendelkező alakzat első előfordulását. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Visszaad egy tömböt az összes diával, amelyek függnek ettől a mesterdiától. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Összevonja a ugyanazzal a formázással rendelkező futamokat az összes bekezdésben minden megfelelő alakzatban. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Összevonja a ugyanazzal a formázással rendelkező futamokat az összes bekezdésben minden megfelelő alakzatban. |

### Lásd még

* osztály [BaseSlide](../baseslide)
* interfész [IMasterSlide](../imasterslide)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->