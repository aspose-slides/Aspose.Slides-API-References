---
title: Write()
second_title: Aspose.Slides voor C++ API-referentie
description: Schrijft het opgegeven teken naar de stroom.
type: docs
weight: 40
url: /nl/system.io/stringwriter/write/
---
## StringWriter::Write(char_t) methode

Writes the specified character to the stream.

```cpp
virtual void System::IO::StringWriter::Write(char_t value) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | char_t | De te schrijven waarde |

## StringWriter::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) methode

Writes the specified subrange of characters from the specified character array to the stream.

```cpp
virtual void System::IO::StringWriter::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | De array die de te schrijven tekens bevat |
| index | **int32_t** | Een nulgebaseerde index van het element in **buffer** waar het te schrijven subbereik begint |
| count | **int32_t** | Het aantal tekens in het te schrijven subbereik |

## StringWriter::Write(const String\&) methode

Writes the specified string to the stream.

```cpp
virtual void System::IO::StringWriter::Write(const String &value) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | De te schrijven tekenreeks |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [StringWriter](../)
* Klasse [String](../../../system/string/)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)