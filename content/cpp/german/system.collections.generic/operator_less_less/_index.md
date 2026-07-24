---
title: operator<<()
second_title: Aspose.Slides für C++ API-Referenz
description: Daten in den Stream mit UTF-8-Kodierung einfügen.
type: docs
weight: 716
url: /de/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) Funktion

Daten in den Stream mittels UTF-8-Kodierung einfügen.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | Schlüsseltyp. |
| TValue | Wertetyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | std::ostream\& | Ausgabestream, in den Daten eingefügt werden. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) zum Einfügen. |

### Rückgabewert

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) Funktion

Daten in den Stream einfügen.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### Vorlagenparameter

| Parameter | Beschreibung |
| --- | --- |
| TKey | Schlüsseltyp. |
| TValue | Wertetyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | std::wostream\& | Ausgabestream, in den Daten eingefügt werden. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) zum Einfügen. |

### Rückgabewert

**stream**.

## Siehe auch

* Klasse [KeyValuePair](../keyvaluepair/)
* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)