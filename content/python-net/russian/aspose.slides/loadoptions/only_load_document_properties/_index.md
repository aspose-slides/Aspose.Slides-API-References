---
title: only_load_document_properties property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties свойство
Это свойство имеет смысл, если файл презентации защищён паролем.
            Значение true означает, что только свойства документа должны быть загружены из зашифрованного 
            файла презентации, а пароль должен игнорироваться.
            Значение false означает, что вся зашифрованная презентация должна быть загружена с использованием правильного 
            пароля.
            Если презентация не зашифрована, то значение свойства всегда игнорируется.
            Если свойства документа зашифрованного файла не публичны и значение свойства равно true, то
            свойства документа не могут быть загружены, и будет выброшено исключение.
            Чтение/запись **bool**.

### Определение:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```


### См. также
* класс [`LoadOptions`](/slides/python-net/ru/aspose.slides/loadoptions)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)