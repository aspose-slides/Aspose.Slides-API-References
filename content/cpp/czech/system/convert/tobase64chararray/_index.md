---
title: ToBase64CharArray()
second_title: Aspose.Slides pro C++ – reference API
description: Base-64 kóduje rozsah prvků ve specifikovaném poli bajtů a ukládá zakódovaná data jako pole znaků Unicode.
type: docs
weight: 27
url: /cs/system/convert/tobase64chararray/
---
## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char16_t\>\&, int, bool) metoda


Base-64 kóduje rozsah prvků ve zadaném poli bajtů a ukládá zakódovaná data jako pole znaků Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char16_t> &out_array, int offset_out, bool insert_line_breaks=false)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Pole bajtů obsahující rozsah prvků k zakódování |
| offset_in | int | Index prvku ve vstupním poli, kde začíná rozsah k zakódování |
| length | int | Délka rozsahu prvků k zakódování |
| out_array | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | Konstantní reference na výstupní pole, do kterého mají být umístěna výsledná data |
| offset_out | int | Index ve výstupním poli, kde začít umisťovat výsledná data |
| insert_line_breaks | **bool** | Určuje, zda mají být znaky zalomení řádku vloženy do výstupního pole po každých 76 znacích base-64 |

### Návratová hodnota

Počet znaků zapsaných do výstupního pole

## Convert::ToBase64CharArray(const ArrayPtr\<uint8_t\>\&, int, int, const ArrayPtr\<char_t\>\&, int, Base64FormattingOptions) metoda


Base-64 kóduje rozsah prvků ve zadaném poli bajtů a ukládá zakódovaná data jako pole znaků Unicode.

```cpp
static int System::Convert::ToBase64CharArray(const ArrayPtr<uint8_t> &in_array, int offset_in, int length, const ArrayPtr<char_t> &out_array, int offset_out, Base64FormattingOptions options)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Pole bajtů obsahující rozsah prvků k zakódování |
| offset_in | int | Index prvku ve vstupním poli, kde začíná rozsah k zakódování |
| length | int | Délka rozsahu prvků k zakódování |
| out_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Konstantní reference na výstupní pole, do kterého mají být umístěna výsledná data |
| offset_out | int | Index ve výstupním poli, kde začít umisťovat výsledná data |
| options | [Base64FormattingOptions](../../base64formattingoptions/) | Určuje možnosti formátování dat zakódovaných v base-64 |

### Návratová hodnota

Počet znaků zapsaných do výstupního pole

## Viz také

* Enum [Base64FormattingOptions](../../base64formattingoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)