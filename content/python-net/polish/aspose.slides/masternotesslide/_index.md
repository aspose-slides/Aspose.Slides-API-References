---
title: MasterNotesSlide class
second_title: Aspose.Slides dla Pythona poprzez .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/masternotesslide/
---
## MasterNotesSlide klasa

Reprezentuje slajd nadrzędny dla notatek.

**Dziedziczenie:**[`MasterNotesSlide`](/slides/python-net/pl/aspose.slides/masternotesslide) → [`BaseSlide`](/slides/python-net/pl/aspose.slides/baseslide)

Typ MasterNotesSlide udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`shapes`](/slides/python-net/pl/aspose.slides/masternotesslide/shapes/) | Zwraca kształty slajdu.<br/>            tylko do odczytu [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pl/aspose.slides/masternotesslide/controls/) | Zwraca kolekcję kontrolek ActiveX na slajdzie.<br/>            tylko do odczytu [`IControlCollection`](/slides/python-net/pl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pl/aspose.slides/masternotesslide/name/) | Zwraca lub ustawia nazwę slajdu.<br/>            odczyt/zapis **str**. |
| [`slide_id`](/slides/python-net/pl/aspose.slides/masternotesslide/slide_id/) | Zwraca identyfikator slajdu.<br/>            tylko do odczytu **int**. |
| [`custom_data`](/slides/python-net/pl/aspose.slides/masternotesslide/custom_data/) | Zwraca niestandardowe dane slajdu.<br/>            tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pl/aspose.slides/masternotesslide/timeline/) | Zwraca obiekt osi czasu animacji.<br/>            tylko do odczytu [`IAnimationTimeLine`](/slides/python-net/pl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pl/aspose.slides/masternotesslide/slide_show_transition/) | Zwraca obiekt Transition, który zawiera informacje o<br/>            tym, jak określony slajd przechodzi w trakcie pokazu slajdów.<br/>            tylko do odczytu [`ISlideShowTransition`](/slides/python-net/pl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pl/aspose.slides/masternotesslide/background/) | Zwraca tło slajdu.<br/>            tylko do odczytu [`IBackground`](/slides/python-net/pl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/masternotesslide/hyperlink_queries/) | Zapewnia łatwy dostęp do zawartych hiperłączy.<br/>            tylko do odczytu [`IHyperlinkQueries`](/slides/python-net/pl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pl/aspose.slides/masternotesslide/show_master_shapes/) | Określa, czy kształty na slajdzie nadrzędnym powinny być wyświetlane na slajdach, czy nie.<br/>            Dla samego slajdu nadrzędnego ta właściwość zawsze zwraca `false`.<br/>            odczyt/zapis **bool**. |
| [`presentation`](/slides/python-net/pl/aspose.slides/masternotesslide/presentation/) | Zwraca interfejs IPresentation.<br/>            tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/pl/aspose.slides/masternotesslide/header_footer_manager/) | Zwraca menedżer HeaderFooter slajdu notatek nadrzędnych.<br/>            tylko do odczytu [`IMasterHandoutSlideHeaderFooterManager`](/slides/python-net/pl/aspose.slides/imasterhandoutslideheaderfootermanager). |
| [`theme_manager`](/slides/python-net/pl/aspose.slides/masternotesslide/theme_manager/) | Zwraca menedżer motywu.<br/>            tylko do odczytu [`IMasterThemeManager`](/slides/python-net/pl/aspose.slides.theme/imasterthememanager). |
| [`notes_style`](/slides/python-net/pl/aspose.slides/masternotesslide/notes_style/) | Zwraca styl tekstu notatek.<br/>            tylko do odczytu [`ITextStyle`](/slides/python-net/pl/aspose.slides/itextstyle). |
| [`drawing_guides`](/slides/python-net/pl/aspose.slides/masternotesslide/drawing_guides/) | Zwraca kolekcję przewodników rysowania dla slajdu notatek nadrzędnych.<br/>            tylko do odczytu [`IDrawingGuidesCollection`](/slides/python-net/pl/aspose.slides/idrawingguidescollection) |
| [`slide`](/slides/python-net/pl/aspose.slides/masternotesslide/slide/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/masternotesslide/join_portions_with_same_formatting/#) | Łączy ciągi znaków o tym samym formatowaniu we wszystkich akapitach wszystkich dopuszczalnych kształtów. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pl/aspose.slides/masternotesslide/join_portions_with_same_formatting/#ishapecollection) | Łączy ciągi znaków o tym samym formatowaniu we wszystkich akapitach wszystkich dopuszczalnych kształtów. |
| [`equals(self, slide)`](/slides/python-net/pl/aspose.slides/masternotesslide/equals/#ibaseslide) | Określa, czy dwa obiekty typu IBaseSlide są równe.<br/>            Wartość zwracana jest obliczana na podstawie struktury slajdu i statycznej zawartości.<br/>            Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są równe. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. aktualnej wartości daty w Placeholderze daty. |
| [`create_theme_effective(self)`](/slides/python-net/pl/aspose.slides/masternotesslide/create_theme_effective/#) | Zwraca skuteczny motyw dla tego slajdu. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pl/aspose.slides/masternotesslide/find_shape_by_alt_text/#str) | Znajduje pierwsze wystąpienie kształtu o określonym alternatywnym tekście. |

### Zobacz także
* klasa [`BaseSlide`](/slides/python-net/pl/aspose.slides/baseslide)
* klasa [`MasterNotesSlide`](/slides/python-net/pl/aspose.slides/masternotesslide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)