---
title: operator<<()
second_title: Referencja API Aspose.Slides dla C++
description: Wstaw dane do strumienia przy użyciu kodowania UTF-8.
type: docs
weight: 716
url: /pl/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream\&, const KeyValuePair\<TKey, TValue\>\&) funkcja

Wstaw dane do strumienia przy użyciu kodowania UTF-8.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TKey | Typ klucza. |
| TValue | Typ wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | std::ostream\& | Strumień wyjściowy do wstawienia danych. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) do wstawienia. |

### Wartość zwracana

**stream**.

## System::Collections::Generic::operator<<(std::wostream\&, const KeyValuePair\<TKey, TValue\>\&) funkcja

Wstaw dane do strumienia.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| TKey | Typ klucza. |
| TValue | Typ wartości. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | std::wostream\& | Strumień wyjściowy do wstawienia danych. |
| pair | const [KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\& | [Data](../../system.data/) do wstawienia. |

### Wartość zwracana

**stream**.

## Zobacz także

* Klasa [KeyValuePair](../keyvaluepair/)
* Przestrzeń nazw [System::Collections::Generic](../)
* Biblioteka [Aspose.Slides](../../)