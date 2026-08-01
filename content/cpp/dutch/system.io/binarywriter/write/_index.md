---
title: Write()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft de opgegeven unsigned 8-bit integerwaarde naar de uitgangsstroom.
type: docs
weight: 92
url: /nl/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) methode


Schrijft de opgegeven unsigned 8-bit integerwaarde naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **uint8_t** | De te schrijven waarde |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) methode


Schrijft het opgegeven subbereik van bytes uit de opgegeven byte-array naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | De array die de te schrijven bytes bevat |
| index | int | Een index beginnend bij 0 van het element in **buffer** waarop het te schrijven subbereik begint |
| count | int | Het aantal elementen in het te schrijven subbereik; -1 geeft aan dat het subbereik eindigt waar de **buffer**-array eindigt |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) methode


Schrijft het opgegeven subbereik van UTF-16-tekens uit de opgegeven teken-array naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | De array die de te schrijven tekens bevat |
| index | int | Een index beginnend bij 0 van het element in **buffer** waarop het te schrijven subbereik begint |
| count | int | Het aantal tekens in het te schrijven subbereik; -1 geeft aan dat het subbereik eindigt waar de **buffer**-array eindigt |

## BinaryWriter::Write(bool) methode


Schrijft een enkel byte met een waarde van 0 als **value** 'true' is en 1 als **value** 'false' is naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **bool** | De booleaanse waarde die de te schrijven bytewaarde bepaalt |

## BinaryWriter::Write(char16_t) methode


Schrijft de opgegeven 16-bit brede tekenwaarde naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char16_t | De te schrijven waarde |

## BinaryWriter::Write(int16_t) methode


Schrijft de opgegeven 16-bit integerwaarde naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **int16_t** | De te schrijven waarde |

## BinaryWriter::Write(int) methode


Schrijft de opgegeven 32-bit integerwaarde naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int | De te schrijven waarde |

## BinaryWriter::Write(int64_t) methode


Schrijft de opgegeven 64-bit integerwaarde naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **int64_t** | De te schrijven waarde |

## BinaryWriter::Write(uint16_t) methode


Schrijft de opgegeven unsigned 16-bit integerwaarde naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **uint16_t** | De te schrijven waarde |

## BinaryWriter::Write(uint32_t) methode


Schrijft de opgegeven unsigned 32-bit integerwaarde naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **uint32_t** | De te schrijven waarde |

## BinaryWriter::Write(uint64_t) methode


Schrijft de opgegeven unsigned 64-bit integerwaarde naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **uint64_t** | De te schrijven waarde |

## BinaryWriter::Write(float) methode


Schrijft de opgegeven enkelprecisie floating-pointwaarde naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **float** | De te schrijven waarde |

## BinaryWriter::Write(double) methode


Schrijft de opgegeven dubbelprecisie floating-pointwaarde naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | **double** | De te schrijven waarde |

## BinaryWriter::Write(const Decimal\&) methode


Schrijft de byte-representatie van de opgegeven [Decimal](../../../system/decimal/)-waarde naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | De te schrijven waarde |

## BinaryWriter::Write(const String\&) methode


Schrijft een lengte-geprefixeerde string in de huidige codering naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | De te schrijven string |

## BinaryWriter::Write(const char_t *) methode


Schrijft een lengte-geprefixeerde string in de huidige codering naar de uitgangsstroom.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const char_t * | De te schrijven c-string |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)