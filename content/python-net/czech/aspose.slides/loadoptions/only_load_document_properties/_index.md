---
title: only_load_document_properties property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/loadoptions/only_load_document_properties/
weight: 110
---
## only_load_document_properties vlastnost
Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem.
            Value of true means that only document properties must be loaded from an encrypted 
            presentation file and password must be ignored.
            Value of false means that entire encrypted presentation must be loaded with use of right 
            password.
            If presentation isn't encrypted then property value is always ignored.
            If document properties of an encrypted file aren't public and property value is true then
            document properties cannot be loaded and exception will be thrown.
            Číst/Zapisovat **bool**.

### Definice:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```

### Viz také
* třída [`LoadOptions`](/slides/python-net/cs/aspose.slides/loadoptions)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)