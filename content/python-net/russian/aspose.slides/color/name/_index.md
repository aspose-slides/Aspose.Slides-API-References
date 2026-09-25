---
title: name property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/color/name/
weight: 190
---
## name свойство
Получает имя этого цвета.<br/>            Для именованного цвета (именованной константы такой как `Color.red`, или цвета, созданного с помощью [`from_name`](/slides/python-net/ru/aspose.slides/color/from_name/)) возвращается .NET-имя, например `"Red"` или `"LightBlue"`.<br/>            Для любого другого цвета значение ARGB возвращается в виде нижнего шестнадцатеричного числа без заполнения нулями, например `"ffff0000"`. `Color.empty.name` равен `"0"`.
            Только для чтения **str**.

### Определение:
```python
@property
def name(self):
    ...
```


### См. также
* класс [`Color`](/slides/python-net/ru/aspose.slides/color)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)