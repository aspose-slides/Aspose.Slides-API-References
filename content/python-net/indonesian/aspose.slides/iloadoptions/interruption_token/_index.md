---
title: interruption_token property
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/iloadoptions/interruption_token/
weight: 80
---
## interruption_token properti
Token untuk memantau permintaan interupsi.
            
            Token ini mengelola seluruh masa hidup instance [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation). Setiap operasi yang berjalan lama, seperti pemuatan atau penyimpanan presentasi, akan diinterupsi melalui pemanggilan metode [`IInterruptionTokenSource.interrupt`](/slides/python-net/id/aspose.slides/iinterruptiontokensource/interrupt) dari [`IInterruptionTokenSource`](/slides/python-net/id/aspose.slides/iinterruptiontokensource).

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
* kelas [`IInterruptionTokenSource`](/slides/python-net/id/aspose.slides/iinterruptiontokensource)
* kelas [`ILoadOptions`](/slides/python-net/id/aspose.slides/iloadoptions)
* kelas [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* perpustakaan [`Aspose.Slides`](/slides/python-net)