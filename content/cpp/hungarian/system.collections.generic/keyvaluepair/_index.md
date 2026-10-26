---
title: KeyValuePair
second_title: Aspose.Slides C++ API hivatkozás
description: "A kulcs és érték páros. Ezt a típust a stack-en kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a System::SmartPtr osztályt ezen típusú objektumok kezelésére."
type: docs
weight: 378
url: /hu/system.collections.generic/keyvaluepair/
---
## KeyValuePair osztály


Key és value páros. Ezt a típust a stack-en kell lefoglalni, és értékkel vagy referenciával kell átadni a függvényeknek. Soha ne használja a [System::SmartPtr](../../system/smartptr/) osztályt ennek a típusnak az objektumainak kezeléséhez.

```cpp
template<typename TKey,typename TValue>class KeyValuePair
```

## Metódusok

| Metódus | Leírás |
| --- | --- |
| const TKey\& [get_Key](./get_key/)() const | Visszaadja a kulcsot. |
| const TValue\& [get_Value](./get_value/)() const | Visszaadja az értéket. |
| int [GetHashCode](./gethashcode/)() const | Kiszámítja a kulcs-érték pár hash-ét a kulcs és az érték hash-nek XOR-olásával. |
| **bool** [IsNull](./isnull/)() const | Mindig hamis értéket ad vissza. |
|  [KeyValuePair](./keyvaluepair/)() | Null kulcs-érték pár inicializáló. |
|  [KeyValuePair](./keyvaluepair/)(const TKey\&, const TValue\&) | Konstruktor. |
|  [KeyValuePair](./keyvaluepair/)(const std::pair\<OtherK, OtherV\>\&) | Típuskonverziós konstruktor. |
| **bool** [operator<](./operator_less/)(const [KeyValuePair](./)\&) const | Javítás az IComparer<KeyValuePair<TKey, TValue>>-ből származó osztályokhoz, nem hasonlít össze semmit. |
| [String](../../system/string/) [ToString](./tostring/)() const | A kulcs-érték párt stringgé konvertálja. |

## Lásd még

* Névtér [System::Collections::Generic](../)
* Könyvtár [Aspose.Slides](../../)