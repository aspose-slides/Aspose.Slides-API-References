---
title: LayoutSlide
second_title: Aspose.Sildes .NET API referencia
description: Egy elrendezési diát képvisel.
type: docs
weight: 7620
url: /hu/aspose.slides/layoutslide/
---
## LayoutSlide osztály

Egy elrendezési diát reprezentál.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Visszaadja a dia hátterét. Csak olvasható [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Visszaadja a dián található ActiveX vezérlők gyűjteményét. Csak olvasható [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Visszaadja a dia egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Visszaadja az elrendezési dia rajzsegédleteinek gyűjteményét. Csak olvasható [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Igaz értéket ad vissza, ha létezik legalább egy dia, amely ezen elrendezési diától függ. Csak olvasható Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Visszaadja az elrendezési dia fejléclábléc-kezelőjét. Csak olvasható [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Könnyű hozzáférést biztosít a benne lévő hiperhivatkozásokhoz. Csak olvasható [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Visszaadja ennek az elrendezési diáknak a layout típusát. Csak olvasható [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Visszaadja vagy beállítja a layout mesterdiáját. Olvasás/írás [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Visszaadja vagy beállítja egy dia nevét. Olvasás/írás String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Visszaadja az elrendezési dia helyőrző-kezelőjét. Csak olvasható [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Visszaadja az IPresentation interfészt. Csak olvasható [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Visszaadja egy dia alakzatait. Csak olvasható [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Megadja, hogy a mesterdia alakzatai megjelenjenek-e a diákon vagy sem. Olvasás/írás Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Visszaadja egy dia azonosítóját. Csak olvasható UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Visszaadja a Transition objektumot, amely információkat tartalmaz arról, hogyan halad előre a megadott dia a diavetítés során. Csak olvasható [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Visszaadja a felülbíráló téma-kezelőt. Csak olvasható [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Visszaadja az animáció idővonal objektumát. Csak olvasható [`IAnimationTimeLine`](../ianimationtimeline). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Visszaad egy hatékony témát ehhez a diához. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Meghatározza, hogy a két IBaseSlide példány egyenlő-e. A visszatérő értéket a dia szerkezete és statikus tartalma alapján számítják ki. Két dia egyenlő, ha az összes alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmat, például a Dátum helyőrző aktuális dátumértékét. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Megkeresi az első előfordulását egy alakzatnak a megadott alternatív szöveggel. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Visszaad egy tömböt az összes diával, amelyek ettől az elrendezési diától függenek. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Egyesíti a futásokat azonos formázással az összes bekezdésben és az összes elfogadható alakzatban. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Egyesíti a futásokat azonos formázással az összes bekezdésben és az összes elfogadható alakzatban. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Eltávolítja az elrendezést a prezentációból. |

### Lásd még

* osztály [BaseSlide](../baseslide)
* interfész [ILayoutSlide](../ilayoutslide)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->