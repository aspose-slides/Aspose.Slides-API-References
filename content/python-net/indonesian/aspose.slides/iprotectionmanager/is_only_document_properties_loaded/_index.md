---
title: is_only_document_properties_loaded property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded properti
Properti ini masuk akal, jika file presentasi dilindungi kata sandi dan properti dokumen dari file ini bersifat publik.
Nilai true berarti hanya properti dokumen yang dimuat dari file presentasi yang terenkripsi tanpa menggunakan kata sandi.
Nilai false berarti seluruh presentasi yang terenkripsi dimuat dengan menggunakan kata sandi yang benar, tidak hanya properti dokumen yang dimuat.
Jika presentasi tidak terenkripsi maka nilai properti selalu false.
Jika properti dokumen dari file terenkripsi tidak bersifat publik maka nilai properti selalu false.
Jika PresentationEx.EncryptDocumentProperties bernilai true maka nilai properti IsOnlyDocumentPropertiesLoaded selalu false.
Baca-saja **bool**.

### Definisi:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Lihat Juga
* kelas [`IProtectionManager`](/slides/python-net/id/aspose.slides/iprotectionmanager)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)