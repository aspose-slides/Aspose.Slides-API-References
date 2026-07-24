---
title: Convert()
second_title: Aspose.Slides für C++ API Referenz
description: Konvertiert Bytes zwischen zwei Codierungen.
type: docs
weight: 378
url: /de/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) method

Konvertiert Bytes zwischen zwei Codierungen.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Quellcodierung. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Zielcodierung. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Zu konvertierende Bytes. |

### Rückgabewert

Konvertierte Bytes.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) method

Konvertiert Bytes zwischen zwei Codierungen.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Quellcodierung. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Zielcodierung. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Zu konvertierende Bytes. |
| index | int | Beginn des Ausschnitts. |
| count | int | Größe des Ausschnitts. |

### Rückgabewert

Konvertierte Bytes.

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasse [Encoding](../)
* Namensraum [System::Text](../../)
* Bibliothek [Aspose.Slides](../../../)