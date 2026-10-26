---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides pro Python přes .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded vlastnost
Tato vlastnost dává smysl, pokud je soubor prezentace chráněn heslem a dokumentové vlastnosti tohoto souboru jsou veřejné.
Hodnota true znamená, že jsou načteny pouze dokumentové vlastnosti z šifrovaného souboru prezentace bez použití hesla.
Hodnota false znamená, že je načtena celá šifrovaná prezentace s použitím správného hesla, a ne pouze dokumentové vlastnosti.
Pokud prezentace není šifrovaná, hodnota vlastnosti je vždy false.
Pokud dokumentové vlastnosti šifrovaného souboru nejsou veřejné, hodnota vlastnosti je vždy false.
Pokud je PresentationEx.EncryptDocumentProperties true, pak je hodnota vlastnosti IsOnlyDocumentPropertiesLoaded vždy false.
Pouze pro čtení **bool**.

### Definice:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Viz také
* třída [`IProtectionManager`](/slides/python-net/cs/aspose.slides/iprotectionmanager)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)