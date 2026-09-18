---
title: MasterHandoutSlide class
second_title: Aspose.Slides dla Pythona via .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/masterhandoutslide/
---
## MasterHandoutSlide klasa

Reprezentuje slajd główny dla notatek.

**Inheritance:**[`MasterHandoutSlide`](/slides/python-net/pl/aspose.slides/masterhandoutslide) → [`BaseSlide`](/slides/python-net/pl/aspose.slides/baseslide)

Typ MasterHandoutSlide udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`shapes`](/slides/python-net/pl/aspose.slides/masterhandoutslide/shapes/) | Zwraca kształty slajdu.<br/>            Tylko do odczytu [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pl/aspose.slides/masterhandoutslide/controls/) | Zwraca kolekcję kontrolerów ActiveX na slajdzie.<br/>            Tylko do odczytu [`IControlCollection`](/slides/python-net/pl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pl/aspose.slides/masterhandoutslide/name/) | Zwraca lub ustawia nazwę slajdu.<br/>            Odczyt/zapis **str**. |
| [`slide_id`](/slides/python-net/pl/aspose.slides/masterhandoutslide/slide_id/) | Zwraca identyfikator (ID) slajdu.<br/>            Tylko do odczytu **int**. |
| [`custom_data`](/slides/python-net/pl/aspose.slides/masterhandoutslide/custom_data/) | Zwraca własne dane slajdu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pl/aspose.slides/masterhandoutslide/timeline/) | Zwraca obiekt linii czasu animacji.<br/>            Tylko do odczytu [`IAnimationTimeLine`](/slides/python-net/pl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pl/aspose.slides/masterhandoutslide/slide_show_transition/) | Zwraca obiekt Transition, który zawiera informacje o<br/>            tym, jak dany slajd przechodzi podczas pokazu slajdów.<br/>            Tylko do odczytu [`ISlideShowTransition`](/slides/python-net/pl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pl/aspose.slides/masterhandoutslide/background/) | Zwraca tło slajdu.<br/>            Tylko do odczytu [`IBackground`](/slides/python-net/pl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/masterhandoutslide/hyperlink_queries/) | Zapewnia łatwy dostęp do zawartych hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkQueries`](/slides/python-net/pl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pl/aspose.slides/masterhandoutslide/show_master_shapes/) | Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie.<br/>            Dla samego slajdu głównego ta właściwość zawsze zwraca `false`.<br/>            Odczyt/zapis **bool**. |
| [`presentation`](/slides/python-net/pl/aspose.slides/masterhandoutslide/presentation/) | Zwraca interfejs IPresentation.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/pl/aspose.slides/masterhandoutslide/header_footer_manager/) | Zwraca menedżera HeaderFooter slajdu głównego notatek.<br/>            Tylko do odczytu [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/pl/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/pl/aspose.slides/masterhandoutslide/theme_manager/) | Zwraca menedżera motywu.<br/>            Tylko do odczytu [`IMasterThemeManager`](/slides/python-net/pl/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/pl/aspose.slides/masterhandoutslide/drawing_guides/) | Zwraca kolekcję przewodników rysowania dla slajdu głównego notatek.<br/>            Tylko do odczytu [`IDrawingGuidesCollection`](/slides/python-net/pl/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/pl/aspose.slides/masterhandoutslide/slide/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#) | Łączy segmenty tekstu (runy) o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pl/aspose.slides/masterhandoutslide/join_portions_with_same_formatting/#ishapecollection) | Łączy segmenty tekstu o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [`equals(self, slide)`](/slides/python-net/pl/aspose.slides/masterhandoutslide/equals/#ibaseslide) | Określa, czy dwie instancje IBaseSlide są równe.<br/>            Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości.<br/>            Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są identyczne. Porównanie nie uwzględnia unikalnych wartości identyfikatorów, np. SlideId oraz zawartości dynamicznej, np. bieżącej wartości daty w Symbolu daty. |
| [`create_theme_effective(self)`](/slides/python-net/pl/aspose.slides/masterhandoutslide/create_theme_effective/#) | Zwraca efektywny motyw dla tego slajdu. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pl/aspose.slides/masterhandoutslide/find_shape_by_alt_text/#str) | Znajduje pierwsze wystąpienie kształtu z określonym tekstem alternatywnym. |

### Zobacz także
* klasa [`BaseSlide`](/slides/python-net/pl/aspose.slides/baseslide)
* klasa [`MasterHandoutSlide`](/slides/python-net/pl/aspose.slides/masterhandoutslide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)