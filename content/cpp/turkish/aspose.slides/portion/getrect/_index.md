---
title: GetRect()
second_title: Aspose.Slides için C++ API Referansı
description: Portion'ı sınırlayan rect'in koordinatlarını al. rect, portion içinde metnin tüm satırlarını, boş olanlar da dahil, içerir.
type: docs
weight: 92
url: /tr/aspose.slides/portion/getrect/
---
## Portion::GetRect() yöntemi


Portion'ı sınırlayan rect'in koordinatlarını al. Rect, portion içindeki metnin tüm satırlarını, boş olanlar da dahil, içerir.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## Açıklamalar


Örnek: 
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

## Ayrıca Bakınız

* Sınıf [RectangleF](../../../system.drawing/rectanglef/)
* Sınıf [Portion](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)