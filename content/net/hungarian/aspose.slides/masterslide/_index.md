---
title: MasterSlide
second_title: Aspose.Sildes .NET API referenciája
description: Egy prezentációban egy mesterdia képviselője.
type: docs
weight: 8010
url: /hu/aspose.slides/masterslide/
---
## MasterSlide class

Egy mesterdia reprezentálása egy prezentációban.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Properties

| Name | Description |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Visszaadja a dia háttérét. Csak olvasható [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Visszaadja a törzsszöveg stílusát. Csak olvasható [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Visszaadja az ActiveX vezérlők gyűjteményét a dián. Csak olvasható [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Visszaadja a dia egyedi adatát. Csak olvasható [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Visszaadja a mesterdia rajzolási segédvonalainak gyűjteményét. Csak olvasható [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Igaz értéket ad vissza, ha legalább egy dia függ ettől a mesterdiától. Csak olvasható Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Visszaadja a mesterdia fejléc/lábléc kezelőjét. Csak olvasható [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Egyszerű hozzáférést biztosít a benne lévő hiperhivatkozásokhoz. Csak olvasható [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Visszaadja a gyermek elrendezési diák gyűjteményét ehhez a mesterdiához. Csak olvasható [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Visszaadja vagy beállítja egy mesterdia nevét. Olvasható/írható String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Visszaadja egy másik szöveg stílusát. Csak olvasható [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Visszaadja az IPresentation interfészt. Csak olvasható [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Meghatározza, hogy a megfelelő mester törlődik-e, amikor az összes rá épülő dia törlésre kerül. Megjegyzés: az Aspose.Slides soha nem távolít el önmagától használaton kívüli mestert; a használaton kívüli mesterek tényleges eltávolításához hívd meg a [`RemoveUnused`](../masterslidecollection/removeunused) metódust. Olvasható/írható Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Visszaadja a dia alakzatjait. Csak olvasható [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Meghatározza, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. Maga a mesterdia esetén ez a tulajdonság mindig `false` értéket ad. Olvasható/írható Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Visszaadja a dia azonosítóját. Csak olvasható UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Visszaadja a Transition objektumot, amely információkat tartalmaz a dia előrehaladásáról a diavetítés során. Csak olvasható [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Visszaadja a téma kezelőt. Csak olvasható [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Visszaadja az animáció idővonal objektumát. Csak olvasható [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Visszaadja a cím szöveg stílusát. Csak olvasható [`ITextStyle`](../itextstyle). |

## Methods

| Name | Description |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Létrehoz egy új mesterdiát az aktuális alapján, külső témát alkalmaz rá, és a létrehozott mestert minden függő diára alkalmazza. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Visszaad egy hatékony témát ehhez a diához. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Meghatározza, hogy a két IBaseSlide példány egyenlő-e. Az eredmény értéke a dia szerkezete és statikus tartalma alapján kerül számításra. Két dia akkor egyenlő, ha minden alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosítók értékeit, pl. SlideId, valamint a dinamikus tartalmat, pl. a Dátum helyőrzőben lévő aktuális dátumot. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Megkeresi egy alakzat első előfordulását a megadott alternatív szöveggel. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Visszaad egy tömböt az összes diával, amelyek ebből a mesterdiából függenek. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Egyesíti a hasonló formázású futamokat minden bekezdésben az összes elfogadható alakzatban. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Egyesíti a hasonló formázású futamokat minden bekezdésben az összes elfogadható alakzatban. |

### See Also

* osztály [BaseSlide](../baseslide)
* interfész [IMasterSlide](../imasterslide)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->