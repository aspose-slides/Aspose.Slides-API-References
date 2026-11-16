---
title: MasterSlide
second_title: Aspose.Sildes .NET API referencia
description: Egy prezentációban képviseli a mesterdiát.
type: docs
weight: 8050
url: /hu/aspose.slides/masterslide/
---
## MasterSlide osztály

Represents a master slide in a presentation.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Tulajdonságok

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Visszaadja a dia háttérét. Csak olvasható [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Visszaadja a törzsszöveg stílusát. Csak olvasható [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Visszaadja a dián található ActiveX vezérlők gyűjteményét. Csak olvasható [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Visszaadja a dia egyedi adatát. Csak olvasható [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Visszaadja a mesterdia rajzsegédleteinek gyűjteményét. Csak olvasható [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Igazat ad vissza, ha létezik legalább egy dia, amely ettől a mesterdiától függ. Csak olvasható Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Visszaadja a mesterdia HeaderFooter kezelőjét. Csak olvasható [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Könnyű hozzáférést biztosít a tartalmazott hiperhivatkozásokhoz. Csak olvasható [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Visszaadja ennek a mesterdiának a gyermekelrendezés-díák gyűjteményét. Csak olvasható [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Visszaadja vagy beállítja egy mesterdia nevét. Olvasható/írható String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Visszaadja egy másik szöveg stílusát. Csak olvasható [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Visszaadja az IPresentation interfészt. Csak olvasható [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Megállapítja, hogy a megfelelő mester törlésre kerül-e, ha az összes, a mestert követő diát törlik. Megjegyzés: Az Aspose.Slides önmagában soha nem távolít el nem használt mestert; a nem használt mesterek tényleges eltávolításához hívja meg [`RemoveUnused`](../masterslidecollection/removeunused) Olvasható/írható Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Visszaadja egy dia alakzatait. Csak olvasható [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. A mesterdia esetében ez a tulajdonság mindig `false` értéket ad vissza. Olvasható/írható Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Visszaadja egy dia azonosítóját. Csak olvasható UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Visszaadja a Transition objektumot, amely információkat tartalmaz a megadott dia előrehaladásáról a diavetítés során. Csak olvasható [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Visszaadja a téma kezelőt. Csak olvasható [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Visszaadja az animáció idővonal objektumot. Csak olvasható [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Visszaadja egy címszöveg stílusát. Csak olvasható [`ITextStyle`](../itextstyle). |

## Módszerek

| Name | Description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Létrehoz egy új mesterdiát a jelenlegi alapján, külső témát alkalmaz rá, és a létrehozott mesterdiát az összes függő diára alkalmazza. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Visszaad egy hatékony témát ehhez a diához. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Meghatározza, hogy a két IBaseSlide példány egyenlő-e. A visszatérő értéket a dia felépítése és statikus tartalma alapján számítják ki. Két dia akkor egyenlő, ha az összes alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t, és a dinamikus tartalmat, például a dátumhelyőrzőben lévő aktuális dátumot. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Megkeresi a megadott alternatív szöveget tartalmazó alakzat első előfordulását. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Visszaad egy tömböt az összes olyan diával, amely ettől a mesterdiától függ. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Összevonja az azonos formázású futamokat az összes bekezdésben az összes megfelelő alakzatban. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Összevonja az azonos formázású futamokat az összes bekezdésben az összes megfelelő alakzatban. |

### Lásd még

* osztály [BaseSlide](../baseslide)
* interfész [IMasterSlide](../imasterslide)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->