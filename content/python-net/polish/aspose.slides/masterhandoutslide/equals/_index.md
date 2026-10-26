---
title: equals method
second_title: Aspose.Slides dla Pythona za pośrednictwem .NET API Reference
description: 
type: docs
url: /pl/aspose.slides/masterhandoutslide/equals/
weight: 20
---
## equals(self, slide) {#ibaseslide}
Określa, czy dwa wystąpienia klasy IBaseSlide są równe.  
Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości.  
Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itd. są równe. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId i zawartości dynamicznej, np. bieżącej wartości daty w Date Placeholder.

### Returns

**true**  jeśli określony IBaseSlide jest równy bieżącemu IBaseSlide; w przeciwnym razie **false** .

```python
def equals(self, slide):
    ...
```

| Parametr | Typ | Opis |
| :- | :- | :- |
| slide | [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide) | The IBaseSlide do porównania z bieżącym IBaseSlide. |

### See Also
* klasa [`IBaseSlide`](/slides/python-net/pl/aspose.slides/ibaseslide)
* klasa [`MasterHandoutSlide`](/slides/python-net/pl/aspose.slides/masterhandoutslide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)