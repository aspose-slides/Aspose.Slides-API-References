---
title: generate_presentation method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.ai/slidesaiagent/generate_presentation/
weight: 20
---
## generate_presentation(self, description, presentation_content_amount) {#str-presentationcontentamounttype}
Membuat instance presentasi dari deskripsi teks. Berikan topik, ide, kutipan, atau cuplikan teks dalam bahasa yang diperlukan.


```python
def generate_presentation(self, description, presentation_content_amount):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| description | **str** | Topik, ide, kutipan, atau cuplikan teks. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/id/aspose.slides.ai/presentationcontentamounttype) | Jumlah konten dalam presentasi yang dihasilkan. |

### Catatan

Contoh di bawah ini menggunakan [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient) default, yang dibuat oleh konstruktor **SlidesAIAgent.#ctor** tanpa parameter dan terhubung ke LLM milik Aspose. Untuk menggunakan penyedia AI yang berbeda, sediakan LLM Anda sendiri, atau sesuaikan koneksi (misalnya, dengan menyediakan `HttpClient` Anda sendiri), berikan implementasi [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient) ke konstruktor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Implementasi yang tersedia meliputi:
             
* [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/id/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/id/aspose.slides.ai/openaicompatiblewebclient)

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Instruksi obrolan AI tidak boleh None atau kosong. |


## generate_presentation(self, description, presentation_content_amount, presentation_template) {#str-presentationcontentamounttype-ipresentation}
Membuat instance presentasi dari deskripsi teks. Berikan topik, ide, kutipan, atau cuplikan teks dalam bahasa yang diperlukan.


```python
def generate_presentation(self, description, presentation_content_amount, presentation_template):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| description | **str** | Topik, ide, kutipan, atau cuplikan teks. |
| presentation_content_amount | [`PresentationContentAmountType`](/slides/python-net/id/aspose.slides.ai/presentationcontentamounttype) | Jumlah konten dalam presentasi yang dihasilkan. |
| presentation_template | [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation) | Sebuah presentasi yang digunakan sebagai template untuk tata letak dan desain, menggantikan template default. |

### Catatan

Contoh di bawah ini menggunakan [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient) default, yang dibuat oleh konstruktor **SlidesAIAgent.#ctor** tanpa parameter dan terhubung ke LLM milik Aspose. Untuk menggunakan penyedia AI yang berbeda, sediakan LLM Anda sendiri, atau sesuaikan koneksi (misalnya, dengan menyediakan `HttpClient` Anda sendiri), berikan implementasi [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient) ke konstruktor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**. Implementasi yang tersedia meliputi:
            
* [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient)
* [`OpenAIWebClient`](/slides/python-net/id/aspose.slides.ai/openaiwebclient)
* [`OpenAICompatibleWebClient`](/slides/python-net/id/aspose.slides.ai/openaicompatiblewebclient)

### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Template presentasi tidak disediakan. |
| **RuntimeError(Proxy error(ArgumentException))** | Instruksi obrolan AI tidak boleh None atau kosong. |



### Lihat Juga
* kelas [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient)
* kelas [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient)
* kelas [`IPresentation`](/slides/python-net/id/aspose.slides/ipresentation)
* kelas [`OpenAICompatibleWebClient`](/slides/python-net/id/aspose.slides.ai/openaicompatiblewebclient)
* kelas [`OpenAIWebClient`](/slides/python-net/id/aspose.slides.ai/openaiwebclient)
* enumerasi [`PresentationContentAmountType`](/slides/python-net/id/aspose.slides.ai/presentationcontentamounttype)
* kelas [`SlidesAIAgent`](/slides/python-net/id/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/id/aspose.slides.ai)
* perpustakaan [`Aspose.Slides`](/slides/python-net)