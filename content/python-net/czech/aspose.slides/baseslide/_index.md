---
title: BaseSlide class
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/baseslide/
---
## BaseSlide třída

Zastupuje společná data pro všechny typy snímků.

Typ BaseSlide zpřístupňuje následující členy:

## Vlastnosti

| Vlastnost | Popis |
| :- | :- |
| [`shapes`](/slides/python-net/cs/aspose.slides/baseslide/shapes/) | Vrací tvary snímku.<br/>            Pouze pro čtení [`IShapeCollection`](/slides/python-net/cs/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/cs/aspose.slides/baseslide/controls/) | Vrací kolekci ActiveX ovládacích prvků na snímku.<br/>            Pouze pro čtení [`IControlCollection`](/slides/python-net/cs/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/cs/aspose.slides/baseslide/name/) | Vrací nebo nastavuje název snímku.<br/>            Čtení/zápis **str**. |
| [`slide_id`](/slides/python-net/cs/aspose.slides/baseslide/slide_id/) | Vrací ID snímku.<br/>            Pouze pro čtení **int**. |
| [`custom_data`](/slides/python-net/cs/aspose.slides/baseslide/custom_data/) | Vrací vlastní data snímku.<br/>            Pouze pro čtení [`ICustomData`](/slides/python-net/cs/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/cs/aspose.slides/baseslide/timeline/) | Vrací objekt časové osy animace.<br/>            Pouze pro čtení [`IAnimationTimeLine`](/slides/python-net/cs/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/cs/aspose.slides/baseslide/slide_show_transition/) | Vrací objekt Transition, který obsahuje informace o<br/>            tom, jak se určený snímek během prezentace posouvá.<br/>            Pouze pro čtení [`ISlideShowTransition`](/slides/python-net/cs/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/cs/aspose.slides/baseslide/background/) | Vrací pozadí snímku.<br/>            Pouze pro čtení [`IBackground`](/slides/python-net/cs/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/cs/aspose.slides/baseslide/hyperlink_queries/) | Poskytuje snadný přístup k obsaženým hypertextovým odkazům.<br/>            Pouze pro čtení [`IHyperlinkQueries`](/slides/python-net/cs/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/cs/aspose.slides/baseslide/show_master_shapes/) | Určuje, zda se tvary na hlavním snímku mají zobrazovat na snímcích nebo ne.<br/>            Pro samotný hlavní snímek tato vlastnost vždy vrací `false`.<br/>            Čtení/zápis **bool**. |
| [`presentation`](/slides/python-net/cs/aspose.slides/baseslide/presentation/) | Vrací rozhraní IPresentation.<br/>            Pouze pro čtení [`IPresentation`](/slides/python-net/cs/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/cs/aspose.slides/baseslide/slide/) |  |

## Metody

| Metoda | Popis |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/cs/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Spojuje úseky se stejným formátováním ve všech odstavcích všech přijatelných tvarů. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/cs/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Spojuje úseky se stejným formátováním ve všech odstavcích ve všech přijatelných tvarech. |
| [`equals(self, slide)`](/slides/python-net/cs/aspose.slides/baseslide/equals/#ibaseslide) | Určuje, zda jsou dvě instance IBaseSlide rovny.<br/>            Návratová hodnota je vypočítána na základě struktury snímku a statického obsahu.<br/>            Dva snímky jsou rovny, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. rovny. Porovnání nebere v úvahu jedinečné identifikátory, například SlideId, a dynamický obsah, například aktuální datum v zástupci Data. |
| [`create_theme_effective(self)`](/slides/python-net/cs/aspose.slides/baseslide/create_theme_effective/#) | Vrací efektivní téma pro tento snímek. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/cs/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Najde první výskyt tvaru s určeným alternativním textem. |


### Viz také
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)