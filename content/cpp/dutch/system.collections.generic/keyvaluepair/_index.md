---
title: KeyValuePair
second_title: Aspose.Slides voor C++ API-referentie
description: "Koppel van sleutel en waarde. Dit type moet op de stack worden toegewezen en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 378
url: /nl/system.collections.generic/keyvaluepair/
---
## KeyValuePair klasse


Koppel van sleutel en waarde. Dit type moet op de stack worden toegewezen en aan functies worden doorgegeven per waarde of per referentie. Gebruik nooit [System::SmartPtr](../../system/smartptr/) klasse om objecten van dit type te beheren.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Methoden

| Method | Beschrijving |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Haalt sleutel op. |
| const TValue\& [get_Value](./get_value/)() const | Haalt waarde op. |
| int [GetHashCode](./gethashcode/)() const | Berekent hash van sleutel-waardepaar door de hashes van sleutel en waarde te xoren. |
| **bool** [IsNull](./isnull/)() const | Retourneert altijd false. |
|  [KeyValuePair](./keyvaluepair/)() | Null sleutel-waardepaar initialisator. |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Constructor. |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Typeconversie-constructor. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Patch voor klassen die afstammen van IComparer<KeyValuePair<TKey, TValue>>, vergelijkt niets. |
| [String](../../system/string/) [ToString](./tostring/)() const | Converteert sleutel-waardepaar naar string. |

## Zie ook

* Naamruimte [System::Collections::Generic](../)
* Bibliotheek [Aspose.Slides](../../)