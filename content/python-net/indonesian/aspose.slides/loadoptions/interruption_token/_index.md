---
title: interruption_token property
second_title: Aspose.Slides untuk Python via Referensi API .NET
description: 
type: docs
url: /id/aspose.slides/loadoptions/interruption_token/
weight: 90
---
## interruption_token properti
Token untuk memantau permintaan interupsi.
            
            Token ini mengelola seluruh masa hidup instance [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). Setiap operasi yang memakan waktu lama, seperti memuat 
            atau menyimpan presentasi, akan diinterupsi dengan memanggil metode [`InterruptionTokenSource.interrupt`](/slides/python-net/id/aspose.slides/interruptiontokensource/interrupt) dari [`InterruptionTokenSource`](/slides/python-net/id/aspose.slides/interruptiontokensource).

### Definisi:
```python
@property
def interruption_token(self):
    ...

@interruption_token.setter
def interruption_token(self, value):
    ...
```

### Lihat Juga
* kelas [`InterruptionTokenSource`](/slides/python-net/id/aspose.slides/interruptiontokensource)
* kelas [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation)
* kelas [`LoadOptions`](/slides/python-net/id/aspose.slides/loadoptions)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)