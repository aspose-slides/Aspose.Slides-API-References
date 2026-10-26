---
title: GetByteCount()
second_title: Aspose.Slides voor C++ API-referentie
description: Berekent het aantal bytes dat nodig is om een buffer te coderen.
type: docs
weight: 40
url: /nl/system.text/icuencoder/getbytecount/
---
## ICUEncoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) methode


Berekent het aantal bytes dat nodig is om een buffer te coderen.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Tekens om te coderen. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Aantal tekens om te coderen. |
| flush | **bool** | Als true, wordt de interne encoderstatus na de berekening opgeschoond. |

### Retourwaarde

Aantal bytes dat nodig is om de buffer te coderen.

## ICUEncoder::GetByteCount(const char_t *, int, bool) methode


Berekent het aantal bytes dat nodig is om een buffer te coderen.

```cpp
virtual int System::Text::ICUEncoder::GetByteCount(const char_t *chars, int count, bool flush)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| chars | const char_t * | Tekens om te coderen. |
| count | int | Aantal tekens om te coderen. |
| flush | **bool** | Als true, wordt de interne encoderstatus na de berekening opgeschoond. |

### Retourwaarde

Aantal bytes dat nodig is om de buffer te coderen.

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [ICUEncoder](../)
* Naamruimte [System::Text](../../)
* Bibliotheek [Aspose.Slides](../../../)