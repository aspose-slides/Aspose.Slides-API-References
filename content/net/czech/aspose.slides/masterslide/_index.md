---
title: MasterSlide
second_title: Aspose.Sildes pro .NET API Reference
description: Reprezentuje hlavní snímek v prezentaci.
type: docs
weight: 8010
url: /cs/aspose.slides/masterslide/
---
## MasterSlide třída

Representuje hlavní snímek v prezentaci.

```csharp
public class MasterSlide : BaseSlide, IMasterSlide
```

## Vlastnosti

| Název | Popis |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | Vrací pozadí snímku. Pouze pro čtení [`IBackground`](../ibackground). |
| [BodyStyle](../../aspose.slides/masterslide/bodystyle) { get; } | Vrací styl těla textu. Pouze pro čtení [`ITextStyle`](../itextstyle). |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | Vrací kolekci ActiveX ovladačů na snímku. Pouze pro čtení [`IControlCollection`](../icontrolcollection). |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | Vrací vlastní data snímku. Pouze pro čtení [`ICustomData`](../icustomdata). |
| [DrawingGuides](../../aspose.slides/masterslide/drawingguides) { get; } | Vrací kolekci kreslicích vodítek pro hlavní snímek. Pouze pro čtení [`IDrawingGuidesCollection`](../idrawingguidescollection) |
| [HasDependingSlides](../../aspose.slides/masterslide/hasdependingslides) { get; } | Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto hlavním snímku. Pouze pro čtení Boolean. |
| [HeaderFooterManager](../../aspose.slides/masterslide/headerfootermanager) { get; } | Vrací správce HeaderFooter hlavního snímku. Pouze pro čtení [`IMasterSlideHeaderFooterManager`](../imasterslideheaderfootermanager). |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | Poskytuje snadný přístup k obsaženým hypertextovým odkazům. Pouze pro čtení [`IHyperlinkQueries`](../ihyperlinkqueries). |
| [LayoutSlides](../../aspose.slides/masterslide/layoutslides) { get; } | Vrací kolekci podřízených rozložení snímků pro tento hlavní snímek. Pouze pro čtení [`IMasterLayoutSlideCollection`](../imasterlayoutslidecollection). |
| override [Name](../../aspose.slides/masterslide/name) { get; set; } | Vrací nebo nastavuje název hlavního snímku. Čtení/zápis String. |
| [OtherStyle](../../aspose.slides/masterslide/otherstyle) { get; } | Vrací styl jiného textu. Pouze pro čtení [`ITextStyle`](../itextstyle). |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | Vrací rozhraní IPresentation. Pouze pro čtení [`IPresentation`](../ipresentation). |
| [Preserve](../../aspose.slides/masterslide/preserve) { get; set; } | Určuje, zda bude odpovídající hlavní snímek smazán, když jsou smazány všechny snímky, které ho následně používají. Poznámka: Aspose.Slides nikdy neodstraní nepoužitý hlavní snímek automaticky, pro skutečné odstranění nepoužitých hlavních snímků zavolejte [`RemoveUnused`](../masterslidecollection/removeunused) Čtení/zápis Boolean. |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | Vrací tvary snímku. Pouze pro čtení [`IShapeCollection`](../ishapecollection). |
| override [ShowMasterShapes](../../aspose.slides/masterslide/showmastershapes) { get; set; } | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích nebo ne. Pro samotný hlavní snímek tato vlastnost vždy vrací `false`. Čtení/zápis Boolean. |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | Vrací ID snímku. Pouze pro čtení UInt32. |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | Vrací objekt Transition, který obsahuje informace o tom, jak se určený snímek posouvá během prezentace. Pouze pro čtení [`ISlideShowTransition`](../islideshowtransition). |
| [ThemeManager](../../aspose.slides/masterslide/thememanager) { get; } | Vrací správce motivu. Pouze pro čtení [`IMasterThemeManager`](../../aspose.slides.theme/imasterthememanager). |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | Vrací objekt časové osy animací. Pouze pro čtení [`IAnimationTimeLine`](../ianimationtimeline). |
| [TitleStyle](../../aspose.slides/masterslide/titlestyle) { get; } | Vrací styl titulního textu. Pouze pro čtení [`ITextStyle`](../itextstyle). |

## Metody

| Název | Popis |
| --- | --- |
| [ApplyExternalThemeToDependingSlides](../../aspose.slides/masterslide/applyexternalthemetodependingslides)(string) | Vytvoří nový hlavní snímek na základě aktuálního, použije na něj externí motiv a použije vytvořený hlavní snímek na všechny závislé snímky. |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | Vrací efektivní motiv pro tento snímek. |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | Určuje, zda jsou dvě instance IBaseSlide rovny. Návratová hodnota je vypočítána na základě struktury snímku a statického obsahu. Dva snímky jsou rovny, pokud jsou všechny tvary, styly, texty, animace a ostatní nastavení atd. rovny. Porovnání nebere v úvahu jedinečné identifikátory, např. SlideId, ani dynamický obsah, např. aktuální hodnotu data v Date Placeholder. |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | Najde první výskyt tvaru se zadaným alternativním textem. |
| [GetDependingSlides](../../aspose.slides/masterslide/getdependingslides)() | Vrací pole se všemi snímky, které závisí na tomto hlavním snímku. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)() | Spojí běhy se stejným formátováním ve všech odstavcích všech akceptovatelných tvarů. |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | Spojí běhy se stejným formátováním ve všech odstavcích ve všech akceptovatelných tvarech. |

### Viz také

* třída [BaseSlide](../baseslide)
* rozhraní [IMasterSlide](../imasterslide)
* jmenný prostor [Aspose.Slides](../../aspose.slides)
* sestavení [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->