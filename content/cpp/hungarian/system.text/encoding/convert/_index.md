---
title: Convert()
second_title: Aspose.Slides for C++ API referencia
description: Átalakítja a bájtokat két kódolás között.
type: docs
weight: 378
url: /hu/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) metódus

Átalakítja a bájtokat két kódolás között.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Forráskódolás. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Célkódolás. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Átalakítandó bájtok. |

### Visszatérési érték

Átalakított bájtok.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) metódus

Átalakítja a bájtokat két kódolás között.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Forráskódolás. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Célkódolás. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Átalakítandó bájtok. |
| index | int | Szelet kezdete. |
| count | int | Szelet mérete. |

### Visszatérési érték

Átalakított bájtok.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Osztály [Encoding](../)
* Névtér [System::Text](../../)
* Könyvtár [Aspose.Slides](../../../)