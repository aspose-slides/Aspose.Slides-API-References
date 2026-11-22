---
title: split_text_by_columns method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/textframe/split_text_by_columns/
weight: 70
---
## split_text_by_columns(self) {#}
Разбивает текстовое содержимое [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe) на массив строк,  
            где каждый элемент соответствует отдельному текстовому столбцу внутри рамки.

### Возвращаемое значение

Массив строк, где каждая строка представляет собой текстовое содержимое конкретного столбца в [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe).



```python
def split_text_by_columns(self):
    ...
```


### Примечания

Если текстовая рамка не содержит несколько столбцов, возвращаемый массив будет содержать один элемент, включающий весь текст.  
            Пустые столбцы будут представлены пустыми строками в массиве.



### См. также
* класс [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe)
* класс [`TextFrame`](/slides/python-net/ru/aspose.slides/textframe)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)