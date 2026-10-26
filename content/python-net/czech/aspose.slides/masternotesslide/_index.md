---
title: MasterNotesSlide class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/masternotesslide/
---
## MasterNotesSlide třída

Představuje hlavní snímek pro poznámky.

**Dědičnost:**[`MasterNotesSlide`](/slides/python-net/cs/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/cs/aspose.slides/baseslide)

Typ MasterNotesSlide poskytuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`shapes`](/slides/python-net/cs/aspose.slides/masternotesslide/shapes/) | Vrací tvary snímku.<br/>            Pouze ke čtení [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/cs/aspose.slides/masternotesslide/controls/) | Vrací kolekci ActiveX ovládacích prvků na snímku.<br/>            Pouze ke čtení [`IControlCollection`](/slides/python-net/cs/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/cs/aspose.slides/masternotesslide/name/) | Vrací nebo nastavuje název snímku.<br/>            Čtení/zápis **str**. |
| [`slide_id`](/slides/python-net/cs/aspose.slides/masternotesslide/slide_id/) | Vrací ID snímku.<br/>            Pouze ke čtení **int**. |
| [`custom_data`](/slides/python-net/cs/aspose.slides/masternotesslide/custom_data/) | Vrací vlastní data snímku.<br/>            Pouze ke čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/cs/aspose.slides/masternotesslide/timeline/) | Vrací objekt časové osy animace.<br/>            Pouze ke čtení [`IAnimationTimeLine`](/slides/python-net/cs/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/cs/aspose.slides/masternotesslide/slide_show_transition/) | Vrací objekt Transition, který obsahuje informace o<br/>            tom, jak se určený snímek během prezentace posouvá.<br/>            Pouze ke čtení [`ISlideShowTransition`](/slides/python-net/cs/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/cs/aspose.slides/masternotesslide/background/) | Vrací pozadí snímku.<br/>            Pouze ke čtení [`IBackground`](/slides/python-net/cs/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/cs/aspose.slides/masternotesslide/hyperlink_queries/) | Poskytuje snadný přístup k obsaženým hypertextovým odkazům.<br/>            Pouze ke čtení [`IHyperlinkQueries`](/slides/python-net/cs/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/cs/aspose.slides/masternotesslide/show_master_shapes/) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích nebo ne.<br/>            Pro samotný hlavní snímek tato vlastnost vždy vrací `false`.<br/>            Čtení/zápis **bool**. |
| [`presentation`](/slides/python-net/cs/aspose.slides/masternotesslide/presentation/) | Vrací rozhraní IPresentation.<br/>            Pouze ke čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/cs/aspose.slides/masternotesslide/header_footer_manager/) | Vrací správce HeaderFooter hlavního poznámkového snímku.<br/>            Pouze ke čtení [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/cs/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/cs/aspose.slides/masternotesslide/theme_manager/) | Vrací správce motivu.<br/>            Pouze ke čtení [`IMasterThemeManager`](/slides/python-net/cs/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/cs/aspose.slides/masternotesslide/notes_style/) | Vrací styl textu poznámek.<br/>            Pouze ke čtení [`ITextStyle`](/slides/python-net/cs/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/cs/aspose.slides/masternotesslide/drawing_guides/) | Vrací kolekci kreslicích vodítek pro hlavní poznámkový snímek.<br/>            Pouze ke čtení [`IDrawingGuidesCollection`](/slides/python-net/cs/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/cs/aspose.slides/masternotesslide/slide/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/cs/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Spojuje úseky se stejným formátováním ve všech odstavcích ve všech přípustných tvarech. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/cs/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Spojuje úseky se stejným formátováním ve všech odstavcích ve všech přípustných tvarech. |
| [`equals(self, slide)`](/slides/python-net/cs/aspose.slides/masternotesslide/equals/#ibaseslide) | Určuje, zda jsou dvě instance IBaseSlide rovny.<br/>            Vrácená hodnota je vypočtena na základě struktury snímku a statického obsahu.<br/>            Dva snímky jsou rovny, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. rovny. Porovnání nezohledňuje jedinečné hodnoty identifikátorů, např. SlideId a dynamický obsah, např. aktuální hodnotu data v zástupci Data. |
| [`create_theme_effective(self)`](/slides/python-net/cs/aspose.slides/masternotesslide/create_theme_effective/#) | Vrací efektivní motiv pro tento snímek. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/cs/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Najde první výskyt tvaru s určeným alternativním textem. |

### Viz také
* třída [`BaseSlide`](/slides/python-net/cs/aspose.slides/baseslide)
* třída [`MasterNotesSlide`](/slides/python-net/cs/aspose.slides/masternotesslide)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)