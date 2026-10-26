---
title: MemoryStream()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van de MemoryStream-klasse met een initiële capaciteit gelijk aan 0.
type: docs
weight: 1
url: /nl/system.io/memorystream/memorystream/
---
## MemoryStream::MemoryStream() constructor


Construeert een nieuw exemplaar van de [MemoryStream](../) klasse met een initiële capaciteit gelijk aan 0.

```cpp
System::IO::MemoryStream::MemoryStream()
```

## MemoryStream::MemoryStream(int) constructor


Construeert een nieuw exemplaar van de [MemoryStream](../) klasse die een stroom vertegenwoordigt die gebaseerd is op een geheugebuffer van de opgegeven grootte.

```cpp
System::IO::MemoryStream::MemoryStream(int capacity_)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| capacity_ | int | De grootte in bytes van een geheugebuffer die is gekoppeld aan de stroom die door het te creëren object wordt vertegenwoordigd |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, bool) constructor


Construeert een nieuw exemplaar van de [MemoryStream](../) klasse die een geheugenstroom vertegenwoordigt die is gekoppeld aan de opgegeven geheugebuffer. Een parameter geeft aan of de stroom beschrijfbaar is.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, bool writable=1)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Een byte-array die wordt gebruikt als geheugebuffer waarop de stroom die door het te creëren object wordt vertegenwoordigd, is gebaseerd |
| writable | **bool** | Geeft aan of de stroom beschrijfbaar moet zijn |

## MemoryStream::MemoryStream(const ArrayPtr\<uint8_t\>\&, int, int, bool, bool) constructor


Construeert een nieuw exemplaar van de [MemoryStream](../) klasse die een geheugenstroom vertegenwoordigt die is gekoppeld aan een segment van de opgegeven geheugebuffer beginnend op de opgegeven index en inclusief het opgegeven aantal elementen. Parameters geven aan of de stroom beschrijfbaar is en of de methode GetBytes() kan worden aangeroepen.

```cpp
System::IO::MemoryStream::MemoryStream(const ArrayPtr<uint8_t> &content, int index, int count, bool writable=1, bool publiclyVisible=false)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| content | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Een byte-array waarvan een segment wordt gebruikt als geheugebuffer waarop de stroom die door het te creëren object wordt vertegenwoordigd, is gebaseerd |
| index | int | Een index vanaf 0 van het element in **content** waar het segment begint |
| count | int | Het aantal elementen van **content** dat in het segment is inbegrepen |
| writable | **bool** | Geeft aan of de stroom beschrijfbaar moet zijn |
| publiclyVisible | **bool** | Geeft aan of de onderliggende geheugebuffer beschikbaar moet worden gemaakt voor de aanroeper van de methode GetByte() |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [MemoryStream](../)
* Naamruimte [System::IO](../../)
* Library [Aspose.Slides](../../../)