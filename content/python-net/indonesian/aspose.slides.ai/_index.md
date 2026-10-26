---
title: aspose.slides.ai
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides.ai/
---
Berisi kelas yang menyediakan fitur berbasis AI untuk menganalisis dan memproses presentasi PowerPoint.
## Kelas

| Kelas | Deskripsi |
| :- | :- |
| [`AsposeAIWebClient`](/slides/python-net/id/aspose.slides.ai/asposeaiwebclient/) | Implementasi [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient) bawaan yang terhubung ke LLM milik Aspose.<br/>            Ini adalah klien default yang digunakan oleh konstruktor **SlidesAIAgent.#ctor** tanpa parameter. |
| [`IAIConversation`](/slides/python-net/id/aspose.slides.ai/iaiconversation/) | Mewakili sebuah instance percakapan. Tidak seperti panggilan AI reguler, percakapan mempertahankan seluruh konteks. |
| [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient/) | Antarmuka klien AI Web. Antarmuka ini memungkinkan penggantian model bahasa AI yang berbeda.<br/>            Kelas yang mengimplementasikan antarmuka ini seharusnya digunakan bersama dengan `SlidesAIAgent`. |
| [`OpenAICompatibleWebClient`](/slides/python-net/id/aspose.slides.ai/openaicompatiblewebclient/) | Implementasi [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient) bawaan yang terhubung ke penyedia LLM yang kompatibel dengan OpenAI<br/>            pada URL dasar yang ditentukan. |
| [`OpenAIWebClient`](/slides/python-net/id/aspose.slides.ai/openaiwebclient/) | Implementasi [`IAIWebClient`](/slides/python-net/id/aspose.slides.ai/iaiwebclient) bawaan yang terhubung ke API OpenAI. |
| [`SlidesAIAgent`](/slides/python-net/id/aspose.slides.ai/slidesaiagent/) | Menyediakan fitur berbasis AI untuk memproses presentasi. |
| [`SlidesAIAgentException`](/slides/python-net/id/aspose.slides.ai/slidesaiagentexception/) | Mewakili pengecualian yang terkait dengan Slides AI Agent. |

## Enumerasi

| Enumerasi | Deskripsi |
| :- | :- |
| [`PresentationContentAmountType`](/slides/python-net/id/aspose.slides.ai/presentationcontentamounttype/) | Menentukan jumlah konten yang termasuk dalam presentasi yang dihasilkan, memengaruhi baik jumlah slide maupun tingkat detail per slide. |