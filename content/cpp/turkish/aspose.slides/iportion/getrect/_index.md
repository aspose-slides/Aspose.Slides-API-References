---
title: GetRect()
second_title: Aspose.Slides için C++ API Referansı
description: Bölümü sınırlayan dikdörtgenin koordinatlarını al. Dikdörtgen, bölmedeki tüm metin satırlarını, boş olanlar da dahil, içerir.
type: docs
weight: 79
url: /tr/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() metod

Bölümü sınırlayan dikdörtgenin koordinatlarını al. Dikdörtgen, bölmedeki tüm metin satırlarını, boş olanlar da dahil, içerir.

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```

### Dönüş Değeri

Bölümü sınırlayan dikdörtgen [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)

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
* Sınıf [IPortion](../)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)