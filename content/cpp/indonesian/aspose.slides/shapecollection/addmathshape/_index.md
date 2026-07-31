---
title: AddMathShape()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat auto shape persegi panjang baru untuk menampung konten matematika dan menambahkannya ke akhir koleksi shape.
type: docs
weight: 365
url: /id/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) method

Membuat sebuah auto shape persegi panjang baru untuk menampung konten matematika dan menambahkannya ke akhir koleksi shape.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| x | **float** | Koordinat x dari frame **shape**-nya, dalam poin. |
| y | **float** | Koordinat y dari frame **shape**-nya, dalam poin. |
| width | **float** | Lebar frame **shape**-nya, dalam poin. |
| height | **float** | Tinggi frame **shape**-nya, dalam poin. |

### Nilai Kembalian

Objek [IAutoShape](../../iautoshape/) yang baru dibuat.

## Catatan

Contoh berikut menunjukkan cara menambahkan Persamaan Matematis di PowerPoint [Presentation](../../presentation/).
```cpp
auto pres = System::MakeObject<Presentation>();

auto mathShape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 720.0f, 150.0f);
auto mathPortion = mathShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);
auto mathParagraph = (System::AsCast<MathPortion>(mathPortion))->get_MathParagraph();
auto fraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathParagraph->Add(System::MakeObject<MathBlock>(fraction));
auto a2 = System::MakeObject<MathematicalText>(u"a")->SetSuperscript(u"2");
auto b2 = System::MakeObject<MathematicalText>(u"b")->SetSuperscript(u"2");
auto c2 = System::MakeObject<MathematicalText>(u"c")->SetSuperscript(u"2");
auto mathBlock = c2->Join(u"=")->Join(a2)->Join(u"+")->Join(b2); // c^2 = a^2 + b^2
mathParagraph->Add(mathBlock);
pres->Save(u"math.pptx", SaveFormat::Pptx);
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)