---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded свойство
Это свойство имеет смысл, если файл презентации защищён паролем и свойства документа этого файла являются публичными. Значение true означает, что только свойства документа загружаются из зашифрованного файла презентации без использования пароля. Значение false означает, что вся зашифрованная презентация загружается с использованием правильного пароля, а не только свойства документа. Если презентация не зашифрована, то значение свойства всегда false. Если свойства документа зашифрованного файла не являются публичными, то значение свойства всегда false. Если PresentationEx.EncryptDocumentProperties имеет значение true, то значение свойства IsOnlyDocumentPropertiesLoaded всегда false. Только для чтения **bool**.

### Определение:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### См. также
* класс [`IProtectionManager`](/slides/python-net/ru/aspose.slides/iprotectionmanager)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)