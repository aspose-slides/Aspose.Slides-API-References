---
title: Convert()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Převádí bajty mezi dvěma kódováními.
type: docs
weight: 378
url: /cs/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) metoda

Převádí bajty mezi dvěma kódováními.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Zdrojové kódování. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Cílové kódování. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bajty k převodu. |

### Návratová hodnota

Převedené bajty.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) metoda

Převádí bajty mezi dvěma kódováními.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Zdrojové kódování. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Cílové kódování. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bajty k převodu. |
| index | int | Začátek výřezu. |
| count | int | Velikost výřezu. |

### Návratová hodnota

Převedené bajty.

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Třída [Encoding](../)
* Jmenný prostor [System::Text](../../)
* Knihovna [Aspose.Slides](../../../)