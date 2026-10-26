---
title: enclose method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathblock/enclose/
weight: 100
---
## enclose(self) {#}
Оборачивает математический элемент в скобки

### Возвращаемое значение

Математический элемент типа [`IMathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/imathdelimiter), включающий скобки



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}
Оборачивает дочерние элементы этого блока в указанные символы, такие как скобки или другие символы, в качестве рамки

### Возвращаемое значение

Математический элемент типа [`IMathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/imathdelimiter), включающий указанные символы в качестве рамки



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| beginning_character | **char** | Начальный символ (обычно левая скобка) |
| ending_character | **char** | Конечный символ (обычно правая скобка) |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
Оборачивает дочерние элементы этого блока в указанные символы, такие как скобки или другие, в качестве рамки и разделяет их символом-разделителем

### Возвращаемое значение

Математический элемент типа [`IMathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/imathdelimiter), включающий указанные символы в качестве рамки и разделителя



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| beginning_character | **char** | Начальный символ (обычно левая скобка) |
| ending_character | **char** | Конечный символ (обычно правая скобка) |
| separator_character | **char** | Символ-разделитель |


### См. также
* класс [`IMathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/imathdelimiter)
* класс [`MathBlock`](/slides/python-net/ru/aspose.slides.mathtext/mathblock)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)