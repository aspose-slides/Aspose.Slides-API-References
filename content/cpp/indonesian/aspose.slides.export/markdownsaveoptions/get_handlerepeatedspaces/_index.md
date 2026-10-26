---
title: get_HandleRepeatedSpaces()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan bagaimana karakter spasi reguler yang berulang harus diproses selama ekspor Markdown.
type: docs
weight: 235
url: /id/aspose.slides.export/markdownsaveoptions/get_handlerepeatedspaces/
---
## MarkdownSaveOptions::get_HandleRepeatedSpaces() const metode


Menentukan bagaimana karakter spasi reguler berulang harus diproses selama ekspor Markdown.

```cpp
Aspose::Slides::Export::HandleRepeatedSpaces Aspose::Slides::Export::MarkdownSaveOptions::get_HandleRepeatedSpaces() const
```

## Keterangan


Properti ini menentukan apakah spasi berurutan akan:* dipertahankan sebagai karakter spasi biasa,
* ditukar secara bergantian antara spasi biasa dan entitas spasi tak terputus (**&nbsp;**),
* atau sepenuhnya diganti (setelah yang pertama) dengan **&nbsp;** untuk mempertahankan penyelarasan visual dalam output Markdown.



Nilai default adalah [HandleRepeatedSpaces::AlternateSpacesToNbsp](../../handlerepeatedspaces/). 
## Lihat Juga

* Enum [HandleRepeatedSpaces](../../handlerepeatedspaces/)
* Class [MarkdownSaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)