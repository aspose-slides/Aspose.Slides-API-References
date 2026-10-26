---
title: MasterHandoutSlide class
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide třída

Představuje hlavní snímek pro podklady.

**Dědičnost:**[`MasterHandoutSlide`](/slides/python-net/cs/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/cs/aspose.slides/baseslide)

Typ MasterHandoutSlide poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`shapes`](/slides/python-net/cs/aspose.slides/masterhandoutslide/shapes/) | Vrací tvary snímku.<br/>            jen pro čtení [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/cs/aspose.slides/masterhandoutslide/controls/) | Vrací kolekci ActiveX ovládacích prvků na snímku.<br/>            jen pro čtení [`IControlCollection`](/slides/python-net/cs/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/cs/aspose.slides/masterhandoutslide/name/) | Vrací nebo nastavuje název snímku.<br/>            čtení/zápis **str**. |
| [`slide_id`](/slides/python-net/cs/aspose.slides/masterhandoutslide/slide_id/) | Vrací ID snímku.<br/>            jen pro čtení **int**. |
| [`custom_data`](/slides/python-net/cs/aspose.slides/masterhandoutslide/custom_data/) | Vrací vlastní data snímku.<br/>            jen pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/cs/aspose.slides/masterhandoutslide/timeline/) | Vrací objekt časové osy animace.<br/>            jen pro čtení [`IAnimationTimeLine`](/slides/python-net/cs/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/cs/aspose.slides/masterhandoutslide/slide_show_transition/) | Vrací objekt Transition, který obsahuje informace o<br/>            tom, jak se určený snímek během promítání posouvá.<br/>            jen pro čtení [`ISlideShowTransition`](/slides/python-net/cs/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/cs/aspose.slides/masterhandoutslide/background/) | Vrací pozadí snímku.<br/>            jen pro čtení [`IBackground`](/slides/python-net/cs/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/cs/aspose.slides/masterhandoutslide/hyperlink_queries/) | Poskytuje snadný přístup k obsaženým hyperodkazům.<br/>            jen pro čtení [`IHyperlinkQueries`](/slides/python-net/cs/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/cs/aspose.slides/masterhandoutslide/show_master_shapes/) | Určuje, zda se tvary na hlavním snímku mají zobrazovat na snímcích nebo ne.<br/>            Pro samotný hlavní snímek tato vlastnost vždy vrací `false`.<br/>            čtení/zápis **bool**. |
| [`presentation`](/slides/python-net/cs/aspose.slides/masterhandoutslide/presentation/) | Vrací rozhraní IPresentation.<br/>            jen pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/cs/aspose.slides/masterhandoutslide/header_footer_manager/) | Vrací správce HeaderFooter hlavního podkladového snímku.<br/>            jen pro čtení [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/cs/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/cs/aspose.slides/masterhandoutslide/theme_manager/) | Vrací správce motivu.<br/>            jen pro čtení [`IMasterThemeManager`](/slides/python-net/cs/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/cs/aspose.slides/masterhandoutslide/drawing_guides/) | Vrací kolekci kreslicích vodítek pro hlavní podkladový snímek.<br/>            jen pro čtení [`IDrawingGuidesCollection`](/slides/python-net/cs/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/cs/aspose.slides/masterhandoutslide/slide/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/cs/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Spojuje úseky se stejným formátováním ve všech odstavcích ve všech přijatelných tvarech. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/cs/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Spojuje úseky se stejným formátováním ve všech odstavcích ve všech přijatelných tvarech. |
| [`equals(self, slide)`](/slides/python-net/cs/aspose.slides/masterhandoutslide/equals/#ibaseslide) | Určuje, zda jsou dvě instance IBaseSlide rovny.<br/>            Vrácená hodnota je vypočtena na základě struktury snímku a statického obsahu.<br/>            Dva snímky jsou rovny, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. rovny. Porovnání nebere v úvahu jedinečné hodnoty identifikátorů, např. SlideId a dynamický obsah, např. aktuální hodnotu data v Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/cs/aspose.slides/masterhandoutslide/create_theme_effective/#) | Vrací efektivní motiv pro tento snímek. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/cs/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Najde první výskyt tvaru se zadaným alternativním textem. |

### Viz také
* třída [`BaseSlide`](/slides/python-net/cs/aspose.slides/baseslide)
* třída [`MasterHandoutSlide`](/slides/python-net/cs/aspose.slides/masterhandoutslide)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)