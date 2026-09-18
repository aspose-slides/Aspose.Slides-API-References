---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/iblobmanagementoptions/max_blobs_bytes_in_memory/
weight: 20
---
## max_blobs_bytes_in_memory özelliği
Bellekte tüm BLOB'ların kaplayabileceği maksimum toplam boyutu (bayt cinsinden) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; yalnızca bu sınır aşılınca geçici dosyalar gibi alternatif mekanizmalar kullanılır. BLOB'ları bellekte tutmak performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın.


### Notlar

Bu özellik, [`IBlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/tr/aspose.slides/iblobmanagementoptions/is_temporary_files_allowed) false olarak ayarlandığında göz ardı edilir, çünkü o zaman bellek tek kullanılabilir depolama konumu olur ve bellekteki BLOB kullanımını sınırlamanın bir etkisi olmaz.

### Tanım:
```python
@property
def max_blobs_bytes_in_memory(self):
    ...

@max_blobs_bytes_in_memory.setter
def max_blobs_bytes_in_memory(self, value):
    ...
```


### Ayrıca Bakınız
* sınıf [`IBlobManagementOptions`](/slides/python-net/tr/aspose.slides/iblobmanagementoptions)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)