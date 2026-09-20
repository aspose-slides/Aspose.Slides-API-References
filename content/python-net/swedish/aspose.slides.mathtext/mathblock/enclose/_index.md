---
title: enclose method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
Innesluter ett matematikelement i parentes

### Returnerar

Matematikelementet av typen [`IMathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/imathdelimiter) som inkluderar parenteserna



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Innesluter underordnade element i detta block i angivna tecken, såsom parenteser eller andra tecken som ram

### Returnerar

Matematikelementet av typen [`IMathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/imathdelimiter) som inkluderar angivna tecken som ram



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| beginning_character | **char** | Inledande tecken (vanligtvis vänster hakparentes) |
| ending_character | **char** | Avslutande tecken (vanligtvis höger hakparentes) |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
Innesluter underordnade element i detta block i angivna tecken, såsom parenteser eller andra som ram och avgränsar med ett separator-tecken

### Returnerar

Matematikelementet av typen [`IMathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/imathdelimiter) som inkluderar angivna tecken som ram och avgränsare



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| beginning_character | **char** | Inledande tecken (vanligtvis vänster hakparentes) |
| ending_character | **char** | Avslutande tecken (vanligtvis höger hakparentes) |
| separator_character | **char** | Separator-tecken |



### Se också
* klass [`IMathDelimiter`](/slides/python-net/sv/aspose.slides.mathtext/imathdelimiter)
* klass [`MathBlock`](/slides/python-net/sv/aspose.slides.mathtext/mathblock)
* modul [`aspose.slides.mathtext`](/slides/python-net/sv/aspose.slides.mathtext)
* bibliotek [`Aspose.Slides`](/slides/python-net)