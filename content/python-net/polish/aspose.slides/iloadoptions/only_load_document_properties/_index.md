---
title: only_load_document_properties property
second_title: Aspose.Slides dla Pythona via .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties właściwość
Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem.
            Wartość true oznacza, że z zaszyfrowanego pliku prezentacji należy załadować tylko właściwości dokumentu i hasło ma być ignorowane.
            Wartość false oznacza, że całą zaszyfrowaną prezentację należy załadować przy użyciu właściwego hasła.
            Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze ignorowana.
            Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość właściwości jest true, wtedy właściwości dokumentu nie mogą zostać załadowane i zostanie wyrzucony wyjątek.
            Odczyt-zapis **bool**.

### Definicja:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```

### Zobacz też
* klasa [`ILoadOptions`](/slides/python-net/pl/aspose.slides/iloadoptions)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)