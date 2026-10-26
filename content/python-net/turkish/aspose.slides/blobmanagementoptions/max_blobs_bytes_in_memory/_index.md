---
title: max_blobs_bytes_in_memory property
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/blobmanagementoptions/max_blobs_bytes_in_memory/
weight: 30
---
## max_blobs_bytes_in_memory özelliği
Bellekte tüm BLOB'ların kaplayabileceği azami toplam boyutu (bayt olarak) tanımlar. Varsayılan olarak, tüm BLOB'lar belleğe yüklenir; yalnızca bu sınır aşıldığında geçici dosyalar gibi alternatif mekanizmalar kullanılır. BLOB'ları bellekte tutmak performansı en üst düzeye çıkarır ancak yüksek bellek kullanımına yol açabilir. Bu özelliği ortamınıza veya gereksinimlerinize göre davranışı özelleştirmek için kullanın.

### Açıklamalar

Bu özellik [`BlobManagementOptions.is_temporary_files_allowed`](/slides/python-net/tr/aspose.slides/blobmanagementoptions/is_temporary_files_allowed) false olarak ayarlandığında yok sayılır, çünkü o zaman bellek tek kullanılabilir depolama konumu olur ve bellek içi BLOB kullanımını sınırlamanın bir etkisi olmaz.

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
* sınıf [`BlobManagementOptions`](/slides/python-net/tr/aspose.slides/blobmanagementoptions)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)