---
title: is_only_document_properties_loaded property
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/protectionmanager/is_only_document_properties_loaded/
weight: 90
---
## is_only_document_properties_loaded properti
Properti ini masuk akal jika file presentasi dilindungi kata sandi dan properti dokumen file ini bersifat publik.
Nilai true berarti hanya properti dokumen yang dimuat dari file presentasi yang terenkripsi tanpa menggunakan kata sandi.
Nilai false berarti seluruh presentasi yang terenkripsi dimuat dengan menggunakan kata sandi yang benar, bukan hanya properti dokumen yang dimuat.
Jika presentasi tidak terenkripsi, maka nilai properti selalu false.
Jika properti dokumen dari file yang terenkripsi tidak publik, maka nilai properti selalu false.
Jika Presentation.EncryptDocumentProperties bernilai true, maka nilai properti IsOnlyDocumentPropertiesLoaded selalu false.
Hanya-baca **bool**.

### Definisi:
```python
@property
def is_only_document_properties_loaded(self):
    ...
```

### Lihat Juga
* kelas [`ProtectionManager`](/slides/python-net/id/aspose.slides/protectionmanager)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)