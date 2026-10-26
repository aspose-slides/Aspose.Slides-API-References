---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides dla Pythona via .NET Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded właściwość
Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem i dokument 
            właściwości tego pliku są publiczne.
            Wartość true oznacza, że tylko właściwości dokumentu są ładowane z zaszyfrowanego 
            pliku prezentacji bez użycia hasła.
            Wartość false oznacza, że cała zaszyfrowana prezentacja jest ładowana przy użyciu prawidłowego 
            hasła, a nie tylko właściwości dokumentu są ładowane.
            Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze false.
            Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne, wartość właściwości jest zawsze false.
            Jeśli Presentation.EncryptDocumentProperties jest true, to IsOnlyDocumentPropertiesLoaded 
            wartość właściwości jest zawsze false.
            Tylko do odczytu **bool**.

### Definicja:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Zobacz także
* klasa [`ProtectionManager`](/slides/python-net/pl/aspose.slides/protectionmanager)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)