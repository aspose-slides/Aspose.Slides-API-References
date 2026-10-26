---
title: enclose method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides.mathtext/imathblock/enclose/
weight: 90
---
## enclose(self) {#}



```python
def enclose(self):
    ...
```



## enclose(self, beginning_character, ending_character) {#char-char}



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| beginning_character | **char** |  |
| ending_character | **char** |  |


## enclose(self, beginning_character, ending_character, separator_character) {#char-char-char}
Обрамляет дочерние элементы этого блока в указанные символы, такие как скобки или другие, в качестве рамки и разделяет их символом-разделитель

### Возвращаемое значение
Элемент математического типа [`IMathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/imathdelimiter), который включает указанные символы в качестве рамки и разделителя



```python
def enclose(self, beginning_character, ending_character, separator_character):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| beginning_character | **char** | Начальный символ (обычно левая скобка) |
| ending_character | **char** | Конечный символ (обычно правая скобка) |
| separator_character | **char** | Символ разделитель |



### См. также
* класс [`IMathBlock`](/slides/python-net/ru/aspose.slides.mathtext/imathblock)
* класс [`IMathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/imathdelimiter)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)