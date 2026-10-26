---
title: only_load_document_properties property
second_title: Aspose.Slides untuk Python via .NET Referensi API
description: 
type: docs
url: /id/aspose.slides/iloadoptions/only_load_document_properties/
weight: 100
---
## only_load_document_properties properti
Properti ini masuk akal, bila file presentasi dilindungi kata sandi.
            Nilai true berarti hanya properti dokumen yang harus dimuat dari file presentasi yang dienkripsi dan kata sandi harus diabaikan.
            Nilai false berarti seluruh presentasi yang dienkripsi harus dimuat dengan menggunakan kata sandi yang benar.
            Jika presentasi tidak dienkripsi maka nilai properti selalu diabaikan.
            Jika properti dokumen dari file yang dienkripsi tidak bersifat publik dan nilai properti adalah true maka
            properti dokumen tidak dapat dimuat dan pengecualian akan dilempar.
            Baca-tulis **bool**.

### Definisi:
```python
@property
def only_load_document_properties(self):
    ...

@only_load_document_properties.setter
def only_load_document_properties(self, value):
    ...
```

### Lihat Juga
* kelas [`ILoadOptions`](/slides/python-net/id/aspose.slides/iloadoptions)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)