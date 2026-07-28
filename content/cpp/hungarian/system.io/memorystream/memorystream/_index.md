---
title: MemoryStream()
second_title: Aspose.Slides for C++ API referencia
description: Létrehoz egy új példányt a MemoryStream osztályból, kezdeti kapacitása 0.
type: docs
weight: 1
url: /hu/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() konstruktor

Létrehoz egy új példányt a [MemoryStream](../) osztályból, kezdeti kapacitással, amely 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) konstruktor

Létrehoz egy új példányt a [MemoryStream](../) osztályból, amely egy megadott méretű memória-pufferen alapuló adatfolyamot képvisel.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| capacity_ | int | A memória-puffer mérete bájtokban, amely az objektum által létrehozott adatfolyamhoz tartozik |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) konstruktor

Létrehoz egy új példányt a [MemoryStream](../) osztályból, amely egy megadott memória-pufferhez csatlakozó memória-adatfolyamot képvisel. Egy paraméter határozza meg, hogy az adatfolyam írható-e.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Egy bájt tömb, amely memória-pufferként szolgál, amelyen az objektum által létrehozott adatfolyam alapul |
| writable | **bool** | Megadja, hogy az adatfolyam írható-e |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) konstruktor

Létrehoz egy új példányt a [MemoryStream](../) osztályból, amely egy megadott memória-puffer egy szegmenséhez csatlakozik, a megadott indexnél kezdődően, és tartalmazza a megadott számú elemet. A paraméterek meghatározzák, hogy az adatfolyam írható-e, illetve hívható-e a GetBytes() metódus.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Egy bájt tömb, amelynek egy szegmense memória-pufferként szolgál az objektum által létrehozott adatfolyam alapjául |
| index | int | Egy 0-alapú index az **content** elemei közül, ahol a szegmens kezdődik |
| count | int | Az **content** elemeinek száma, amely a szegmensben szerepel |
| writable | **bool** | Megadja, hogy az adatfolyam írható-e |
| publiclyVisible | **bool** | Megadja, hogy a háttér-memória-puffer elérhető-e a GetByte() metódus hívójának |

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)