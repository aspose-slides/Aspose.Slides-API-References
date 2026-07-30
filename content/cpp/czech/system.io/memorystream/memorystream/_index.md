---
title: MemoryStream()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou instanci třídy MemoryStream s počáteční kapacitou rovnou 0.
type: docs
weight: 1
url: /cs/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() konstruktor


Vytvoří novou instanci třídy [MemoryStream](../) s počáteční kapacitou rovnající se 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) konstruktor


Vytvoří novou instanci třídy [MemoryStream](../), která představuje proud založený na paměťovém bufferu o specifikované velikosti.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| capacity_ | int | Velikost v bajtech paměťového bufferu spojeného s proudem, který představuje vytvářený objekt |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) konstruktor


Vytvoří novou instanci třídy [MemoryStream](../), která představuje paměťový proud připojený k určenému paměťovému bufferu. Parametr určuje, zda je proud zapisovatelný.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů, které bude použito jako paměťový buffer, na kterém bude založen proud představovaný vytvářeným objektem |
| writable | **bool** | Určuje, zda má být proud zapisovatelný |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) konstruktor


Vytvoří novou instanci třídy [MemoryStream](../), která představuje paměťový proud připojený k segmentu určeného paměťového bufferu počínaje zadaným indexem a zahrnující zadaný počet prvků. Parametry určují, zda je proud zapisovatelný a zda může být volána metoda GetBytes().

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Pole bajtů, jehož segment má být použit jako paměťový buffer, na kterém bude založen proud představovaný vytvářeným objektem |
| index | int | Nulový index prvku v **content**, kde segment začíná |
| count | int | Počet prvků **content** zahrnutých do segmentu |
| writable | **bool** | Určuje, zda má být proud zapisovatelný |
| publiclyVisible | **bool** | Určuje, zda má být podkladový paměťový buffer zpřístupněn volajícímu metody GetByte() |

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* třída [MemoryStream](../)
* jmenný prostor [System::IO](../../)
* Library [Aspose.Slides](../../../)