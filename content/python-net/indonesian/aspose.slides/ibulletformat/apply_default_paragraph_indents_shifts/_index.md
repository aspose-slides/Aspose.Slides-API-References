---
title: apply_default_paragraph_indents_shifts method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ibulletformat/apply_default_paragraph_indents_shifts/
weight: 10
---
## apply_default_paragraph_indents_shifts(self) {#}
Menetapkan pergeseran non-nol default untuk Indent dan MarginLeft paragraf yang efektif ketika bullet diaktifkan (seperti yang dilakukan PowerPoint jika mengaktifkan bullet/penomoran paragraf). Jika bullet dinonaktifkan, maka hanya mengatur ulang Indent dan MarginLeft paragraf (seperti yang dilakukan PowerPoint jika menonaktifkan bullet/penomoran paragraf). Pergeseran indent diterapkan dengan mempertimbangkan konteks bullet saat ini - IBulletFormat.Type, .NumberedBulletStyle, dan FontHeight bagian pertama. Pergeseran indent non-nol diterapkan pada Indent dan MarginLeft paragraf yang efektif (membuat nilai hasil menjadi nilai lokal).


```python
def apply_default_paragraph_indents_shifts(self):
    ...
```


### Pengecualian

| Exception | Deskripsi |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Memanggil metode ini tidak penting dan akan melempar **System.InvalidOperationException** dalam kasus berikut:<br/>            jika objek format induk bukan paragraf (misalnya memanggil ITextStyle.DefaultParagraphFormat.Bullet.ApplyDefaultParagraphIndentsShifts() akan melempar pengecualian);<br/>            atau jika paragraf belum ditambahkan ke koleksi ITextFrame.Paragraphs mana pun (tambahkan terlebih dahulu); |



### Lihat Juga
* kelas [`IBulletFormat`](/slides/python-net/id/aspose.slides/ibulletformat)
* modul [`aspose.slides`](/slides/python-net/id/aspose.slides)
* pustaka [`Aspose.Slides`](/slides/python-net)