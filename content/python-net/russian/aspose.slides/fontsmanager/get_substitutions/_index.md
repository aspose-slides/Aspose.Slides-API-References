---
title: get_substitutions method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/fontsmanager/get_substitutions/
weight: 60
---
## get_substitutions(self) {#}
Получает информацию о шрифтах, которые будут заменены при рендеринге презентации.

### Возвращаемое значение

Коллекция всех замен шрифтов [`FontSubstitutionInfo`](/slides/python-net/ru/aspose.slides/fontsubstitutioninfo).



```python
def get_substitutions(self):
    ...
```



## get_substitutions(self, slides) {#listint}
Получает информацию о шрифтах, которые будут заменены при рендеринге указанных слайдов.

### Возвращаемое значение

Коллекция всех замен шрифтов ([`FontSubstitutionInfo`](/slides/python-net/ru/aspose.slides/fontsubstitutioninfo)) для указанных слайдов.



```python
def get_substitutions(self, slides):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| slides | **List[int]** | Массив индексов слайдов, для которых нужно получить информацию о заменах шрифтов, начиная с 1. |



### См. также
* класс [`FontsManager`](/slides/python-net/ru/aspose.slides/fontsmanager)
* класс [`FontSubstitutionInfo`](/slides/python-net/ru/aspose.slides/fontsubstitutioninfo)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)