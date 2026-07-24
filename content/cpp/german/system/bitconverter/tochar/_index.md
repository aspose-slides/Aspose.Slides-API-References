---
title: ToChar()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, zu einem char_t-Wert.
type: docs
weight: 40
url: /de/system/bitconverter/tochar/
---
## BitConverter::ToChar(const System::ArrayPtr\<uint8_t\>\&, int) Methode

Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen char_t-Wert.

```cpp
static char_t System::BitConverter::ToChar(const System::ArrayPtr<uint8_t> &value, int startIndex)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [System::ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | [Array](../../array/) die Bytes zum Konvertieren enthält |
| startIndex | int | [Index](../../index/) im Array, an dem das Entnehmen der Bytes für die Konvertierung beginnen soll |

### Rückgabewert

char_t Wert, der aus der Konvertierung resultiert

## BitConverter::ToChar(const System::Details::ArrayView\<uint8_t\>\&, int) Methode

Konvertiert zwei Bytes aus dem angegebenen Array, beginnend am angegebenen Index, in einen char_t-Wert.

```cpp
static char_t System::BitConverter::ToChar(const System::Details::ArrayView<uint8_t> &value, int startIndex)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const System::Details::ArrayView\<**uint8_t**\>\& | ArrayView, das Bytes zum Konvertieren enthält |
| startIndex | int | [Index](../../index/) im Array, an dem das Entnehmen der Bytes für die Konvertierung beginnen soll |

### Rückgabewert

char_t Wert, der aus der Konvertierung resultiert

## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [BitConverter](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)