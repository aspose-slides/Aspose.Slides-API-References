---
title: GetRect()
second_title: Aspose.Slides untuk Referensi API C++
description: Dapatkan koordinat rect yang membatasi portion. Rect mencakup semua baris teks dalam portion, termasuk yang kosong.
type: docs
weight: 92
url: /id/aspose.slides/portion/getrect/
---
## Portion::GetRect() metode

Dapatkan koordinat rect yang melingkupi portion. Rect mencakup semua baris teks dalam portion, termasuk yang kosong.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

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
* Kelas [Portion](../)
* Ruang nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)