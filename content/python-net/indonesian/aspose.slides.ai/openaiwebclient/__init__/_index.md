---
title: OpenAIWebClient constructor
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.ai/openaiwebclient/__init__/
weight: 10
---
## __init__(self, model, api_key, organization_id) {#str-str-str}
Membuat instance klien web OpenAI.


```python
def __init__(self, model, api_key, organization_id):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| model | **str** | Model bahasa OpenAI. Nilai yang mungkin:<br/><br/>              - gpt-4o<br/><br/>              - gpt-4o-mini<br/><br/>              - o1<br/><br/>              - o1-mini<br/><br/>              - o3<br/><br/>              - o3-mini |
| api_key | **str** | Kunci API OpenAI. |
| organization_id | **str** | ID Organisasi (opsional). |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Nilai kunci API tidak boleh None atau kosong. |
| **RuntimeError(Proxy error(ArgumentException))** | Nilai model teks tidak boleh None atau kosong. |



### Lihat Juga
* kelas [`OpenAIWebClient`](/slides/python-net/id/aspose.slides.ai/openaiwebclient)
* modul [`aspose.slides.ai`](/slides/python-net/id/aspose.slides.ai)
* pustaka [`Aspose.Slides`](/slides/python-net)