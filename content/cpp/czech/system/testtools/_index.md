---
title: TestTools
second_title: Aspose.Slides pro C++ API Reference
description: Poskytuje sadu užitečných metod, které kontrolují některé základní vlastnosti různých typů a funkcí.
type: docs
weight: 1925
url: /cs/system/testtools/
---
## TestTools struct

Poskytuje sadu užitečných metod, které kontrolují některé základní vlastnosti různých typů a funkcí.

```cpp
class TestTools
```

## Methods

| Method | Description |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Kontroluje, zda funkce vyhodí výjimku libovolného typu. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Kontroluje, zda je řetězec prázdný. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Kontroluje, zda je kolekce prázdná. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Kontroluje, zda je konkrétní hodnota null. [Version](../version/) pro aritmetické a výčtové typy. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Kontroluje, zda je konkrétní hodnota null. [Version](../version/) pro nearitmetické a nevýčtové typy hodnot. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Kontroluje, zda je konkrétní hodnota null. [Version](../version/) pro nearitmetické typy hodnot. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Kontroluje, zda je konkrétní hodnota null. [Version](../version/) pro páry klíč-hodnota. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Kontroluje, zda je řetězec null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Kontroluje, zda je kolekce null nebo prázdná. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Kontroluje, zda je řetězec null nebo prázdný. |

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)