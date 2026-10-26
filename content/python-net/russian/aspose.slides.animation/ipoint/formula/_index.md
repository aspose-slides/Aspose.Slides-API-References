---
title: formula property
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.animation/ipoint/formula/
weight: 10
---
## formula свойство
Formulas within values, from, to, by attributes can be made up of these:
            Стандартные арифметические операторы: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
            Константы: ‘pi’ ‘e’
            Условные операторы: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
            Операторы сравнения: '==', '>=', '', '!=', '!'
            Тригонометрические операторы: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
            Натуральный логарифм ‘ln()’
            Ссылки на свойства (поддерживаемые хостом свойства)
            
            например: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
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
* класс [`IPoint`](/slides/python-net/ru/aspose.slides.animation/ipoint)
* модуль [`aspose.slides.animation`](/slides/python-net/ru/aspose.slides.animation)
* библиотека [`Aspose.Slides`](/slides/python-net)