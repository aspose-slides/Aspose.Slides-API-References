---
title: Write()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft de tekenreeksweergave van het opgegeven object naar de stroom.
type: docs
weight: 105
url: /nl/system.io/textwriter/write/
---
## TextWriter::Write(const SharedPtr\<Object\>\&) methode


Schrijft de tekenreeksweergave van het opgegeven object naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(const SharedPtr<Object> &value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Het object om te schrijven |

## TextWriter::Write(bool) methode


Schrijft de tekenreeksweergave van de opgegeven boolean-waarde naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(bool value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | **bool** | De waarde om te schrijven |

## TextWriter::Write(char_t) methode


Schrijft het opgegeven teken naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(char_t value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | De waarde om te schrijven |

## TextWriter::Write(Decimal) methode


Schrijft de tekenreeksweergave van het opgegeven [Decimal](../../../system/decimal/)-object naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(Decimal value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | Het object om te schrijven |

## TextWriter::Write(double) methode


Schrijft de tekenreeksweergave van de opgegeven double-precisie floating-point-waarde naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(double value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | De waarde om te schrijven |

## TextWriter::Write(int) methode


Schrijft de tekenreeksweergave van de opgegeven 32-bit-integerwaarde naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(int value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | int | De waarde om te schrijven |

## TextWriter::Write(int64_t) methode


Schrijft de tekenreeksweergave van de opgegeven 64-bit-integerwaarde naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(int64_t value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | **int64_t** | De waarde om te schrijven |

## TextWriter::Write(float) methode


Schrijft de tekenreeksweergave van de opgegeven single-precisie floating-point-waarde naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(float value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | **float** | De waarde om te schrijven |

## TextWriter::Write(const String\&) methode


Schrijft de opgegeven tekenreeks naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(const String &value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | De tekenreeks om te schrijven |

## TextWriter::Write(uint32_t) methode


Schrijft de tekenreeksweergave van de opgegeven ongeondertekende 32-bit-integerwaarde naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(uint32_t value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint32_t** | De waarde om te schrijven |

## TextWriter::Write(uint64_t) methode


Schrijft de tekenreeksweergave van de opgegeven ongeondertekende 64-bit-integerwaarde naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(uint64_t value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint64_t** | De waarde om te schrijven |

## TextWriter::Write(const ArrayPtr\<char_t\>\&) methode


Schrijft alle tekens van de opgegeven array naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | De array die de te schrijven tekens bevat |

## TextWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) methode


Schrijft het opgegeven subbereik van UTF-16-tekens van de opgegeven karakterarray naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | De array die de te schrijven tekens bevat |
| index | **int32_t** | Een nul-gebaseerde index van het element in **buffer** waarop het te schrijven subbereik begint |
| count | **int32_t** | Het aantal tekens in het te schrijven subbereik; -1 geeft aan dat het subbereik eindigt waar de **buffer**-array eindigt |

## TextWriter::Write(const char_t *) methode


Schrijft de opgegeven c-string naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(const char_t *value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | De te schrijven c-string |

## TextWriter::Write(const TypeInfo\&) methode


Schrijft de tekenreeksweergave van het opgegeven [TypeInfo](../../../system/typeinfo/)-object naar de stroom.

```cpp
virtual void System::IO::TextWriter::Write(const TypeInfo &value)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | Het object om te schrijven |

## TextWriter::Write(const String\&, const TArgs\&...) methode


Schrijft de opgegeven waarden opgemaakt volgens het opgegeven formaat naar de stroom.

```cpp
template<class...> void System::IO::TextWriter::Write(const String &format, const TArgs &... args)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| TArgs | De lijst met typen van waarden die geschreven moeten worden |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Het tekenreeksformaat |
| args | const TArgs\&... | De waarden om te schrijven |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Object](../../../system/object/)
* Class [TextWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)