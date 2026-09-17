---
title: app_version property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/idocumentproperties/app_version/
weight: 90
---
## app_version свойство
Возвращает версию приложения.
            Только для чтения **str**.


### Примечания

Содержание этого элемента должно быть в формате XX.YYYY, где X и Y представляют числовые значения;
            в противном случае документ считается несоответствующим.
            Aspose.Slides представляет свою версию в формате XX.YYZZ, где:
            XX - основная версия
            YY - вторичная версия
            ZZ - версия исправления
            Например, значение 23.0105 означает версию Aspose.Slides 23.1.5.

### Определение:
```python
@property
def app_version(self):
    ...
```


### См. также
* класс [`IDocumentProperties`](/slides/python-net/ru/aspose.slides/idocumentproperties)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)