---
title: MathDelimiter constructor
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.mathtext/mathdelimiter/__init__/
weight: 10
---
## __init__(self, element) {#imathelement}
Инициализирует MathDelimiter указанным элементом в качестве единственного базового аргумента


```python
def __init__(self, element):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| element | [`IMathElement`](/slides/python-net/ru/aspose.slides.mathtext/imathelement) | Базовый элемент, к которому применяется разделитель. Может быть None. |

### Исключения

| Исключение | Описание |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Выбрасывается, если `element` является контейнером для других элементов, таких как MathBlock. В этом случае необходимо вызвать другой конструктор с аргументом IEnumerable. |



### Смотрите также
* класс [`IMathElement`](/slides/python-net/ru/aspose.slides.mathtext/imathelement)
* класс [`MathDelimiter`](/slides/python-net/ru/aspose.slides.mathtext/mathdelimiter)
* модуль [`aspose.slides.mathtext`](/slides/python-net/ru/aspose.slides.mathtext)
* библиотека [`Aspose.Slides`](/slides/python-net)