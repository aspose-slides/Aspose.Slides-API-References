---
title: WriteLine()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft regeleinde-tekens naar de stream.
type: docs
weight: 92
url: /nl/system.io/streamwriter/writeline/
---
## StreamWriter::WriteLine() methode

Schrijft regeleinde-tekens naar de stream.

```cpp
void System::IO::StreamWriter::WriteLine() override
```

## StreamWriter::WriteLine(const String\&) methode

Schrijft de opgegeven string, gevolgd door de regeleinde-tekens, naar de stream.

```cpp
void System::IO::StreamWriter::WriteLine(const String &value) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | De te schrijven string |

## StreamWriter::WriteLine(const SharedPtr\<Object\>\&) methode

Schrijft de tekenreeksrepresentatie van het opgegeven object, gevolgd door de regeleinde-tekens, naar de stream.

```cpp
void System::IO::StreamWriter::WriteLine(const SharedPtr<Object> &obj) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Het object om te schrijven |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&) methode

Schrijft alle tekens van de opgegeven array, gevolgd door de regeleinde-tekens, naar de stream.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | De array die de te schrijven tekens bevat |

## StreamWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) methode

Schrijft het opgegeven deelbereik van UTF-16-tekens uit de opgegeven tekenarray, gevolgd door de regeleinde-tekens, naar de stream.

```cpp
void System::IO::StreamWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | De array die de te schrijven tekens bevat |
| index | **int32_t** | Een index beginnend bij 0 van het element in **buffer** waarop het te schrijven deelbereik begint |
| count | **int32_t** | Het aantal tekens in het deelbereik dat moet worden geschreven; -1 geeft aan dat het deelbereik eindigt wanneer de **buffer**-array eindigt |

## StreamWriter::WriteLine(const char_t *) methode

Schrijft de opgegeven c-string, gevolgd door de regeleinde-tekens, naar de stream.

```cpp
void System::IO::StreamWriter::WriteLine(const char_t *buffer) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const char_t * | De te schrijven c-string |

## StreamWriter::WriteLine(const System::SharedPtr\<T\>\&) methode

Schrijft de tekenreeksrepresentatie van het opgegeven object, gevolgd door de regeleinde-tekens, naar de stream.

```cpp
template<typename T> void System::IO::StreamWriter::WriteLine(const System::SharedPtr<T> &obj)
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
* Class [StreamWriter](../)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)