---
title: Convert()
second_title: Aspose.Slides dla referencji API C++
description: Konwertuje bajty pomiędzy dwoma kodowaniami.
type: docs
weight: 378
url: /pl/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) metoda

Konwertuje bajty pomiędzy dwoma kodowaniami.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie źródłowe. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie docelowe. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bajty do konwersji. |

### Wartość zwracana

Przekonwertowane bajty.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) metoda

Konwertuje bajty pomiędzy dwoma kodowaniami.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie źródłowe. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kodowanie docelowe. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Bajty do konwersji. |
| index | int | Początek fragmentu. |
| count | int | Rozmiar fragmentu. |

### Wartość zwracana

Przekonwertowane bajty.

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Klasa [Encoding](../)
* Przestrzeń nazw [System::Text](../../)
* Biblioteka [Aspose.Slides](../../../)