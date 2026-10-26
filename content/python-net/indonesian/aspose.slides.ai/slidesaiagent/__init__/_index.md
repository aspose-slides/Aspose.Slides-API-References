---
title: SlidesAIAgent constructor
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.ai/slidesaiagent/__init__/
weight: 10
---
## __init__(self) {#}
Menginisialisasi sebuah instance baru dari [`SlidesAIAgent`](/slides/python-net/id/aspose.slides.ai/slidesaiagent) menggunakan [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient) bawaan dengan konfigurasi defaultnya. Klien terhubung ke LLM milik Aspose dan tidak memerlukan konfigurasi tambahan. Untuk menggunakan klien AI yang berbeda, gunakan overload **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** sebagai gantinya.

```python
def __init__(self):
    ...
```

## __init__(self, ai_client) {#iaiwebclient}
Menginisialisasi sebuah instance baru dari [`SlidesAIAgent`](/slides/python-net/id/aspose.slides.ai/slidesaiagent) dengan klien AI khusus. Gunakan overload ini untuk menentukan penyedia AI, menyediakan LLM Anda sendiri, atau menyesuaikan koneksi (misalnya, dengan menyediakan `HttpClient` milik Anda). Implementasi apa pun dari [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient) dapat digunakan, termasuk:
* [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/id/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/id/aspose.slides.ai/openaicompatiblewebclient)

Untuk menggunakan [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient) bawaan dengan konfigurasi defaultnya, gunakan overload **SlidesAIAgent.#ctor** sebagai gantinya.

```python
def __init__(self, ai_client):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| ai_client | [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient) | Instansi klien AI. Implementasi apa pun dari [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient) dapat digunakan. |

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Instansi klien AI tidak disediakan. |

### Lihat Juga
* kelas [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient)
* kelas [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient)
* kelas [`OpenAICompatibleWebClient`](/slides/python-net/id/aspose.slides.ai/openaicompatiblewebclient)
* kelas [`OpenAIWebClient`](/slides/python-net/id/aspose.slides.ai/openaiwebclient)
* kelas [`SlidesAIAgent`](/slides/python-net/id/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/id/aspose.slides.ai)
* perpustakaan [`Aspose.Slides`](/slides/python-net)