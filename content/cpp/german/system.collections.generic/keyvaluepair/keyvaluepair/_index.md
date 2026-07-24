---
title: KeyValuePair()
second_title: Aspose.Slides für C++ API Referenz
description: Null Schlüssel-Wert-Paar Initialisierer.
type: docs
weight: 1
url: /de/system.collections.generic/keyvaluepair/keyvaluepair/
---
## KeyValuePair::KeyValuePair() Konstruktor

Null Schlüssel-Wert-Paar Initialisierer.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair()
```

## KeyValuePair::KeyValuePair(const TKey\&, const TValue\&) Konstruktor

Konstruktor.

```cpp
System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const TKey &key, const TValue &value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| key | const TKey\& | Schlüssel. |
| value | const TValue\& | Wert. |

## KeyValuePair::KeyValuePair(const std::pair\<OtherK, OtherV\>\&) Konstruktor

Typkonvertierungskonstruktor.

```cpp
template<typename OtherK,typename OtherV> System::Collections::Generic::KeyValuePair<TKey, TValue>::KeyValuePair(const std::pair<OtherK, OtherV> &pair)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| OtherK | Anderer Schlüsseltyp. |
| OtherV | Anderer Werttyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pair | const std::pair\<OtherK, OtherV\>\& | Paarwert. |

## Siehe auch

* Klasse [KeyValuePair](../)
* Namensraum [System::Collections::Generic](../../)
* Bibliothek [Aspose.Slides](../../../)