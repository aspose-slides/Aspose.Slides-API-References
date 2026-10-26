---
title: get_substitutions method
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides/ifontsmanager/get_substitutions/
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
| slides | **List[int]** | Массив индексов слайдов, для которых необходимо получить информацию о замене шрифтов, начиная с 1. |



### См. также
* класс [`FontSubstitutionInfo`](/slides/python-net/ru/aspose.slides/fontsubstitutioninfo)
* класс [`IFontsManager`](/slides/python-net/ru/aspose.slides/ifontsmanager)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)