---
title: KeyValuePair()
second_title: Aspose.Slides voor C++ API-referentie
description: Null key-value pair-initialisator.
type: docs
weight: 1
url: /nl/system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() constructor

Null key-value pair-initialisator.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey\&, const TValue\&) constructor

Constructor.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| key | const TKey\& | Sleutel. |
| value | const TValue\& | Waarde. |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>\&) constructor

Constructor voor typeconversie.

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| OtherK | Andere sleuteltype. |
| OtherV | Andere waardetype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>\& | Paarwaarde. |

## Zie ook

* Klasse [KeyValuePair](../)
* Namespace [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)