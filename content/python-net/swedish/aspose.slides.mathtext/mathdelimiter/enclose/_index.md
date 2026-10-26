---
title: enclose method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
---
## enclose(self) {#}
Innesluter ett matematiskt element i parentes

### Returnerar

Matematikelementet av typen [`IMathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/imathdelimiter) som inkluderar parentesen



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Innesluter ett matematiskt element i angivna tecken, såsom parentes eller andra tecken som ram

### Returnerar

Om `beginning_character` och `ending_character` är None, 
            tilldelas motsvarande egenskaper endast värden och inget nytt objekt skapas (returnerar detta exempel).
            Annars returneras ett nytt matematiskt element av typen Delimiter som inkluderar de angivna tecknen som ram 
            och detta exempel av [`MathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter) inramat innanför.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| beginning_character | **char** | Inledande tecken (vanligtvis vänster hakparentes) |
| ending_character | **char** | Avslutande tecken (vanligtvis höger hakparentes) |



### Se även
* klass [`IMathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/imathdelimiter)
* klass [`MathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/mathdelimiter)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)