---
title: MemoryStream()
second_title: Aspose.Slides für C++ API-Referenz
description: Konstruiert eine neue Instanz der MemoryStream-Klasse mit einer Anfangskapazität von 0.
type: docs
weight: 1
url: /de/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() Konstruktor

Konstruiert eine neue Instanz der [MemoryStream](../) Klasse mit einer Anfangskapazität von 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) Konstruktor

Konstruiert eine neue Instanz der [MemoryStream](../) Klasse, die einen Stream darstellt, der auf einem Speicherpuffer der angegebenen Größe basiert.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| capacity_ | int | Die Größe in Bytes eines Speicherpuffers, der mit dem von dem zu erstellenden Objekt dargestellten Stream verbunden ist |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) Konstruktor

Konstruiert eine neue Instanz der [MemoryStream](../) Klasse, die einen Speicherstream darstellt, der mit dem angegebenen Speicherpuffer verbunden ist. Ein Parameter gibt an, ob der Stream schreibbar ist.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ein Byte-Array, das als Speicherpuffer verwendet wird, auf dem der von dem zu erstellenden Objekt dargestellte Stream basiert |
| writable | **bool** | Gibt an, ob der Stream schreibbar sein soll |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) Konstruktor

Konstruiert eine neue Instanz der [MemoryStream](../) Klasse, die einen Speicherstream darstellt, der mit einem Segment des angegebenen Speicherpuffers verbunden ist, beginnend am angegebenen Index und einschließlich der angegebenen Anzahl von Elementen. Parameter geben an, ob der Stream schreibbar ist und ob die Methode GetBytes() aufgerufen werden kann.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Ein Byte-Array, dessen ein Segment als Speicherpuffer verwendet werden soll, auf dem der von dem zu erstellenden Objekt dargestellte Stream basiert |
| index | int | Ein 0-basierter Index des Elements in **content**, an dem das Segment beginnt |
| count | int | Die Anzahl der Elemente von **content**, die im Segment enthalten sind |
| writable | **bool** | Gibt an, ob der Stream schreibbar sein soll |
| publiclyVisible | **bool** | Gibt an, ob der zugrunde liegende Speicherpuffer dem Aufrufer der Methode GetByte() zur Verfügung gestellt werden soll |

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [MemoryStream](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)