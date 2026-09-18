---
title: formula property
second_title: Aspose.Slides dla Pythona przez .NET - odniesienie API
description: 
type: docs
url: /pl/aspose.slides.animation/ipoint/formula/
weight: 10
---
## formula właściwość
Formuły w wartościach, atrybutach from, to, by mogą składać się z następujących elementów:
- Standardowe operatory arytmetyczne: ‘+’, ‘-‘, ‘*’, ‘/’, ‘^’, ‘%’ (mod)
- Stałe: ‘pi’ ‘e’
- Operatory warunkowe: ‘abs’, ‘min’, ‘max’, ‘?’ (if)
- Operatory porównania: '==', '>=', '', '!=', '!'
- Operatory trygonometryczne: ‘sin()’, ‘cos()’, ‘tan()’, ‘asin()’, ‘acos()’, ‘atan()’
- Logarytm naturalny ‘ln()’
- Odwołania do właściwości (właściwości obsługiwane przez host)

na przykład: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)"
Odczyt/zapis **str**.

### Definicja:
```python
@property
def formula(self):
    ...

@formula.setter
def formula(self, value):
    ...
```

### Zobacz także
* klasa [`IPoint`](/slides/python-net/pl/aspose.slides.animation/ipoint)
* moduł [`aspose.slides.animation`](/slides/python-net/pl/aspose.slides.animation)
* biblioteka [`Aspose.Slides`](/slides/python-net)