---
title: Exists()
second_title: Aspose.Slides voor C++ API-referentie
description: Bepaalt of het opgegeven Array-object een element bevat dat voldoet aan de vereisten van het opgegeven predicaat.
type: docs
weight: 781
url: /nl/system/array/exists/
---
## Array::Exists(ArrayPtr\<T\>, std::function\<bool(T)>) methode


Bepaalt of het opgegeven [Array](../)-object een element bevat dat voldoet aan de vereisten van de opgegeven predicaat.

```cpp
static bool System::Array<T>::Exists(ArrayPtr<T> arr, std::function<bool(T)> match)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arr | [ArrayPtr](../../arrayptr/)\<T\> | De array waarin naar het element wordt gezocht |
| match | std::function\<**bool**(T)> | Functiesobject dat de vereisten definieert en controleert of een element daaraan voldoet |

### Retourwaarde

Waar als **arr** een element bevat dat voldoet aan de vereisten gedefinieerd door **match**

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [Array](../)
* Naamruimte [System](../../)
* Library [Aspose.Slides](../../../)