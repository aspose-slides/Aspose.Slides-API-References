---
title: TestTools
second_title: Aspose.Slides för C++ API-referens
description: Tillhandahåller en uppsättning användbara metoder som kontrollerar vissa grundläggande egenskaper hos olika typer och funktioner.
type: docs
weight: 1925
url: /sv/system/testtools/
---
## TestTools struct

Tillhandahåller en uppsättning användbara metoder som kontrollerar vissa grundläggande egenskaper hos olika typer och funktioner.

```cpp
class TestTools
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Kontrollerar om funktionen kastar ett undantag av någon typ. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Kontrollerar om strängen är tom. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Kontrollerar om samlingen är tom. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Kontrollerar om ett specifikt värde är null. [Version](../version/) för aritmetiska och enum-typer. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Kontrollerar om ett specifikt värde är null. [Version](../version/) för icke-aritmetiska och icke-enum-värdetyper. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Kontrollerar om ett specifikt värde är null. [Version](../version/) för icke-aritmetiska värdetyper. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Kontrollerar om ett specifikt värde är null. [Version](../version/) för nyckel-värdepar. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Kontrollerar om strängen är null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Kontrollerar om samlingen är null eller tom. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Kontrollerar om strängen är null eller tom. |

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)