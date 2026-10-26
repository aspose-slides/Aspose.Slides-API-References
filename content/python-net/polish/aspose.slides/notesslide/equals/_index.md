---
title: equals method
second_title: Aspose.Slides dla Pythona poprzez .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/notesslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Określa, czy dwie instancje IBaseSlide są równe.
            Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości.
            Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia, itp., są równe. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz treści dynamicznej, np. bieżącej wartości daty w Date Placeholder.

### Zwraca

**true**  jeśli określony IBaseSlide jest równy bieżącemu IBaseSlide; 
            w przeciwnym razie **false** .


```python
def equals(self, slide):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide) | IBaseSlide do porównania z bieżącym IBaseSlide. |


### Zobacz także
* klasa [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide)
* klasa [`NotesSlide`](/slides/python-net/pl/aspose.slides/notesslide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)