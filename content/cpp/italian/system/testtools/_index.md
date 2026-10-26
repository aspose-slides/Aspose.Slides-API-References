---
title: TestTools
second_title: Riferimento API di Aspose.Slides per C++
description: Fornisce un insieme di metodi utili che verificano alcune proprietà di base di diversi tipi e funzioni.
type: docs
weight: 1925
url: /it/system/testtools/
---
## TestTools struct

Fornisce un set di metodi utili che verificano alcune proprietà di base di diversi tipi e funzioni.

```cpp
class TestTools
```

## Methods

| Method | Description |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Verifica se la funzione lancia un'eccezione di qualsiasi tipo. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Verifica se la stringa è vuota. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Verifica se la collezione è vuota. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Verifica se il valore specifico è null. [Version](../version/) per i tipi aritmetici e enum. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Verifica se il valore specifico è null. [Version](../version/) per i tipi non aritmetici e non enum. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Verifica se il valore specifico è null. [Version](../version/) per i tipi non aritmetici. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Verifica se il valore specifico è null. [Version](../version/) per le coppie chiave-valore. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Verifica se la stringa è null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Verifica se la collezione è null o vuota. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Verifica se la stringa è null o vuota. |
## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)