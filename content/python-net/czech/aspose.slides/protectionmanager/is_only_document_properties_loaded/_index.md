---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides pro Python přes .NET API referenci
description: 
type: docs
url: /cs/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded vlastnost
Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné.
Hodnota true znamená, že jsou z šifrovaného souboru prezentace načteny pouze vlastnosti dokumentu bez použití hesla.
Hodnota false znamená, že je načtena celá šifrovaná prezentace s použitím správného hesla, ne jen vlastnosti dokumentu jsou načteny.
Pokud prezentace není šifrována, pak je hodnota vlastnosti vždy false.
Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné, pak je hodnota vlastnosti vždy false.
Pokud je Presentation.EncryptDocumentProperties true, pak je hodnota vlastnosti IsOnlyDocumentPropertiesLoaded vždy false.
Pouze ke čtení **bool**.

### Definice:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Viz také
* třída [`ProtectionManager`](/slides/python-net/cs/aspose.slides/protectionmanager)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)