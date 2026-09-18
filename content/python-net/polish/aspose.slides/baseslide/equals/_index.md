---
title: equals method
second_title: Aspose.Slides dla Pythona przez .NET - Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/baseslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Określa, czy dwie instancje IBaseSlide są równe.
            Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości.
            Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itd. są równe. Porównanie nie bierze pod uwagę unikalnych wartości identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. bieżącej wartości daty w polu zastępczym daty.

### Zwraca

**true**  jeśli określony IBaseSlide jest równy bieżącemu IBaseSlide; 
            w przeciwnym razie, **false** .

```python
def equals(self, slide):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide) | IBaseSlide do porównania z bieżącym IBaseSlide. |

### Zobacz także
* klasa [`BaseSlide`](/slides/python-net/pl/aspose.slides/baseslide)
* klasa [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)