---
title: FromBase64CharArray()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Dekóduje data kódovaná v base-64, která jsou reprezentována jako rozsah v poli znaků Unicode.
type: docs
weight: 53
url: /cs/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) metoda


Dekóduje data kódovaná ve formátu base-64, která jsou reprezentována jako rozsah v poli znaků Unicode.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```


### Parametry

| Parametr | Typ | Popis |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Pole obsahující data k dekódování |
| offset | int | Pozice ve vstupním poli, kde začíná rozsah k dekódování |
| length | int | Délka rozsahu k dekódování |

### Návratová hodnota

Pole bajtů obsahující dekódovaná data

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)