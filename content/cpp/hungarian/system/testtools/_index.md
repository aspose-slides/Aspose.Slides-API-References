---
title: TestTools
second_title: Aspose.Slides C++ API Referencia
description: Hasznos módszerek egy sorát biztosítja, amelyek ellenőrzik a különböző típusok és függvények alapvető tulajdonságait.
type: docs
weight: 1925
url: /hu/system/testtools/
---
## TestTools struct

Hasznos módszerek egy sorát biztosítja, amelyek ellenőrzik különböző típusok és függvények alapvető tulajdonságait.

```cpp
class TestTools
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Ellenőrzi, hogy a függvény kivételt dob-e bármilyen típusban. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Ellenőrzi, hogy a karakterlánc üres-e. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Ellenőrzi, hogy a gyűjtemény üres-e. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Ellenőrzi, hogy a megadott érték null-e. [Version](../version/) aritmetikus és enum típusokhoz. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Ellenőrzi, hogy a megadott érték null-e. [Version](../version/) nem aritmetikus és nem enum értéktípusokhoz. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Ellenőrzi, hogy a megadott érték null-e. [Version](../version/) nem aritmetikus értéktípusokhoz. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Ellenőrzi, hogy a megadott érték null-e. [Version](../version/) kulcs-érték párokhoz. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Ellenőrzi, hogy a karakterlánc null-e. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Ellenőrzi, hogy a gyűjtemény null-e vagy üres. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Ellenőrzi, hogy a karakterlánc null-e vagy üres. |

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)