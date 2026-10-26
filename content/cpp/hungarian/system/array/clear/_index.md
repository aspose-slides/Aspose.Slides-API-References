---
title: Clear()
second_title: Aspose.Slides C++ API referencia
description: Nem támogatott, mert a jelenlegi objektum által képviselt tömb csak olvasható.
type: docs
weight: 53
url: /hu/system/array/clear/
---
## Array::Clear() metódus

Nem támogatott, mert a jelenlegi objektum által képviselt tömb csak olvasható.

```cpp
virtual void System::Array<T>::Clear() override
```

## Array::Clear(const ArrayPtr\<Type\>\&, int, int) metódus

Felcseréli a **count** értéket, amely a **startIndex** indexnél kezdődik a megadott tömbben, alapértelmezett értékekkel.

```cpp
template<typename Type> static void System::Array<T>::Clear(const ArrayPtr<Type> &arr, int startIndex, int count)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| Type | Az elemek típusa a cél tömbben |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<[Type](../../object/type/)\>\& | Cél tömb |
| startIndex | int | [Index](../../index/) ahol elkezdjük a tételek cseréjét |
| count | int | A cserélendő tételek száma |

## Lásd még

* Típusdefiníció [ArrayPtr](../../arrayptr/)
* Metódus [Type](../../object/type/)
* Osztály [Array](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)