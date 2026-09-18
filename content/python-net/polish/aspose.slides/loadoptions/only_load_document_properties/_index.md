---
title: only_load_document_properties property
second_title: Aspose.Slides dla Pythona - odniesienie API .NET
description: 
type: docs
url: /pl/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties właściwość
Ta właściwość ma sens, jeśli plik prezentacji jest chroniony hasłem.
            Wartość true oznacza, że tylko właściwości dokumentu muszą być wczytane z zaszyfrowanego
            pliku prezentacji i hasło musi być zignorowane.
            Wartość false oznacza, że cała zaszyfrowana prezentacja musi być wczytana przy użyciu prawidłowego
            hasła.
            Jeśli prezentacja nie jest zaszyfrowana, wartość właściwości jest zawsze ignorowana.
            Jeśli właściwości dokumentu zaszyfrowanego pliku nie są publiczne i wartość właściwości jest true, wtedy
            właściwości dokumentu nie mogą zostać wczytane i zostanie rzucony wyjątek.
            Odczyt/zapis **bool**.

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
* klasa [`LoadOptions`](/slides/python-net/pl/aspose.slides/loadoptions)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)