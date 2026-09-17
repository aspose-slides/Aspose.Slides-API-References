---
title: formula property
second_title: Aspose.Slides для Python через .NET Справочник API
description: 
type: docs
url: /ru/aspose.slides.animation/point/formula/
weight: 20
---
## formula свойство
Формулы в значениях, атрибутах from, to, by могут состоять из следующего:
            Стандартные арифметические операторы: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Константы: ‘pi’ ‘e’
            Условные операторы: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Операторы сравнения: '==', '>=', '', '!=', '!'
            Тригонометрические операторы: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Натуральный логарифм ‘ln()’
            Ссылки на свойства (host supported properties)
            
            например: "#ppt_x+(cos(-2-pi*(1-$))*-#ppt_x-sin(-2-pi*(1-$))*(1-#ppt_y))*(1-$)"
            Чтение/запись **str**.

### Определение:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```


### См. также
* класс [`Point`](/slides/python-net/ru/aspose.slides.animation/point)
* модуль [`aspose.slides.animation`](/slides/python-net/ru/aspose.slides.animation)
* библиотека [`Aspose.Slides`](/slides/python-net)