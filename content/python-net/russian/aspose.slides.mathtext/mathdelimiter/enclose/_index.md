---
title: enclose method
second_title: Aspose.Slides для Python через .NET: справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathdelimiter/enclose/
weight: 60
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
Оборачивает математический элемент в указанные символы, такие как скобки или другие символы в качестве рамки

### Возвращаемое значение

Если `beginning_character` и `ending_character` имеют значение None, 
            соответствующие свойства получают только значения и новый объект не создаётся (возвращает этот экземпляр).
            В противном случае возвращается новый математический элемент типа Delimiter, который включает указанные символы в качестве рамки 
            и этот экземпляр [`MathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter) вложен внутрь.



```python
def enclose(self, beginning_character, ending_character):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| beginning_character | **char** | Символ начала (обычно левая скобка) |
| ending_character | **char** | Символ окончания (обычно правая скобка) |



### См. также
* class [`IMathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/imathdelimiter)
* class [`MathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter)
* module [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* library [`Aspose.Slides`](/slides/python-net)