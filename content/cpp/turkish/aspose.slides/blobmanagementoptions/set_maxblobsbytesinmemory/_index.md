---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides için C++ API Referansı
description: Bellekte tüm BLOB'ların kaplayabileceği maksimum toplam boyutu (bayt olarak) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; yalnızca bu sınıra ulaşıldığında geçici dosyalar gibi alternatif mekanizmalar kullanılır. BLOB'ları bellekte tutmak performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın.
type: docs
weight: 92
url: /tr/aspose.slides/blobmanagementoptions/set_maxblobsbytesinmemory/
---
## BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) metodu

Tüm BLOB'ların bellekte kaplayabileceği maksimum toplam boyutu (bayt olarak) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; yalnızca bu sınıra ulaşıldığında geçici dosyalar gibi alternatif mekanizmalar kullanılır. BLOB'ları bellekte tutmak performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın.

```cpp
void Aspose::Slides::BlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value) override
```

## Açıklamalar

Bu değer, [BlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) false olarak ayarlandığında yok sayılır, çünkü o zaman bellek tek kullanılabilir depolama konumu olur ve bellek içi BLOB kullanımını sınırlamak bir etki yaratmaz.  

Varsayılan değer 629,145,600 bayt (600 MB) dir.  

Bu özelliği sıfıra ayarlayabilirsiniz, ancak yine de küçük bir minimum bellek miktarı ayrılmış olur.  

## Ayrıca Bakınız

* Sınıf [BlobManagementOptions](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)