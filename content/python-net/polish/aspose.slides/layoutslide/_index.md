---
title: LayoutSlide class
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/layoutslide/
---
## LayoutSlide klasa

Reprezentuje slajd układu.

**Dziedziczenie:**[`LayoutSlide`](/slides/python-net/pl/aspose.slides/layoutslide) → [`BaseSlide`](/slides/python-net/pl/aspose.slides/baseslide)

Typ LayoutSlide udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`shapes`](/slides/python-net/pl/aspose.slides/layoutslide/shapes/) | Zwraca kształty slajdu.<br/>            Tylko do odczytu [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pl/aspose.slides/layoutslide/controls/) | Zwraca kolekcję kontrolek ActiveX na slajdzie.<br/>            Tylko do odczytu [`IControlCollection`](/slides/python-net/pl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pl/aspose.slides/layoutslide/name/) | Zwraca lub ustawia nazwę slajdu.<br/>            Odczyt/zapis **str**. |
| [`slide_id`](/slides/python-net/pl/aspose.slides/layoutslide/slide_id/) | Zwraca identyfikator slajdu.<br/>            Tylko do odczytu **int**. |
| [`custom_data`](/slides/python-net/pl/aspose.slides/layoutslide/custom_data/) | Zwraca niestandardowe dane slajdu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pl/aspose.slides/layoutslide/timeline/) | Zwraca obiekt osi czasu animacji.<br/>            Tylko do odczytu [`IAnimationTimeLine`](/slides/python-net/pl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pl/aspose.slides/layoutslide/slide_show_transition/) | Zwraca obiekt Transition, który zawiera informacje o<br/>            tym, jak określony slajd przechodzi podczas pokazu slajdów.<br/>            Tylko do odczytu [`ISlideShowTransition`](/slides/python-net/pl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pl/aspose.slides/layoutslide/background/) | Zwraca tło slajdu.<br/>            Tylko do odczytu [`IBackground`](/slides/python-net/pl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/layoutslide/hyperlink_queries/) | Umożliwia łatwy dostęp do zawartych hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkQueries`](/slides/python-net/pl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pl/aspose.slides/layoutslide/show_master_shapes/) | Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie.<br/>            Odczyt/zapis **bool**. |
| [`presentation`](/slides/python-net/pl/aspose.slides/layoutslide/presentation/) | Zwraca interfejs IPresentation.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/pl/aspose.slides/layoutslide/header_footer_manager/) | Zwraca menedżera HeaderFooter układu slajdu.<br/>            Tylko do odczytu [`ILayoutSlideHeaderFooterManager`](/slides/python-net/pl/aspose.slides/ilayoutslideheaderfootermanager). |
| [`placeholder_manager`](/slides/python-net/pl/aspose.slides/layoutslide/placeholder_manager/) | Zwraca menedżera placeholderów układu slajdu.<br/>            Tylko do odczytu [`ILayoutPlaceholderManager`](/slides/python-net/pl/aspose.slides/ilayoutplaceholdermanager). |
| [`master_slide`](/slides/python-net/pl/aspose.slides/layoutslide/master_slide/) | Zwraca lub ustawia slajd główny dla układu.<br/>            Odczyt/zapis [`IMasterSlide`](/slides/python-net/pl/aspose.slides/imasterslide). |
| [`theme_manager`](/slides/python-net/pl/aspose.slides/layoutslide/theme_manager/) | Zwraca menedżera nadpisującego motywu.<br/>            Tylko do odczytu [`IOverrideThemeManager`](/slides/python-net/pl/aspose.slides.theme/ioverridethememanager). |
| [`layout_type`](/slides/python-net/pl/aspose.slides/layoutslide/layout_type/) | Zwraca typ układu tego slajdu układu.<br/>            Tylko do odczytu [`SlideLayoutType`](/slides/python-net/pl/aspose.slides/slidelayouttype). |
| [`has_depending_slides`](/slides/python-net/pl/aspose.slides/layoutslide/has_depending_slides/) | Zwraca true, jeśli istnieje przynajmniej jeden slajd zależny od tego slajdu układu.<br/>            Tylko do odczytu **bool**. |
| [`drawing_guides`](/slides/python-net/pl/aspose.slides/layoutslide/drawing_guides/) | Zwraca kolekcję przewodników rysowania dla slajdu układu.<br/>            Tylko do odczytu [`IDrawingGuidesCollection`](/slides/python-net/pl/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/pl/aspose.slides/layoutslide/slide/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/layoutslide/join_portions_with_same_formatting/#) | Łączy runy o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pl/aspose.slides/layoutslide/join_portions_with_same_formatting/#ishapecollection) | Łączy runy o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [`equals(self, slide)`](/slides/python-net/pl/aspose.slides/layoutslide/equals/#ibaseslide) | Określa, czy dwa egzemplarze IBaseSlide są równe.<br/>            Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości.<br/>            Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są równe. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz zawartości dynamicznej, np. bieżącej wartości daty w Placeholderze daty. |
| [`create_theme_effective(self)`](/slides/python-net/pl/aspose.slides/layoutslide/create_theme_effective/#) | Zwraca efektywny motyw dla tego slajdu. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pl/aspose.slides/layoutslide/find_shape_by_alt_text/#str) | Znajduje pierwsze wystąpienie kształtu z określonym tekstem alternatywnym. |
| [`remove(self)`](/slides/python-net/pl/aspose.slides/layoutslide/remove/#) | Usuwa układ z prezentacji. |
| [`get_depending_slides(self)`](/slides/python-net/pl/aspose.slides/layoutslide/get_depending_slides/#) | Zwraca tablicę ze wszystkimi slajdami, które zależą od tego slajdu układu. |


### Zobacz także
* klasa [`BaseSlide`](/slides/python-net/pl/aspose.slides/baseslide)
* klasa [`LayoutSlide`](/slides/python-net/pl/aspose.slides/layoutslide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)