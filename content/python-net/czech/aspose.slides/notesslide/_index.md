---
title: NotesSlide class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/notesslide/
---
## NotesSlide třída

Představuje snímek poznámek v prezentaci.

**Dědičnost:**[`NotesSlide`](/slides/python-net/cs/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/cs/aspose.slides/baseslide)

Typ NotesSlide vystavuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`shapes`](/slides/python-net/cs/aspose.slides/notesslide/shapes/) | Vrací tvary snímku.<br/>            Pouze pro čtení [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/cs/aspose.slides/notesslide/controls/) | Vrací kolekci ovládacích prvků ActiveX na snímku.<br/>            Pouze pro čtení [`IControlCollection`](/slides/python-net/cs/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/cs/aspose.slides/notesslide/name/) | Vrací nebo nastavuje název snímku.<br/>            Čtení/Zápis **str**. |
| [`slide_id`](/slides/python-net/cs/aspose.slides/notesslide/slide_id/) | Vrací ID snímku.<br/>            Pouze pro čtení **int**. |
| [`custom_data`](/slides/python-net/cs/aspose.slides/notesslide/custom_data/) | Vrací vlastní data snímku.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/cs/aspose.slides/notesslide/timeline/) | Vrací objekt časové osy animace.<br/>            Pouze pro čtení [`IAnimationTimeLine`](/slides/python-net/cs/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/cs/aspose.slides/notesslide/slide_show_transition/) | Vrací objekt Transition, který obsahuje informace o<br/>            tom, jak se určený snímek posouvá během prezentace.<br/>            Pouze pro čtení [`ISlideShowTransition`](/slides/python-net/cs/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/cs/aspose.slides/notesslide/background/) | Vrací pozadí snímku.<br/>            Pouze pro čtení [`IBackground`](/slides/python-net/cs/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/cs/aspose.slides/notesslide/hyperlink_queries/) | Poskytuje snadný přístup k obsaženým hypertextovým odkazům.<br/>            Pouze pro čtení [`IHyperlinkQueries`](/slides/python-net/cs/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/cs/aspose.slides/notesslide/show_master_shapes/) | Určuje, zda mají být tvary v hlavním snímku zobrazeny na snímcích nebo ne.<br/>            Čtení/Zápis **bool**. |
| [`presentation`](/slides/python-net/cs/aspose.slides/notesslide/presentation/) | Vrací rozhraní IPresentation.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/cs/aspose.slides/notesslide/header_footer_manager/) | Vrací správce HeaderFooter poznámkového snímku.<br/>            Pouze pro čtení [`INotesSlideHeaderFooterManager`](/slides/python-net/cs/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/cs/aspose.slides/notesslide/notes_text_frame/) | Vrací TextFrame s textem poznámek, pokud existuje.<br/>            Pouze pro čtení [`ITextFrame`](/slides/python-net/cs/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/cs/aspose.slides/notesslide/theme_manager/) | Vrací správce přepisujícího motivu.<br/>            Pouze pro čtení [`IOverrideThemeManager`](/slides/python-net/cs/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/cs/aspose.slides/notesslide/parent_slide/) | Vrací nadřazený snímek.<br/>            Pouze pro čtení [`ISlide`](/slides/python-net/cs/aspose.slides/islide). |
| [`slide`](/slides/python-net/cs/aspose.slides/notesslide/slide/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/cs/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Spojí běhy se stejným formátováním ve všech odstavcích ve všech povolených tvarech. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/cs/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Spojí běhy se stejným formátováním ve všech odstavcích ve všech povolených tvarech. |
| [`equals(self, slide)`](/slides/python-net/cs/aspose.slides/notesslide/equals/#ibaseslide) | Určuje, zda jsou dvě instance IBaseSlide rovny.<br/>            Návratová hodnota je vypočítána na základě struktury snímku a statického obsahu.<br/>            Dva snímky jsou rovny, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. rovny. Porovnání nezohledňuje jedinečné hodnoty identifikátorů, např. SlideId a dynamický obsah, např. aktuální hodnotu data v zástupci data. |
| [`create_theme_effective(self)`](/slides/python-net/cs/aspose.slides/notesslide/create_theme_effective/#) | Vrací efektivní motiv pro tento snímek. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/cs/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Najde první výskyt tvaru se zadaným alternativním textem. |

### Viz také
* třída [`BaseSlide`](/slides/python-net/cs/aspose.slides/baseslide)
* třída [`NotesSlide`](/slides/python-net/cs/aspose.slides/notesslide)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)