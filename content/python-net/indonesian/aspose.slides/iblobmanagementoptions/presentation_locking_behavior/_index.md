---
title: presentation_locking_behavior property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/iblobmanagementoptions/presentation_locking_behavior/
weight: 30
---
## presentation_locking_behavior properti
Properti ini menentukan apakah sebuah instance dari kelas Presentation dapat menjadi pemilik sumber - file 
            atau aliran selama masa hidup instance. Jika instance menjadi pemilik, ia mengunci sumber. Hal ini membantu 
            meningkatkan konsumsi memori dan kinerja saat bekerja dengan BLOB, namun sumber (aliran atau file) 
            tidak dapat diubah selama masa hidup instance Presentation. Ini adalah contoh:

### Definisi:
```python
@property
def presentation_locking_behavior(self):
    ...

@presentation_locking_behavior.setter
def presentation_locking_behavior(self, value):
    ...
```


### Lihat Juga
* kelas [`IBlobManagementOptions`](/slides/python-net/id/aspose.slides/iblobmanagementoptions)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)