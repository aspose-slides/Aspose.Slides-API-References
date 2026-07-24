---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides for C++ API Referansı
description: Bellekte tüm BLOB'ların kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu sınır ulaştığında yalnızca geçici dosyalar gibi alternatif mekanizmalar kullanılır. BLOB'ları bellekte tutmak performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın.
type: docs
weight: 79
url: /tr/aspose.slides/blobmanagementoptions/get_maxblobsbytesinmemory/
---
## BlobManagementOptions::get_MaxBlobsBytesInMemory() yöntemi

Tüm BLOB'ların bellekte kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu sınır ulaştığında yalnızca geçici dosyalar gibi alternatif mekanizmalar kullanılır. BLOB'ları bellekte tutmak performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın.

```cpp
uint64_t Aspose::Slides::BlobManagementOptions::get_MaxBlobsBytesInMemory() override
```

## Açıklamalar

Bu değer, [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) false olarak ayarlandığında yok sayılır, çünkü o zaman yalnızca bellek kullanılabilir tek depolama konumudur ve bellekteki BLOB kullanımını sınırlamanın bir etkisi yoktur.

Varsayılan değer 629.145.600 bayt (600 MB)'dır.

Bu özelliği sıfıra ayarlayabilirsiniz, ancak yine de küçük bir minimum bellek miktarı ayrılacaktır.

## Ayrıca Bakınız

* Sınıf [BlobManagementOptions](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)