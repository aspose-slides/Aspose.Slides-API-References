---
title: operator<<()
second_title: Aspose.Slides för C++ API-referens
description: Infoga data i strömmen med UTF-8-kodning.
type: docs
weight: 716
url: /sv/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) funktion

Infoga data i strömmen med UTF-8-kodning.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Nyckeltyp. |
| TValue | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | std::ostream\& | Utdataström att infoga data i. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) att infoga. |

### Returvärde

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) funktion

Infoga data i strömmen.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| TKey | Nyckeltyp. |
| TValue | Värdetyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | std::wostream\& | Utdataström att infoga data i. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) att infoga. |

### Returvärde

**stream**.

## Se även

* Klass [KeyValuePair](../keyvaluepair/)
* Namnrymd [System::Collections::Generic](../)
* Bibliotek [Aspose.Slides](../../)