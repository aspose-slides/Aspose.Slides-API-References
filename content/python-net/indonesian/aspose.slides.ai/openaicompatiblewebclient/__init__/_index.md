---
title: OpenAICompatibleWebClient constructor
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.ai/openaicompatiblewebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, base_url) {#str-str-str}
Membuat sebuah instance dari klien web yang kompatibel dengan OpenAI.


```python
def __init__(self, model, api_key, base_url):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| model | **str** | Nama model yang didukung oleh penyedia LLM. |
| api_key | **str** | Kunci API (token). |
| base_url | **str** | URL dasar dari LLM yang kompatibel dengan OpenAI. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nilai API key tidak boleh None atau kosong. |
| **RuntimeError(Proxy error(ArgumentException))** | Nilai model teks tidak boleh None atau kosong. |
| **RuntimeError(Proxy error(ArgumentException))** | Nilai Base URL tidak boleh None atau kosong. |



### Lihat Juga
* kelas [`OpenAICompatibleWebClient`](/slides/python-net/id/aspose.slides.ai/openaicompatiblewebclient)
* modul [`aspose.slides.ai`](/slides/python-net/id/aspose.slides.ai)
* pustaka [`Aspose.Slides`](/slides/python-net)