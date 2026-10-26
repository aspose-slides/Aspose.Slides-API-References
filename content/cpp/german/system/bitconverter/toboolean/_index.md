---
title: ToBoolean()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert ein Byte aus dem angegebenen Array, beginnend am angegebenen Index, in einen booleschen Wert.
type: docs
weight: 27
url: /de/system/bitconverter/toboolean/
---
## BitConverter::ToBoolean(const System::ArrayPtr\<uint8_t\>\&, int) Methode


Konvertiert ein Byte aus dem angegebenen Array, beginnend am angegebenen Index, in einen boolean-Wert.

```cpp
static bool System::BitConverter::ToBoolean(const System::ArrayPtr<uint8_t> &value, int startIndex)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die Bytes zum Konvertieren enthält |
| startIndex | int | [Index](../../index/) im Array, an dem mit dem Entnehmen von Bytes für die Konvertierung begonnen werden soll |

### Rückgabewert

[Boolean](../../boolean/) Wert, der aus der Konvertierung resultiert

## BitConverter::ToBoolean(const System::Details::ArrayView\<uint8_t\>\&, int) Methode


Konvertiert ein Byte aus dem angegebenen Array, beginnend am angegebenen Index, in einen boolean-Wert.

```cpp
static bool System::BitConverter::ToBoolean(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, das Bytes zum Konvertieren enthält |
| startIndex | int | [Index](../../index/) im Array, an dem mit dem Entnehmen von Bytes für die Konvertierung begonnen werden soll |

### Rückgabewert

[Boolean](../../boolean/) Wert, der aus der Konvertierung resultiert

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)