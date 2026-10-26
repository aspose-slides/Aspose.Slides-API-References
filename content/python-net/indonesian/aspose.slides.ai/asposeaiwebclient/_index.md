---
title: AsposeAIWebClient class
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.ai/asposeaiwebclient/
---
## AsposeAIWebClient kelas

Implementasi [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient) bawaan yang terhubung ke LLM milik Aspose.  
Ini adalah klien default yang digunakan oleh konstruktor **SlidesAIAgent.#ctor** tanpa parameter.

Tipe AsposeAIWebClient mengekspos anggota-anggota berikut:

## Konstruktor

| Konstruktor | Deskripsi |
| :- | :- |
| [`__init__(self)`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient/__init__/#) | Membuat sebuah instance dari klien web Aspose AI yang terhubung ke endpoint LLM Aspose default.<br/>            Ini adalah klien yang digunakan oleh konstruktor **SlidesAIAgent.#ctor** tanpa parameter, sehingga membuat<br/>            secara eksplisit hanya diperlukan saat mengirimkan klien ke konstruktor **Aspose.Slides.AI.SlidesAIAgent.#ctor(Aspose.Slides.A**<br/>            secara langsung. |
| [`__init__(self, url)`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient/__init__/#str) | Membuat sebuah instance dari klien web Aspose AI yang terhubung ke URL endpoint kustom. Gunakan overload ini<br/>            ketika Anda memiliki URL yang disediakan oleh tim Aspose.Slides; jika tidak, gunakan overload<br/>            **AsposeAIWebClient.#ctor** dengan URL default. |

## Metode

| Metode | Deskripsi |
| :- | :- |
| [`create_conversation(self)`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient/create_conversation/#) | Membuat sebuah instance percakapan. Tidak seperti panggilan AI reguler, percakapan mempertahankan seluruh konteks. |

### Lihat Juga
* kelas [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient)
* modul [`aspose.slides.ai`](/slides/python-net/id/aspose.slides.ai)
* pustaka [`Aspose.Slides`](/slides/python-net)