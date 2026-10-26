---
title: GetRect()
second_title: Referensi API Aspose.Slides untuk C++
description: Dapatkan koordinat rect yang membatasi bagian. Rect mencakup semua baris teks dalam bagian, termasuk yang kosong.
type: docs
weight: 79
url: /id/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() metode


Dapatkan koordinat rect yang membatasi bagian. Rect mencakup semua baris teks dalam bagian, termasuk yang kosong.

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```


### Nilai Kembali

Rectangle yang membatasi bagian [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)
## Catatan



Contoh: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::Rectangle, 50.0f, 50.0f, 200.0f, 50.0f);

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Clear();
auto portion0 = System::MakeObject<Portion>(u"Some text");
auto portion1 = System::MakeObject<Portion>(u"GetRect text");

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion0);
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion1);

auto rect = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(1)->GetRect();
// ...
```

## Lihat Juga

* Kelas [RectangleF](../../../system.drawing/rectanglef/)
* Kelas [IPortion](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)