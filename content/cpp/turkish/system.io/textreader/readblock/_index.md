---
title: ReadBlock()
second_title: Aspose.Slides for C++ API Referansı
description: Mevcut metin okuyucusundan belirtilen maksimum karakter sayısını okur ve verileri belirtilen index'ten başlayarak bir buffer'a yazar.
type: docs
weight: 53
url: /tr/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) yöntemi

Mevcut metin okuyucusundan belirtilen maksimum karakter sayısını okur ve verileri belirtilen index konumundan başlayarak buffer'a yazar.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```

### Argümanlar

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Okunan verinin yazılacağı bir karakter buffer |
| index | int | buffer içinde yazmaya başlanacak 0 tabanlı bir index |
| count | int | Okunacak maksimum karakter sayısı |

### Dönüş Değeri

Okunan gerçek karakter sayısı

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)