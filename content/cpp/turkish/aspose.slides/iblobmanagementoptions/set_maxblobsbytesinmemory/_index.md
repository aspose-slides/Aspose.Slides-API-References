---
title: set_MaxBlobsBytesInMemory()
second_title: Aspose.Slides için C++ API Referansı
description: Tüm BLOB'ların bellekte kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu limit aşıldığında alternatif mekanizmalar (örneğin geçici dosyalar) kullanılır. BLOB'ların bellekte tutulması performansı maksimize eder fakat yüksek bellek kullanımına neden olabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın.
type: docs
weight: 92
url: /tr/aspose.slides/iblobmanagementoptions/set_maxblobsbytesinmemory/
---
## IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t) yöntemi

Tüm BLOB'ların bellekte kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; bu limit aşıldığında ancak alternatif mekanizmalar (örneğin geçici dosyalar) kullanılır. BLOB'ların bellekte tutulması performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği, davranışı ortamınıza veya gereksinimlerinize göre özelleştirmek için kullanın.

```cpp
virtual void Aspose::Slides::IBlobManagementOptions::set_MaxBlobsBytesInMemory(uint64_t value)=0
```

## Açıklamalar

Bu değer, [IBlobManagementOptions::set_IsTemporaryFilesAllowed](../set_istemporaryfilesallowed/) false olarak ayarlandığında yok sayılır, çünkü o zaman bellek tek kullanılabilir depolama konumu olur ve bellekteki BLOB kullanımını sınırlamak bir etki yaratmaz.  

Varsayılan değer 629.145.600 bayt (600 MB)'dir.  

Bu özelliği sıfıra ayarlayabilirsiniz, ancak yine de küçük bir minimum bellek miktarı ayrılacaktır. 

## Ayrıca Bakınız

* Sınıf [IBlobManagementOptions](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)