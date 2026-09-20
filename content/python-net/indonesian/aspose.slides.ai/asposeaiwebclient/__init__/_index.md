---
title: AsposeAIWebClient constructor
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.ai/asposeaiwebclient/__init__/
weight: 10
---
## __init__(self) {#}
Membuat sebuah instance dari klien web Aspose AI yang terhubung ke endpoint Aspose LLM default.
            Ini adalah klien yang digunakan oleh konstruktor **SlidesAIAgent.#ctor** tanpa parameter, sehingga membuatnya
            secara eksplisit hanya diperlukan ketika mengirimkan klien ke konstruktor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**
            secara langsung.


```python
def __init__(self):
    ...
```



## __init__(self, url) {#str}
Membuat sebuah instance dari klien web Aspose AI yang terhubung ke URL endpoint khusus. Gunakan overload ini ketika Anda memiliki URL yang disediakan oleh tim Aspose.Slides; jika tidak, gunakan overload **AsposeAIWebClient.#ctor** dengan URL default.


```python
def __init__(self, url):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| url | **str** | Endpoint URL dari Aspose LLM, disediakan oleh tim Aspose.Slides. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | URL tidak boleh None atau kosong. |



### Lihat Juga
* kelas [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient)
* modul [`aspose.slides.ai`](/slides/python-net/id/aspose.slides.ai)
* perpustakaan [`Aspose.Slides`](/slides/python-net)