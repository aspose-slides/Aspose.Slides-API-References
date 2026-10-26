---
title: SlidesAIAgent class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.ai/slidesaiagent/
---
## SlidesAIAgent kelas

Menyediakan fitur berbasis AI untuk memproses presentasi.

Tipe SlidesAIAgent mengungkapkan anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self, ai_client)`](/slides/python-net/id/aspose.slides.ai/slidesaiagent/__init__/#iaiwebclient) | Menginisialisasi sebuah instance baru dari [`SlidesAIAgent`](/slides/python-net/id/aspose.slides.ai/slidesaiagent) dengan klien AI khusus.<br/>Gunakan overload ini untuk menentukan penyedia AI, menyediakan LLM Anda sendiri, atau menyesuaikan koneksi (misalnya, dengan menyediakan `HttpClient` milik Anda).<br/>Implementasi apa pun dari [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient) dapat digunakan, termasuk:<br/><br/>* [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient)<br/>* [`OpenAIWebClient`](/slides/python-net/id/aspose.slides.ai/openaiwebclient)<br/>* [`OpenAICompatibleWebClient`](/slides/python-net/id/aspose.slides.ai/openaicompatiblewebclient)<br/><br/><br/>Untuk menggunakan [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient) bawaan dengan konfigurasi defaultnya,<br/>gunakan overload **SlidesAIAgent.#ctor** sebagai gantinya. |
| [`__init__(self)`](/slides/python-net/id/aspose.slides.ai/slidesaiagent/__init__/#) | Menginisialisasi sebuah instance baru dari [`SlidesAIAgent`](/slides/python-net/id/aspose.slides.ai/slidesaiagent) menggunakan [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient) bawaan dengan konfigurasi defaultnya.<br/>Klien terhubung ke LLM milik Aspose dan tidak memerlukan konfigurasi tambahan.<br/>Untuk menggunakan klien AI yang berbeda, gunakan overload **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A** sebagai gantinya. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`generate_presentation(self, description, presentation_content_amount)`](/slides/python-net/id/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype) | Menghasilkan sebuah instance presentasi dari deskripsi teks. Berikan topik, ide, kutipan, atau potongan teks dalam bahasa yang diperlukan. |
| [`generate_presentation(self, description, presentation_content_amount, presentation_template)`](/slides/python-net/id/aspose.slides.ai/slidesaiagent/generate_presentation/#str-presentationcontentamounttype-ipresentation) | Menghasilkan sebuah instance presentasi dari deskripsi teks. Berikan topik, ide, kutipan, atau potongan teks dalam bahasa yang diperlukan. |
| [`translate(self, presentation, language)`](/slides/python-net/id/aspose.slides.ai/slidesaiagent/translate/#ipresentation-str) | Menerjemahkan presentasi ke bahasa yang ditentukan menggunakan AI (versi sinkron). |

### Lihat Juga
* kelas [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient)
* kelas [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient)
* kelas [`OpenAICompatibleWebClient`](/slides/python-net/id/aspose.slides.ai/openaicompatiblewebclient)
* kelas [`OpenAIWebClient`](/slides/python-net/id/aspose.slides.ai/openaiwebclient)
* kelas [`SlidesAIAgent`](/slides/python-net/id/aspose.slides.ai/slidesaiagent)
* modul [`aspose.slides.ai`](/slides/python-net/id/aspose.slides.ai)
* perpustakaan [`Aspose.Slides`](/slides/python-net)