---
title: Clear()
second_title: Aspose.Slides för C++ API-referens
description: Stöds inte eftersom arrayen som representeras av det aktuella objektet är skrivskyddad.
type: docs
weight: 53
url: /sv/system/array/clear/
---
## Array::Clear() metod

Stöds inte eftersom arrayen som representeras av det aktuella objektet är skrivskyddad.

```cpp
virtual void System::Array<T>::Clear() override
```

## Array::Clear(const ArrayPtr\<Type\>\&, int, int) metod

Ersätter **count** värden som startar vid indexet **startIndex** i den angivna arrayen med standardvärden.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| Type | Typ av element i målarrayen |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Målarray |
| startIndex | int | [Index](../../index/) vid vilken man börjar ersätta objekten |
| count | int | Antalet objekt att ersätta |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Metod [Type](../../object/type/)
* Klass [Array](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)