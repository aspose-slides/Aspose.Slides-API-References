---
title: GetRect()
second_title: Referência da API Aspose.Slides para C++
description: Obtenha as coordenadas do retângulo que delimita a porção. O retângulo inclui todas as linhas de texto na porção, incluindo as vazias.
type: docs
weight: 92
url: /pt/aspose.slides/portion/getrect/
---
## Portion::GetRect() método

Obtenha as coordenadas do retângulo que delimita a porção. O retângulo inclui todas as linhas de texto na porção, incluindo as vazias.

```cpp
System::Drawing::RectangleF Aspose::Slides::Portion::GetRect() override
```

## Observações

Exemplo:
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

## Veja também

* Classe [RectangleF](../../../system.drawing/rectanglef/)
* Classe [Portion](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)