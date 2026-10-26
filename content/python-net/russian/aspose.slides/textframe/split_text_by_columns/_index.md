---
title: split_text_by_columns method
second_title: Aspose.Slides для Python через .NET API Справочник
description: 
type: docs
url: /ru/aspose.slides/textframe/split_text_by_columns/
weight: 60
---
## split_text_by_columns(self) {#}
Разбивает текстовое содержимое [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe) на массив строк,  
            где каждый элемент соответствует отдельному текстовому столбцу внутри кадра.

### Возвращаемое значение

Массив строк, где каждая строка представляет текстовое содержимое конкретного столбца  
            в [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe).



```python
def split_text_by_columns(self):
    ...
```


### Примечания

Если текстовый кадр не содержит несколько столбцов, возвращаемый массив будет иметь один элемент,  
            содержащий весь текст.  
            Пустые столбцы будут представлены пустыми строками в массиве.



### См. также
* класс [`ITextFrame`](/slides/python-net/ru/aspose.slides/itextframe)
* класс [`TextFrame`](/slides/python-net/ru/aspose.slides/textframe)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)