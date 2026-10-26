---
title: only_load_document_properties property
second_title: Aspose.Slides pro Python prostřednictvím .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties vlastnost
Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem.
Hodnota true znamená, že musí být načteny pouze vlastnosti dokumentu z šifrovaného 
prezentace souboru a heslo má být ignorováno.
Hodnota false znamená, že musí být načtena celá šifrovaná prezentace s použitím správného 
hesla.
Pokud prezentace není šifrována, pak je hodnota vlastnosti vždy ignorována.
Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné a hodnota vlastnosti je true, 
pak vlastnosti dokumentu nelze načíst a bude vyvolána výjimka.
Čtení-zápis **bool**.

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
* třída [`ILoadOptions`](/slides/python-net/cs/aspose.slides/iloadoptions)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)