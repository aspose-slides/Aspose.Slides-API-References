---
title: BaseSlide class
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides/baseslide/
---
## BaseSlide klasa

Represents common data for all slide types.

The BaseSlide type exposes the following members:

## Właściwości

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/pl/aspose.slides/baseslide/shapes/) | Zwraca kształty slajdu.<br/>            Tylko do odczytu [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pl/aspose.slides/baseslide/controls/) | Zwraca kolekcję kontrolek ActiveX na slajdzie.<br/>            Tylko do odczytu [`IControlCollection`](/slides/python-net/pl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pl/aspose.slides/baseslide/name/) | Zwraca lub ustawia nazwę slajdu.<br/>            Odczyt/zapis **str**. |
| [`slide_id`](/slides/python-net/pl/aspose.slides/baseslide/slide_id/) | Zwraca identyfikator slajdu.<br/>            Tylko do odczytu **int**. |
| [`custom_data`](/slides/python-net/pl/aspose.slides/baseslide/custom_data/) | Zwraca niestandardowe dane slajdu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pl/aspose.slides/baseslide/timeline/) | Zwraca obiekt osi czasu animacji.<br/>            Tylko do odczytu [`IAnimationTimeLine`](/slides/python-net/pl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pl/aspose.slides/baseslide/slide_show_transition/) | Zwraca obiekt Transition zawierający informacje o<br/>            tym, jak określony slajd przechodzi w trakcie pokazu slajdów.<br/>            Tylko do odczytu [`ISlideShowTransition`](/slides/python-net/pl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pl/aspose.slides/baseslide/background/) | Zwraca tło slajdu.<br/>            Tylko do odczytu [`IBackground`](/slides/python-net/pl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/baseslide/hyperlink_queries/) | Zapewnia łatwy dostęp do zawartych hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkQueries`](/slides/python-net/pl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pl/aspose.slides/baseslide/show_master_shapes/) | Określa, czy kształty na slajdzie głównym mają być wyświetlane na slajdach, czy nie.<br/>            Dla samego slajdu głównego ta właściwość zawsze zwraca `false`.<br/>            Odczyt/zapis **bool**. |
| [`presentation`](/slides/python-net/pl/aspose.slides/baseslide/presentation/) | Zwraca interfejs IPresentation.<br/>            Tylko do odczytu [`IPresentation`](/slides/python-net/pl/aspose.slides/ipresentation). |
| [`slide`](/slides/python-net/pl/aspose.slides/baseslide/slide/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/baseslide/join_portions_with_same_formatting/#) | Łączy ciągi tekstowe o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [`join_portions_with_same_formatting(self, collection)`](/slides/python-net/pl/aspose.slides/baseslide/join_portions_with_same_formatting/#ishapecollection) | Łączy ciągi tekstowe o tym samym formatowaniu we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [`equals(self, slide)`](/slides/python-net/pl/aspose.slides/baseslide/equals/#ibaseslide) | Określa, czy dwie instancje IBaseSlide są równe.<br/>            Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości.<br/>            Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są równe. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz treści dynamicznej, np. bieżącej wartości daty w symbolu zastępczym Daty. |
| [`create_theme_effective(self)`](/slides/python-net/pl/aspose.slides/baseslide/create_theme_effective/#) | Zwraca efektywny motyw dla tego slajdu. |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pl/aspose.slides/baseslide/find_shape_by_alt_text/#str) | Znajduje pierwsze wystąpienie kształtu z określonym tekstem alternatywnym. |


### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)