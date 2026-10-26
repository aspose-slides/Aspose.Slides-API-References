---
title: only_load_document_properties property
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties свойство
Это свойство имеет смысл, если файл презентации защищён паролем.
Значение true означает, что из зашифрованного файла презентации должны быть загружены только свойства документа, а пароль должен игнорироваться.
Значение false означает, что вся зашифрованная презентация должна быть загружена с использованием правильного пароля.
Если презентация не зашифрована, значение свойства всегда игнорируется.
Если свойства документа зашифрованного файла не являются публичными и значение свойства равно true, то свойства документа не могут быть загружены, и будет выброшено исключение.
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
* класс [`ILoadOptions`](/slides/python-net/ru/aspose.slides/iloadoptions)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)