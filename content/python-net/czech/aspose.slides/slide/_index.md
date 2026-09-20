---
title: Slide class
second_title: Aspose.Slides pro Python přes .NET – reference API
description: 
type: docs
url: /cs/aspose.slides/slide/
---
## Slide třída

Reprezentuje snímek v prezentaci.

**Dědičnost:**[`Slide`](/slides/python-net/cs/aspose.slides/slide) → [`BaseSlide`](/slides/python-net/cs/aspose.slides/baseslide)

Typ Slide poskytuje následující členy:

## Vlastnosti

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/cs/aspose.slides/slide/shapes/) | Vrací tvary snímku.<br/>            Pouze pro čtení [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/cs/aspose.slides/slide/controls/) | Vrací sbírku ActiveX ovládacích prvků na snímku.<br/>            Pouze pro čtení [`IControlCollection`](/slides/python-net/cs/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/cs/aspose.slides/slide/name/) | Vrací nebo nastavuje název snímku.<br/>            Čtení/zápis **str**. |
| [`slide_id`](/slides/python-net/cs/aspose.slides/slide/slide_id/) | Vrací ID snímku.<br/>            Pouze pro čtení **int**. |
| [`custom_data`](/slides/python-net/cs/aspose.slides/slide/custom_data/) | Vrací vlastní data snímku.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/cs/aspose.slides/slide/timeline/) | Vrací objekt animační časové osy.<br/>            Pouze pro čtení [`IAnimationTimeLine`](/slides/python-net/cs/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/cs/aspose.slides/slide/slide_show_transition/) | Vrací objekt Transition, který obsahuje informace o<br/>            tom, jak se určený snímek posouvá během prezentace.<br/>            Pouze pro čtení [`ISlideShowTransition`](/slides/python-net/cs/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/cs/aspose.slides/slide/background/) | Vrací pozadí snímku.<br/>            Pouze pro čtení [`IBackground`](/slides/python-net/cs/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/cs/aspose.slides/slide/hyperlink_queries/) | Poskytuje snadný přístup k obsaženým hypertextovým odkazům.<br/>            Pouze pro čtení [`IHyperlinkQueries`](/slides/python-net/cs/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/cs/aspose.slides/slide/show_master_shapes/) | Určuje, zda se tvary na hlavním snímku mají zobrazovat na snímcích nebo ne.<br/>            Čtení/zápis **bool**. |
| [`presentation`](/slides/python-net/cs/aspose.slides/slide/presentation/) | Vrací rozhraní IPresentation.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/cs/aspose.slides/slide/header_footer_manager/) | Vrací správce HeaderFooter snímku.<br/>            Pouze pro čtení [`ISlideHeaderFooterManager`](/slides/python-net/cs/aspose.slides/islideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/cs/aspose.slides/slide/theme_manager/) | Vrací správce přepisujícího motivu.<br/>            Pouze pro čtení [`IOverrideThemeManager`](/slides/python-net/cs/aspose.slides.theme/ioverridethememanager). |
| [`slide_number`](/slides/python-net/cs/aspose.slides/slide/slide_number/) | Vrací číslo snímku.<br/>            Index snímku v kolekci [`Presentation.slides`](/slides/python-net/cs/aspose.slides/presentation/slides) je vždy roven SlideNumber - Presentation.FirstSlideNumber.<br/>            Čtení/zápis **int**. |
| [`hidden`](/slides/python-net/cs/aspose.slides/slide/hidden/) | Určuje, zda je určený snímek během prezentace skrytý.<br/>            Čtení/zápis **bool**. |
| [`layout_slide`](/slides/python-net/cs/aspose.slides/slide/layout_slide/) | Vrací nebo nastavuje rozložení snímku pro aktuální snímek.<br/>            Čtení/zápis [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide). |
| [`notes_slide_manager`](/slides/python-net/cs/aspose.slides/slide/notes_slide_manager/) | Umožňuje přístup k poznámkovému snímku, přidávat a odstraňovat jej.<br/>            Pouze pro čtení [`INotesSlideManager`](/slides/python-net/cs/aspose.slides/inotesslidemanager). |
| [`slide`](/slides/python-net/cs/aspose.slides/slide/slide/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/cs/aspose.slides/slide/join_portions_with_same_formatting/#) | Spojí běhy s identickým formátováním ve všech odstavcích ve všech vyhovujících tvarech. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/cs/aspose.slides/slide/join_portions_with_same_formatting/#ishapecollection) | Spojí běhy s identickým formátováním ve všech odstavcích ve všech vyhovujících tvarech. |
| [`get_image(self, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/slide/get_image/#float-float) | Vrací objekt Miniatury obrázku s vlastním měřítkem. |
| [`get_image(self)`](/slides/python-net/cs/aspose.slides/slide/get_image/#) | Vrací objekt Miniatury obrázku (20 % skutečné velikosti). |
| [`get_image(self, image_size)`](/slides/python-net/cs/aspose.slides/slide/get_image/#asposepydrawingsize) | Vrací objekt Miniatury obrázku s určenou velikostí. |
| [`get_image(self, options)`](/slides/python-net/cs/aspose.slides/slide/get_image/#asposeslidesexportitiffoptions) | Vrací objekt Miniatury TIFF obrázku s určenými parametry. |
| [`get_image(self, options)`](/slides/python-net/cs/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions) | Vrací objekt Miniatury obrázku. |
| [`get_image(self, options, scale_x, scale_y)`](/slides/python-net/cs/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-float-float) | Vrací objekt Miniatury obrázku s vlastním měřítkem. |
| [`get_image(self, options, image_size)`](/slides/python-net/cs/aspose.slides/slide/get_image/#asposeslidesexportirenderingoptions-asposepydrawingsize) | Vrací objekt Miniatury obrázku s určenou velikostí. |
| [`write_as_svg(self, stream)`](/slides/python-net/cs/aspose.slides/slide/write_as_svg/#iorawiobase) | Ukládá obsah snímku jako soubor SVG. |
| [`write_as_svg(self, stream, svg_options)`](/slides/python-net/cs/aspose.slides/slide/write_as_svg/#iorawiobase-asposeslidesexportisvgoptions) | Ukládá obsah snímku jako soubor SVG. |
| [`equals(self, slide)`](/slides/python-net/cs/aspose.slides/slide/equals/#ibaseslide) | Určuje, zda jsou dvě instance IBaseSlide stejné.<br/>            Návratová hodnota je vypočtena na základě struktury snímku a statického obsahu.<br/>            Dva snímky jsou stejné, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. stejné. Porovnání nebere v úvahu hodnoty jedinečných identifikátorů, např. SlideId, ani dynamický obsah, např. aktuální datum v zástupci data. |
| [`create_theme_effective(self)`](/slides/python-net/cs/aspose.slides/slide/create_theme_effective/#) | Vrací efektivní motiv pro tento snímek. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/cs/aspose.slides/slide/find_shape_by_alt_text/#str) | Najde první výskyt tvaru s určeným alternativním textem. |
| [`write_as_emf(self, stream)`](/slides/python-net/cs/aspose.slides/slide/write_as_emf/#iorawiobase) | Ukládá obsah snímku jako soubor EMF. |
| [`remove(self)`](/slides/python-net/cs/aspose.slides/slide/remove/#) | Odstraňuje snímek z prezentace. |
| [`reset(self)`](/slides/python-net/cs/aspose.slides/slide/reset/#) | Resetuje pozici, velikost a formátování každého tvaru, který má prototyp na LayoutSlide. |
| [`get_slide_comments(self, author)`](/slides/python-net/cs/aspose.slides/slide/get_slide_comments/#icommentauthor) | Vrací všechny komentáře ke snímku přidané konkrétním autorem. |

### Viz také
* třída [`BaseSlide`](/slides/python-net/cs/aspose.slides/baseslide)
* třída [`Slide`](/slides/python-net/cs/aspose.slides/slide)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)