---
title: MasterSlide class
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/masterslide/
---
## Klasa MasterSlide

Reprezentuje slajd master w prezentacji.

**Inheritance:**[`MasterSlide`](/slides/python-net/pl/aspose.slides/masterslide) → [`BaseSlide`](/slides/python-net/pl/aspose.slides/baseslide)

Typ MasterSlide udostępnia następujące członki:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`shapes`](/slides/python-net/pl/aspose.slides/masterslide/shapes/) | Zwraca kształty slajdu.<br/>            Tylko do odczytu [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pl/aspose.slides/masterslide/controls/) | Zwraca kolekcję kontrolek ActiveX na slajdzie.<br/>            Tylko do odczytu [`IControlCollection`](/slides/python-net/pl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pl/aspose.slides/masterslide/name/) | Zwraca lub ustawia nazwę slajdu master.<br/>            Odczyt/zapis **str**. |
| [`slide_id`](/slides/python-net/pl/aspose.slides/masterslide/slide_id/) | Zwraca identyfikator slajdu.<br/>            Tylko do odczytu **int**. |
| [`custom_data`](/slides/python-net/pl/aspose.slides/masterslide/custom_data/) | Zwraca dane własne slajdu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pl/aspose.slides/masterslide/timeline/) | Zwraca obiekt osi czasu animacji.<br/>            Tylko do odczytu [`IAnimationTimeLine`](/slides/python-net/pl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pl/aspose.slides/masterslide/slide_show_transition/) | Zwraca obiekt Transition, który zawiera informacje o<br/>            tym, jak określony slajd przechodzi podczas pokazu.<br/>            Tylko do odczytu [`ISlideShowTransition`](/slides/python-net/pl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pl/aspose.slides/masterslide/background/) | Zwraca tło slajdu.<br/>            Tylko do odczytu [`IBackground`](/slides/python-net/pl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/masterslide/hyperlink_queries/) | Umożliwia łatwy dostęp do zawartych hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkQueries`](/slides/python-net/pl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pl/aspose.slides/masterslide/show_master_shapes/) | Określa, czy kształty na slajdzie master powinny być wyświetlane na slajdach.<br/>            Dla samego slajdu master ta właściwość zawsze zwraca `false`.<br/>            Odczyt/zapis **bool**. |
| [`presentation`](/slides/python-net/pl/aspose.slides/masterslide/presentation/) | Zwraca interfejs IPresentation.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/pl/aspose.slides/masterslide/header_footer_manager/) | Zwraca menedżer HeaderFooter slajdu master.<br/>            Tylko do odczytu [`IMasterSlideHeaderFooterManager`](/slides/python-net/pl/aspose.slides/imasterslideheaderfootermanager). |
| [`title_style`](/slides/python-net/pl/aspose.slides/masterslide/title_style/) | Zwraca styl tekstu tytułowego.<br/>            Tylko do odczytu [`ITextStyle`](/slides/python-net/pl/aspose.slides/itextstyle). |
| [`body_style`](/slides/python-net/pl/aspose.slides/masterslide/body_style/) | Zwraca styl tekstu głównego.<br/>            Tylko do odczytu [`ITextStyle`](/slides/python-net/pl/aspose.slides/itextstyle). |
| [`other_style`](/slides/python-net/pl/aspose.slides/masterslide/other_style/) | Zwraca styl innego tekstu.<br/>            Tylko do odczytu [`ITextStyle`](/slides/python-net/pl/aspose.slides/itextstyle). |
| [`layout_slides`](/slides/python-net/pl/aspose.slides/masterslide/layout_slides/) | Zwraca kolekcję podrzędnych slajdów układu dla tego slajdu master.<br/>            Tylko do odczytu [`IMasterLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/imasterlayoutslidecollection). |
| [`preserve`](/slides/python-net/pl/aspose.slides/masterslide/preserve/) | Określa, czy odpowiadający master zostanie usunięty, gdy wszystkie slajdy wykorzystujące ten master zostaną usunięte.<br/>            Uwaga: Aspose.Slides nigdy nie usunie żadnego nieużywanego mastera samodzielnie, aby faktycznie usunąć nieużywane mastery, wywołaj **Aspose.Slides.MasterSlideCollection.RemoveUnused(Syste**<br/>            Odczyt/zapis **bool**. |
| [`has_depending_slides`](/slides/python-net/pl/aspose.slides/masterslide/has_depending_slides/) | Zwraca wartość true, jeśli istnieje przynajmniej jeden slajd zależny od tego slajdu master.<br/>            Tylko do odczytu **bool**. |
| [`theme_manager`](/slides/python-net/pl/aspose.slides/masterslide/theme_manager/) | Zwraca menedżer motywu.<br/>            Tylko do odczytu [`IMasterThemeManager`](/slides/python-net/pl/aspose.slides.theme/imasterthememanager). |
| [`drawing_guides`](/slides/python-net/pl/aspose.slides/masterslide/drawing_guides/) | Zwraca kolekcję prowadnic rysunkowych dla slajdu master.<br/>            Tylko do odczytu [`IDrawingGuidesCollection`](/slides/python-net/pl/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/pl/aspose.slides/masterslide/slide/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/masterslide/join_portions_with_same_formatting/#) | Łączy runy o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pl/aspose.slides/masterslide/join_portions_with_same_formatting/#ishapecollection) | Łączy runy o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [`equals(self, slide)`](/slides/python-net/pl/aspose.slides/masterslide/equals/#ibaseslide) | Określa, czy dwie instancje IBaseSlide są równe.<br/>            Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości.<br/>            Dwie prezentacje są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są identyczne. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. bieżącej wartości daty w polu zastępczym Date Placeholder. |
| [`create_theme_effective(self)`](/slides/python-net/pl/aspose.slides/masterslide/create_theme_effective/#) | Zwraca efektywny motyw dla tego slajdu. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pl/aspose.slides/masterslide/find_shape_by_alt_text/#str) | Znajduje pierwsze wystąpienie kształtu o określonym alternatywnym tekście. |
| [`apply_external_theme_to_depending_slides(self, fname)`](/slides/python-net/pl/aspose.slides/masterslide/apply_external_theme_to_depending_slides/#str) | Tworzy nowy slajd master na podstawie bieżącego, stosując do niego zewnętrzny motyw <br/>            i aplikuje utworzony slajd master do wszystkich zależnych slajdów. |
| [`get_depending_slides(self)`](/slides/python-net/pl/aspose.slides/masterslide/get_depending_slides/#) | Zwraca tablicę wszystkich slajdów, które zależą od tego slajdu master. |

### Zobacz także
* klasa [`BaseSlide`](/slides/python-net/pl/aspose.slides/baseslide)
* klasa [`MasterSlide`](/slides/python-net/pl/aspose.slides/masterslide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)