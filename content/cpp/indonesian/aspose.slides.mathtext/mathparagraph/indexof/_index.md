---
title: IndexOf()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan indeks suatu IMathBlock tertentu dalam koleksi.
type: docs
weight: 131
url: /id/aspose.slides.mathtext/mathparagraph/indexof/
---
## MathParagraph::IndexOf(System::SharedPtr\<IMathBlock\>) metode


Menentukan indeks suatu [IMathBlock](../../imathblock/) tertentu dalam koleksi.

```cpp
int32_t Aspose::Slides::MathText::MathParagraph::IndexOf(System::SharedPtr<IMathBlock> mathBlock) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Item yang akan dicari dalam koleksi. |

### Nilai Kembali

Indeks *mathBlock* jika ditemukan dalam koleksi; jika tidak, -1.
## Catatan



Contoh: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
int32_t index = mathParagraph->IndexOf(block);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBlock](../../imathblock/)
* Kelas [MathParagraph](../)
* Ruang nama [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)