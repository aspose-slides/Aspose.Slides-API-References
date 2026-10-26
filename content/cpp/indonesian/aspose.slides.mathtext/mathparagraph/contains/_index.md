---
title: Contains()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan apakah koleksi berisi nilai tertentu.
type: docs
weight: 118
url: /id/aspose.slides.mathtext/mathparagraph/contains/
---
## MathParagraph::Contains(System::SharedPtr\<IMathBlock\>) metode

Menentukan apakah koleksi berisi nilai tertentu.

```cpp
bool Aspose::Slides::MathText::MathParagraph::Contains(System::SharedPtr<IMathBlock> mathBlock) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | Objek yang akan dicari dalam koleksi. |

### Nilai Kembali

true jika *mathBlock* ditemukan dalam koleksi; jika tidak, false.

## Catatan



Contoh: 
```cpp
auto shape = slide->get_Shapes()->AddMathShape(x, y, width, height);
auto mathParagraph = (System::AsCast<MathPortion>(shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)))->get_MathParagraph();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
mathParagraph->Add(block);
bool contains = mathParagraph->Contains(block);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IMathBlock](../../imathblock/)
* Kelas [MathParagraph](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)