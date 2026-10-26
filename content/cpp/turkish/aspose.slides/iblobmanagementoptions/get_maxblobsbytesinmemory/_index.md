---
title: get_MaxBlobsBytesInMemory()
second_title: Aspose.Slides için C++ API Referansı
description: Bellekte tüm BLOB'ların kaplayabileceği maksimum toplam boyutu (bayt olarak) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu sınır ancak aşıldığında alternatif mekanizmalar (geçici dosyalar gibi) kullanılır. BLOB'ları bellekte tutmak performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın.
type: docs
weight: 79
url: /tr/aspose.slides/iblobmanagementoptions/get_maxblobsbytesinmemory/
---
## IBlobManagementOptions::get_MaxBlobsBytesInMemory() metodu


Bellekte tüm BLOB'ların kaplayabileceği maksimum toplam boyutu (bayt olarak) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu sınır yalnızca aşıldığında alternatif mekanizmalar (geçici dosyalar gibi) devreye alınır. BLOB'ları bellekte tutmak performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Davranışı ortamınıza veya gereksinimlerinize göre uyarlamak için bu özelliği kullanın.

```cpp
virtual uint64_t Aspose::Slides::IBlobManagementOptions::get_MaxBlobsBytesInMemory()=0
```

## Açıklamalar


Bu değer, [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) false olarak ayarlandığında yok sayılır, çünkü o zaman bellek tek kullanılabilir depolama konumu olur ve bellek içi BLOB kullanımını sınırlamanın etkisi olmaz. 

Varsayılan değer 629,145,600 bayt (600 MB)'dır. 

Bu özelliği sıfıra ayarlayabilirsiniz, ancak yine de küçük bir minimum bellek miktarı ayrılmış olur. 
## İlgili

* Sınıf [IBlobManagementOptions](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)