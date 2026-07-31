---
title: ApplyDefaultParagraphIndentsShifts()
second_title: Referensi API Aspose.Slides untuk C++
description: "Menetapkan pergeseran non-nol default untuk Indent paragraf efektif dan MarginLeft ketika bullets diaktifkan (seperti yang dilakukan PowerPoint bila mengaktifkan paragraph bullets/numbering di dalamnya). Jika bullets dinonaktifkan maka hanya mengatur ulang Indent paragraf dan MarginLeft (seperti yang dilakukan PowerPoint bila menonaktifkan paragraph bullets/numbering di dalamnya). Indents shifts diterapkan terkait konteks bullet saat ini - IBulletFormat::get(set)_Type, .NumberedBulletStyle dan FontHeight dari bagian pertama. Non-zero indents shifts diterapkan ke Indent dan MarginLeft efektif dari paragraf saat ini (menjadikan nilai hasil sebagai nilai lokal)."
type: docs
weight: 235
url: /id/aspose.slides/bulletformat/applydefaultparagraphindentsshifts/
---
## BulletFormat::ApplyDefaultParagraphIndentsShifts() metode


Menetapkan pergeseran non-nol default untuk Indent paragraf efektif dan MarginLeft ketika bullets diaktifkan (seperti yang dilakukan PowerPoint bila mengaktifkan bullets/penomoran paragraf di dalamnya). Jika bullets dinonaktifkan maka hanya mengatur ulang Indent paragraf dan MarginLeft (seperti yang dilakukan PowerPoint bila menonaktifkan bullets/penomoran paragraf di dalamnya). Pergeseran Indent diterapkan berdasarkan konteks bullet saat ini - IBulletFormat::get(set)_Type, .NumberedBulletStyle, dan FontHeight dari bagian pertama. Pergeseran Indent non-nol diterapkan ke Indent dan MarginLeft efektif dari paragraf saat ini (membuat nilai hasil menjadi nilai lokal).

```cpp
void Aspose::Slides::BulletFormat::ApplyDefaultParagraphIndentsShifts() override
```


## Lihat Juga

* Kelas [BulletFormat](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)