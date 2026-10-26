---
title: Write()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft het opgegeven teken naar de stream.
type: docs
weight: 79
url: /nl/system.io/streamwriter/write/
---
## StreamWriter::Write(char_t) methode


Schrijft het opgegeven teken naar de stream.

```cpp
void System::IO::StreamWriter::Write(char_t value) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char_t | Het teken om te schrijven |

## StreamWriter::Write(const String\&) methode


Schrijft de opgegeven string naar de stream.

```cpp
void System::IO::StreamWriter::Write(const String &value) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | De string om te schrijven |

## StreamWriter::Write(const SharedPtr\<Object\>\&) methode


Schrijft de tekenreeksrepresentatie van het opgegeven object naar de stream.

```cpp
void System::IO::StreamWriter::Write(const SharedPtr<Object> &obj) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Het object om te schrijven |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&) methode


Schrijft alle tekens uit de opgegeven array naar de stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | De array met de te schrijven tekens |

## StreamWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) methode


Schrijft het opgegeven subbereik van UTF-16-tekens uit de opgegeven tekenarray naar de stream.

```cpp
void System::IO::StreamWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | De array met de te schrijven tekens |
| index | **int32_t** | Een index beginnend bij 0 van het element in **buffer** waar het te schrijven subbereik begint |
| count | **int32_t** | Het aantal tekens in het te schrijven subbereik; -1 geeft aan dat het subbereik eindigt wanneer de **buffer**-array eindigt |

## StreamWriter::Write(const char_t *) methode


Schrijft de opgegeven c-string naar de stream.

```cpp
void System::IO::StreamWriter::Write(const char_t *buffer) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const char_t * | De c-string om te schrijven |

## StreamWriter::Write(const System::SharedPtr\<T\>\&) methode


Schrijft de tekenreeksrepresentatie van het opgegeven object naar de stream.

```cpp
template<typename T> void System::IO::StreamWriter::Write(const System::SharedPtr<T> &obj)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Het type van het object |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [System::SharedPtr](../../../system/sharedptr/)\<T\>\& | Het object om te schrijven |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [StreamWriter](../)
* Klasse [String](../../../system/string/)
* Klasse [Object](../../../system/object/)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)