---
title: MemoryStream()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av MemoryStream-klassen med initial kapacitet lika med 0.
type: docs
weight: 1
url: /sv/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() konstruktor


Skapar en ny instans av [MemoryStream](../)-klassen med initial kapacitet lika med 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) konstruktor


Skapar en ny instans av [MemoryStream](../)-klassen som representerar en ström baserad på en minnesbuffert av den angivna storleken.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| capacity_ | int | Storleken i byte för en minnesbuffert som är associerad med strömmen som representeras av det objekt som skapas |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) konstruktor


Skapar en ny instans av [MemoryStream](../)-klassen som representerar en minnesström som är ansluten till den angivna minnesbufferten. En parameter anger om strömmen är skrivbar.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | En byte-array som ska användas som minnesbuffert som den ström som representeras av det objekt som skapas baseras på |
| writable | **bool** | Anger om strömmen ska vara skrivbar |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) konstruktor


Skapar en ny instans av [MemoryStream](../)-klassen som representerar en minnesström som är ansluten till ett segment av den angivna minnesbufferten som börjar vid det angivna indexet och inkluderar det angivna antalet element. Parametrar anger om strömmen är skrivbar och om metoden GetBytes() kan anropas.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | En byte-array vars segment ska användas som minnesbuffert som den ström som representeras av det objekt som skapas baseras på |
| index | int | Ett 0-baserat index för elementet i **content** där segmentet börjar |
| count | int | Antalet element i **content** som ingår i segmentet |
| writable | **bool** | Anger om strömmen ska vara skrivbar |
| publiclyVisible | **bool** | Anger om den underliggande minnesbufferten ska göras tillgänglig för anroparen av metoden GetByte() |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [MemoryStream](../)
* Namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)