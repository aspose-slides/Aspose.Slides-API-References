---
title: operator<<()
second_title: Aspose.Slides pro C++ - reference API
description: Vloží data do proudu pomocí kódování UTF-8.
type: docs
weight: 716
url: /cs/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) funkce


Vložte data do proudu pomocí kódování UTF-8.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TKey | Typ klíče. |
| TValue | Typ hodnoty. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::ostream\& | Výstupní proud, do kterého se data vkládají. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) k vložení. |

### Návratová hodnota

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) funkce


Vložte data do proudu.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Parametry šablony

| Parameter | Description |
| --- | --- |
| TKey | Typ klíče. |
| TValue | Typ hodnoty. |

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::wostream\& | Výstupní proud, do kterého se data vkládají. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) k vložení. |

### Návratová hodnota

**stream**.

## Viz také

* Třída [KeyValuePair](../keyvaluepair/)
* Jmenný prostor [System::Collections::Generic](../)
* Knihovna [Aspose.Slides](../../)