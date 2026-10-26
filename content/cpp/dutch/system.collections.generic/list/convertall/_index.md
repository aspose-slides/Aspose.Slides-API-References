---
title: ConvertAll()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een lijst met elementen die naar een ander type zijn geconverteerd.
type: docs
weight: 352
url: /nl/system.collections.generic/list/convertall/
---
## List::ConvertAll(Converter\<T, OutputType\>) method

Maakt een lijst met elementen die naar een ander type zijn geconverteerd.

```cpp
template<typename OutputType> SharedPtr<List<OutputType>> System::Collections::Generic::List<T>::ConvertAll(Converter<T, OutputType> converter)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| OutputType | Output-lijst elementtype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| converter | [Converter](../../../system/converter/)\<T, OutputType\> | Converter die moet worden gebruikt voor de conversie van items. |

### Retourwaarde

Een nieuw aangemaakte lijst met geconverteerde elementen.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Converter](../../../system/converter/)
* Klasse [List](../)
* Naamruimte [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)