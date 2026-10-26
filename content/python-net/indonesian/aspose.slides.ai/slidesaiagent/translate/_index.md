---
title: translate method
second_title: Aspose.Slides untuk Python via .NET API Referensi
description: 
type: docs
url: /id/aspose.slides.ai/slidesaiagent/translate/
weight: 30
---
## translate(self, presentation, language) {#ipresentation-str}
Menerjemahkan sebuah presentasi ke bahasa yang ditentukan menggunakan AI (versi sinkron).

```python
def translate(self, presentation, language):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| presentation | [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation) | Target presentation |
| language | **str** | Target language |

### Keterangan

Contoh di bawah menggunakan [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient) default, yang dibuat oleh konstruktor **SlidesAIAgent.#ctor** tanpa parameter dan terhubung ke LLM milik Aspose. Untuk menggunakan penyedia AI yang berbeda, sediakan LLM Anda sendiri, atau sesuaikan koneksi (misalnya, dengan menyediakan `HttpClient` Anda sendiri), kirimkan implementasi [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient) ke konstruktor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Implementasi yang tersedia meliputi:

* [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/id/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/id/aspose.slides.ai/openaicompatiblewebclient)

### Pengecualian

| Pengecualian | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Presentation instance is not provided |
| **RuntimeError(Proxy error(ArgumentException))** | Language value can't be None or empty |

### Lihat Juga
* kelas [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient)
* kelas [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient)
* kelas [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation)
* kelas [`OpenAICompatibleWebClient`](/slides/python-net/id/aspose.slides.ai/openaicompatiblewebclient)
* kelas [`OpenAIWebClient`](/slides/python-net/id/aspose.slides.ai/openaiwebclient)
* kelas [`SlidesAIAgent`](/slides/python-net/id/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/id/aspose.slides.ai)
* pustaka [`Aspose.Slides`](/slides/python-net)