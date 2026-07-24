---
title: FromBase64CharArray()
second_title: Aspose.Slides for C++ API Referansı
description: Unicode karakter dizisinde bir aralık olarak temsil edilen base-64 kodlu verileri çözer.
type: docs
weight: 53
url: /tr/system/convert/frombase64chararray/
---
## Convert::FromBase64CharArray(const ArrayPtr\<char_t\>\&, int, int) method


Unicode karakter dizisindeki bir aralık olarak temsil edilen base-64 kodlu verileri çözer.

```cpp
static ArrayPtr<uint8_t> System::Convert::FromBase64CharArray(const ArrayPtr<char_t> &in_array, int offset, int length)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| in_array | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Kod çözülecek verileri içeren dizi |
| offset | int | Kod çözülecek aralığın başladığı giriş dizisindeki konum |
| length | int | Kod çözülecek aralığın uzunluğu |

### Dönen Değer

Kod çözülen verileri içeren bir byte-dizi

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../arrayptr/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)