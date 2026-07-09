---
title: LayoutSlide
second_title: Aspose.Sildes .NET API Referencia
description: Egy elrendezési diát képvisel.
type: docs
weight: 7640
url: /hu/aspose.slides/layoutslide/
---
## LayoutSlide osztály

Az elrendezési dia képviselője.

```csharp
public sealed class LayoutSlide : BaseSlide, ILayoutSlide
```

## Tulajdonságok

| Név | Leírás |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Visszaadja a dia háttérét. Csak olvasható [`IBackground`](../ibackground). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Visszaadja a dián lévő ActiveX vezérlők gyűjteményét. Csak olvasható [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Visszaadja a dia egyéni adatait. Csak olvasható [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/layoutslide/drawingguides) { get; } | Visszaadja az elrendezési dia rajzútmutatóinak gyűjteményét. Csak olvasható [`IDrawingGuidesCollection`](../idrawingguidescollection). |
| [HasDependingSlides](../../aspose.slides/layoutslide/hasdependingslides) { get; } | Igazat ad vissza, ha létezik legalább egy dia, amely ettől az elrendezési diától függ. Csak olvasható Boolean. |
| [HeaderFooterManager](../../aspose.slides/layoutslide/headerfootermanager) { get; } | Visszaadja az elrendezési dia HeaderFooter kezelőjét. Csak olvasható [`ILayoutSlideHeaderFooterManager`](../ilayoutslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Egyszerű hozzáférést biztosít a beágyazott hiperhivatkozásokhoz. Csak olvasható [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutType](../../aspose.slides/layoutslide/layouttype) { get; } | Visszaadja ennek az elrendezési diáknak a layout típusát. Csak olvasható [`SlideLayoutType`](../slidelayouttype). |
| [MasterSlide](../../aspose.slides/layoutslide/masterslide) { get; set; } | Visszaadja vagy beállítja a layout mester diát. Olvasás/írás [`IMasterSlide`](../imasterslide). |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | Visszaadja vagy beállítja egy dia nevét. Olvasás/írás String. |
| [PlaceholderManager](../../aspose.slides/layoutslide/placeholdermanager) { get; } | Visszaadja az elrendezési dia helyőrzőkezelőjét. Csak olvasható [`ILayoutPlaceholderManager`](../ilayoutplaceholdermanager). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Visszaadja az IPresentation interfészt. Csak olvasható [`IPresentation`](../ipresentation). |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Visszaadja egy dia alakzatait. Csak olvasható [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/layoutslide/showmastershapes) { get; set; } | Megadja, hogy a mester dián lévő alakzatok megjelenjenek-e a diákon vagy sem. Olvasás/írás Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Visszaadja egy dia azonosítóját. Csak olvasható UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Visszaadja a Transition objektumot, amely információt tartalmaz arról, hogyan halad tovább a megadott dia a diavetítés során. Csak olvasható [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/layoutslide/thememanager) { get; } | Visszaadja a felülbíráló téma kezelőt. Csak olvasható [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Visszaadja az animáció idővonal objektumot. Csak olvasható [`IAnimationTimeLine`](../ianimationtimeline). |

## Metódusok

| Név | Leírás |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Visszaad egy hatékony témát ehhez a diához. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Megállapítja, hogy a két IBaseSlide példány egyenlő-e. A visszatérő értéket a dia struktúrája és statikus tartalma alapján számítják ki. Két dia akkor egyenlő, ha az összes alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmakat, például a dátumhelyőrzőben lévő aktuális dátum értékét. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Megkeresi az első előfordulását egy alakzatnak a megadott helyettesítő szöveggel. |
| [GetDependingSlides](../../aspose.slides/layoutslide/getdependingslides)() | Visszaad egy tömböt az összes olyan diákkal, amelyek ettől az elrendezési diától függenek. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Egyesíti a formázásban egyező futásokat az összes bekezdésben minden alkalmas alakzaton. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Egyesíti a formázásban egyező futásokat az összes bekezdésben minden alkalmas alakzaton. |
| [Remove](../../aspose.slides/layoutslide/remove)() | Eltávolítja az elrendezést a prezentációból. |

### Lásd még

* osztály [BaseSlide](../baseslide)
* interfész [ILayoutSlide](../ilayoutslide)
* névtér [Aspose.Slides](../../aspose.slides)
* összeállítás [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->