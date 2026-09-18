---
title: NotesSlide class
second_title: Aspose.Slides dla Pythona przez .NET – dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/notesslide/
---
## NotesSlide klasa

Reprezentuje slajd notatek w prezentacji.

**Dziedziczenie:**[`NotesSlide`](/slides/python-net/pl/aspose.slides/notesslide) → [`BaseSlide`](/slides/python-net/pl/aspose.slides/baseslide)

Typ NotesSlide udostępnia następujące elementy:

## Właściwości

| Właściwość | Opis |
| :- | :- |
| [`shapes`](/slides/python-net/pl/aspose.slides/notesslide/shapes/) | Zwraca kształty slajdu.<br/>            Tylko do odczytu [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pl/aspose.slides/notesslide/controls/) | Zwraca kolekcję kontroli ActiveX na slajdzie.<br/>            Tylko do odczytu [`IControlCollection`](/slides/python-net/pl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pl/aspose.slides/notesslide/name/) | Zwraca lub ustawia nazwę slajdu.<br/>            Odczyt/zapis **str**. |
| [`slide_id`](/slides/python-net/pl/aspose.slides/notesslide/slide_id/) | Zwraca identyfikator slajdu.<br/>            Tylko do odczytu **int**. |
| [`custom_data`](/slides/python-net/pl/aspose.slides/notesslide/custom_data/) | Zwraca niestandardowe dane slajdu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pl/aspose.slides/notesslide/timeline/) | Zwraca obiekt osi czasu animacji.<br/>            Tylko do odczytu [`IAnimationTimeLine`](/slides/python-net/pl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pl/aspose.slides/notesslide/slide_show_transition/) | Zwraca obiekt Transition zawierający informacje o<br/>            tym, jak określony slajd przechodzi podczas pokazu slajdów.<br/>            Tylko do odczytu [`ISlideShowTransition`](/slides/python-net/pl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pl/aspose.slides/notesslide/background/) | Zwraca tło slajdu.<br/>            Tylko do odczytu [`IBackground`](/slides/python-net/pl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/notesslide/hyperlink_queries/) | Zapewnia łatwy dostęp do zawartych hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkQueries`](/slides/python-net/pl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pl/aspose.slides/notesslide/show_master_shapes/) | Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie.<br/>            Odczyt/zapis **bool**. |
| [`presentation`](/slides/python-net/pl/aspose.slides/notesslide/presentation/) | Zwraca interfejs IPresentation.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`header_footer_manager`](/slides/python-net/pl/aspose.slides/notesslide/header_footer_manager/) | Zwraca menedżera HeaderFooter slajdu notatek.<br/>            Tylko do odczytu [`INotesSlideHeaderFooterManager`](/slides/python-net/pl/aspose.slides/inotesslideheaderfootermanager). |
| [`notes_text_frame`](/slides/python-net/pl/aspose.slides/notesslide/notes_text_frame/) | Zwraca TextFrame z tekstem notatek, jeśli istnieje.<br/>            Tylko do odczytu [`ITextFrame`](/slides/python-net/pl/aspose.slides/itextframe). |
| [`theme_manager`](/slides/python-net/pl/aspose.slides/notesslide/theme_manager/) | Zwraca menedżera nadpisującego tematu.<br/>            Tylko do odczytu [`IOverrideThemeManager`](/slides/python-net/pl/aspose.slides.theme/ioverridethememanager). |
| [`parent_slide`](/slides/python-net/pl/aspose.slides/notesslide/parent_slide/) | Zwraca slajd nadrzędny.<br/>            Tylko do odczytu [`ISlide`](/slides/python-net/pl/aspose.slides/islide). |
| [`slide`](/slides/python-net/pl/aspose.slides/notesslide/slide/) |  |

## Metody

| Metoda | Opis |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/notesslide/join_portions_with_same_formatting/#) | Łączy ciągi o tym samym formatowaniu we wszystkich akapitach wszystkich dopuszczalnych kształtów. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pl/aspose.slides/notesslide/join_portions_with_same_formatting/#ishapecollection) | Łączy ciągi o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [`equals(self, slide)`](/slides/python-net/pl/aspose.slides/notesslide/equals/#ibaseslide) | Określa, czy dwa wystąpienia IBaseSlide są równe.<br/>            Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości.<br/>            Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itd. są równe. Porównanie nie uwzględnia unikalnych wartości identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. aktualnej wartości daty w zastępniku daty. |
| [`create_theme_effective(self)`](/slides/python-net/pl/aspose.slides/notesslide/create_theme_effective/#) | Zwraca efektywny motyw dla tego slajdu. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pl/aspose.slides/notesslide/find_shape_by_alt_text/#str) | Znajduje pierwsze wystąpienie kształtu z określonym tekstem alternatywnym. |

### Zobacz też
* klasa [`BaseSlide`](/slides/python-net/pl/aspose.slides/baseslide)
* klasa [`NotesSlide`](/slides/python-net/pl/aspose.slides/notesslide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)