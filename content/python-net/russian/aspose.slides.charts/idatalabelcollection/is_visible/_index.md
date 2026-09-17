---
title: is_visible property
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.charts/idatalabelcollection/is_visible/
weight: 120
---
## is_visible свойство
False означает, что подпись данных по умолчанию не видима (и поэтому все флаги Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat имеют значение false). Только для чтения **bool**.

### Замечания

Если подпись данных видима по умолчанию, вы можете скрыть её по умолчанию с помощью метода Hide(). Но если подпись данных не видима по умолчанию (IsVisible равно false), вы можете сделать подпись данных «видимой по умолчанию», установив флаги Show*-flags (ShowValue, ...) свойства DefaultDataLabelFormat в состояние true.

### Определение:
```python
@property
def is_visible(self):
    ...
```

### См. также
* класс [`IDataLabelCollection`](/slides/python-net/ru/aspose.slides.charts/idatalabelcollection)
* модуль [`aspose.slides.charts`](/slides/python-net/ru/aspose.slides.charts)
* библиотека [`Aspose.Slides`](/slides/python-net)