---
title: IBaseSlide class
second_title: Aspose.Slides dla Pythona przez .NET referencja API
description: 
type: docs
url: /pl/aspose.slides/ibaseslide/
---
## IBaseSlide klasa

Represents common data for all slide types.

The IBaseSlide type exposes the following members:

## Właściwości

| Property | Description |
| :- | :- |
| [`shapes`](/slides/python-net/pl/aspose.slides/ibaseslide/shapes/) | Zwraca kształty slajdu.<br/>            Tylko do odczytu [`IShapeCollection`](/slides/python-net/pl/aspose.slides/ishapecollection). |
| [`controls`](/slides/python-net/pl/aspose.slides/ibaseslide/controls/) | Zwraca kolekcję kontrolek ActiveX na slajdzie.<br/>            Tylko do odczytu [`IControlCollection`](/slides/python-net/pl/aspose.slides/icontrolcollection). |
| [`name`](/slides/python-net/pl/aspose.slides/ibaseslide/name/) | Zwraca lub ustawia nazwę slajdu.<br/>            Odczyt/zapis **str**. |
| [`slide_id`](/slides/python-net/pl/aspose.slides/ibaseslide/slide_id/) | Zwraca identyfikator slajdu.<br/>            Tylko do odczytu **int**. |
| [`custom_data`](/slides/python-net/pl/aspose.slides/ibaseslide/custom_data/) | Zwraca niestandardowe dane slajdu.<br/>            Tylko do odczytu [`ICustomData`](/slides/python-net/pl/aspose.slides/icustomdata). |
| [`timeline`](/slides/python-net/pl/aspose.slides/ibaseslide/timeline/) | Zwraca obiekt osi czasu animacji.<br/>            Tylko do odczytu [`IAnimationTimeLine`](/slides/python-net/pl/aspose.slides/ianimationtimeline). |
| [`slide_show_transition`](/slides/python-net/pl/aspose.slides/ibaseslide/slide_show_transition/) | Zwraca obiekt TransitionEx, który zawiera informacje o<br/>            jak określony slajd przechodzi podczas pokazu slajdów.<br/>            Tylko do odczytu [`ISlideShowTransition`](/slides/python-net/pl/aspose.slides/islideshowtransition). |
| [`background`](/slides/python-net/pl/aspose.slides/ibaseslide/background/) | Zwraca tło slajdu.<br/>            Tylko do odczytu [`IBackground`](/slides/python-net/pl/aspose.slides/ibackground). |
| [`hyperlink_queries`](/slides/python-net/pl/aspose.slides/ibaseslide/hyperlink_queries/) | Zapewnia łatwy dostęp do zawartych hiperłączy.<br/>            Tylko do odczytu [`IHyperlinkQueries`](/slides/python-net/pl/aspose.slides/ihyperlinkqueries). |
| [`show_master_shapes`](/slides/python-net/pl/aspose.slides/ibaseslide/show_master_shapes/) | Określa, czy kształty na slajdzie wzorcowym powinny być wyświetlane na slajdach, czy nie.<br/>            Dla samego slajdu wzorcowego ta właściwość zawsze zwraca `false`.<br/>            Odczyt/zapis **bool**. |
| [`slide`](/slides/python-net/pl/aspose.slides/ibaseslide/slide/) |  |
| [`presentation`](/slides/python-net/pl/aspose.slides/ibaseslide/presentation/) |  |

## Metody

| Method | Description |
| :- | :- |
| [`find_shape_by_alt_text(self, alt_text)`](/slides/python-net/pl/aspose.slides/ibaseslide/find_shape_by_alt_text/#str) | Znajduje pierwsze wystąpienie kształtu o określonym alternatywnym tekście. |
| [`join_portions_with_same_formatting(self)`](/slides/python-net/pl/aspose.slides/ibaseslide/join_portions_with_same_formatting/#) | Łączy ciągi z tym samym formatowaniem we wszystkich akapitach we wszystkich dopuszczalnych kształtach. |
| [`equals(self, slide)`](/slides/python-net/pl/aspose.slides/ibaseslide/equals/#ibaseslide) | Określa, czy dwa obiekty IBaseSlide są równe.<br/>            Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości.<br/>            Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia, itp. są równe. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz treści dynamicznej, np. bieżącej wartości daty w symbolu zastępczym Daty. |
| [`create_theme_effective(self)`](/slides/python-net/pl/aspose.slides/ibaseslide/create_theme_effective/#) |  |

### Zobacz także
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)