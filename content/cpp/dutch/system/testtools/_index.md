---
title: TestTools
second_title: Aspose.Slides voor C++ API-referentie
description: Biedt een reeks handige methoden die enkele basis eigenschappen van verschillende types en functies controleren.
type: docs
weight: 1925
url: /nl/system/testtools/
---
## TestTools struct

Biedt een reeks handige methoden die enkele basis eigenschappen van verschillende types en functies controleren.

```cpp
class TestTools
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Controleert of de functie een uitzondering van welk type dan ook werpt. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Controleert of de string leeg is. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Controleert of de collectie leeg is. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Controleert of de specifieke waarde null is. [Version](../version/) voor rekenkundige en enum types. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Controleert of de specifieke waarde null is. [Version](../version/) voor niet-rekenkundige en niet-enum waardetypes. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Controleert of de specifieke waarde null is. [Version](../version/) voor niet-rekenkundige waardetypes. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Controleert of de specifieke waarde null is. [Version](../version/) voor sleutel-waardeparen. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Controleert of de string null is. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Controleert of de collectie null of leeg is. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Controleert of de string null of leeg is. |

## Zie ook

* Namespace [System](../)
* Bibliotheek [Aspose.Slides](../../)