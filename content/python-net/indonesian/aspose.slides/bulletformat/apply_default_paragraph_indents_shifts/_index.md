---
title: apply_default_paragraph_indents_shifts method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/bulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Menetapkan pergeseran default non-zero untuk Indent dan MarginLeft paragraf yang efektif ketika bullet diaktifkan (seperti yang dilakukan PowerPoint jika mengaktifkan bullet/penomoran paragraf di dalamnya). Jika bullet dinonaktifkan maka cukup mengatur ulang Indent dan MarginLeft paragraf (seperti yang dilakukan PowerPoint jika menonaktifkan bullet/penomoran paragraf di dalamnya). Pergeseran indent diterapkan berdasarkan konteks bullet saat ini — IBulletFormat.Type, .NumberedBulletStyle, dan FontHeight dari bagian pertama. Pergeseran indent non-zero diterapkan ke Indent dan MarginLeft paragraf yang efektif pada paragraf saat ini (menjadikan nilai hasil menjadi nilai lokal).

```python
def apply_default_paragraph_indents_shifts(self):
    ...
```

### Pengecualian

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Memanggil metode ini tidak penting dan akan melempar **System.InvalidOperationException** dalam kasus berikut:<br/>            if parent formatted object is not a paragraph (for example calling ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() will throw exception);<br/>            or if paragraph wasn't added to any ITextFrame.Paragraphs collection (add it first); |

### Lihat Juga
* kelas [`BulletFormat`](/slides/python-net/id/aspose.slides/bulletformat)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)