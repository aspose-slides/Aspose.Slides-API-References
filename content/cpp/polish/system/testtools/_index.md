---
title: TestTools
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Udostępnia zestaw przydatnych metod, które sprawdzają niektóre podstawowe właściwości różnych typów i funkcji.
type: docs
weight: 1925
url: /pl/system/testtools/
---
## TestTools struct

Udostępnia zestaw przydatnych metod, które sprawdzają niektóre podstawowe właściwości różnych typów i funkcji.

```cpp
class TestTools
```

## Metody

| Method | Description |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Sprawdza, czy funkcja rzuca wyjątek dowolnego typu. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Sprawdza, czy ciąg jest pusty. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Sprawdza, czy kolekcja jest pusta. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Sprawdza, czy określona wartość jest nullem. [Version](../version/) dla typów arytmetycznych i wyliczeniowych. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Sprawdza, czy określona wartość jest nullem. [Version](../version/) dla typów niearytmetycznych i nie-wyliczeniowych. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Sprawdza, czy określona wartość jest nullem. [Version](../version/) dla typów niearytmetycznych. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Sprawdza, czy określona wartość jest nullem. [Version](../version/) dla par klucz-wartość. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Sprawdza, czy ciąg jest nullem. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Sprawdza, czy kolekcja jest nullem lub jest pusta. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Sprawdza, czy ciąg jest nullem lub jest pusty. |
## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)